---
name: Record and pay an invoice against a contract (FinCon)
description: Add a paid invoice to a contract, register its payment, tag it, and read back the invoice detail in Alasco FinCon.
api: openapi/alasco-fincon-openapi.json
operations:
- get_contracts_contracts__get
- add_paid_invoice_invoices_add_paid_invoice__post
- register_payment_invoices__id__register_payment__post
- assign_tag_invoices__invoice_id__tags_assign__post
- get_invoice_details_invoices__id___get
---

# Record and pay an invoice against a contract (Alasco FinCon)

Base URL `https://api.alasco.de/fincon/v1`. Auth via `X-API-KEY` + `X-API-TOKEN`; trailing slashes required.

## Steps
1. **Find the contract** — `get_contracts_contracts__get` (`GET /contracts/`), filtering with `filter[...]` to locate the target contract.
2. **Add the paid invoice** — `add_paid_invoice_invoices_add_paid_invoice__post` (`POST /invoices/add-paid-invoice/`) referencing the contract.
3. **Register the payment** — `register_payment_invoices__id__register_payment__post` (`POST /invoices/{id}/register-payment/`).
4. **Tag the invoice** (optional) — `assign_tag_invoices__invoice_id__tags_assign__post` (`POST /invoices/{invoice_id}/tags/assign/`).
5. **Confirm** — `get_invoice_details_invoices__id___get` (`GET /invoices/{id}/`).

## Notes
- There is **no idempotency-key contract**; guard against duplicate posts client-side by checking existing invoices first.
- Corrections use `update_paid_invoice_invoices__id__update_paid_invoice__post`; removal uses `delete_paid_invoice_invoices__id___delete`.
