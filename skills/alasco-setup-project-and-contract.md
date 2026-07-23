---
name: Set up a project, property, and contract (FinCon)
description: Stand up a new real-estate development project in Alasco FinCon - create the property and project, register the contracting entity and contractor, then open a contract.
api: openapi/alasco-fincon-openapi.json
operations:
- create_property_properties__post
- create_project_projects__post
- create_contracting_entity_contracting_entities__post
- create_contractor_contractors__post
- create_contract_contracts__post
---

# Set up a project, property, and contract (Alasco FinCon)

Use the FinCon API (`https://api.alasco.de/fincon/v1`) to bootstrap a development project's cost structure.

## Auth & conventions
- Send both `X-API-KEY` and `X-API-TOKEN` headers on every request (see `authentication/alasco-authentication.yml`).
- Always use a **trailing slash** on endpoints (`/projects/`, not `/projects`) and follow 302/307 redirects.
- Responses follow JSON:API principles; page lists with `cursor[position]` and filter with `filter[<attr>.<op>]` (see `conventions/alasco-conventions.yml`).
- Validation failures return **422** with a `detail[]` of `{loc, msg, type}` (see `errors/alasco-problem-types.yml`).

## Steps
1. **Create the property** — `create_property_properties__post` (`POST /properties/`).
2. **Create the project** — `create_project_projects__post` (`POST /projects/`), linking it to the property.
3. **Register the contracting entity** — `create_contracting_entity_contracting_entities__post` (`POST /contracting_entities/`).
4. **Register the contractor** — `create_contractor_contractors__post` (`POST /contractors/`).
5. **Open the contract** — `create_contract_contracts__post` (`POST /contracts/`), referencing the contracting entity, contractor, and the project's cost elements.
6. Verify with `get_project_details_projects__id___get` and `get_contract_details_contracts__id___get`.
