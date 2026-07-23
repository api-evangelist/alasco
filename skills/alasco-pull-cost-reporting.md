---
name: Pull project and cost-element financial reporting (FinCon)
description: Read project, contract, and cost-element financials plus the cash-outflow view from Alasco FinCon reporting endpoints for dashboards and reconciliation.
api: openapi/alasco-fincon-openapi.json
operations:
- get_project_financials_reporting_projects__get
- get_contract_financials_reporting_contracts__get
- get_cost_element_financials_reporting_cost_elements__get
- get_cash_outflow_cost_element_view_reporting_cash_outflow_cost_elements__get
---

# Pull financial reporting (Alasco FinCon)

Base URL `https://api.alasco.de/fincon/v1`. Auth via `X-API-KEY` + `X-API-TOKEN`; trailing slashes required. All reporting endpoints are read-only GETs and page with `cursor[position]`.

## Steps
1. **Project financials** — `get_project_financials_reporting_projects__get` (`GET /reporting/projects/`) for budget vs. actual at the project level.
2. **Contract financials** — `get_contract_financials_reporting_contracts__get` (`GET /reporting/contracts/`).
3. **Cost-element financials** — `get_cost_element_financials_reporting_cost_elements__get` (`GET /reporting/cost_elements/`) for the cost-tree breakdown.
4. **Cash-outflow view** — `get_cash_outflow_cost_element_view_reporting_cash_outflow_cost_elements__get` (`GET /reporting/cash_outflow/cost_elements/`) for forecast/actual cash outflow.

## Notes
- Use `include` to pull related resources inline and reduce round-trips.
- Combine with `get_cost_element_contract_financials_reporting_cost_elements_contracts__get` for the contract-by-cost-element matrix.
