---
name: Onboard a supplier
description: Create a supplier company and its contacts in Workday Strategic Sourcing and classify it with categories, groups, and segmentation.
api: openapi/scoutrfp-suppliers-v1-openapi.json
operations:
  - Create a Supplier Company
  - Get a Supplier Company
  - Create a Supplier Contact
  - Create a Supplier Category
  - Create a Supplier Company Segmentation
---

# Onboard a supplier

Use the Workday Strategic Sourcing **Suppliers API** (`https://api.us.workdayspend.com/services/suppliers/v1`) to add a supplier company, attach contacts, and classify it.

## Auth & conventions
- Headers: `X-Api-Key`, `X-User-Token`, `X-User-Email`. JSON:API media type. HTTPS only. 5 req/s limit.
- You can address records by Strategic Sourcing `id` or by your own `external_id` (many operations have `...by External ID` variants) — use `external_id` to keep your system of record aligned.

## Steps
1. **Create the company** — `Create a Supplier Company` (POST `/supplier_companies`). Include name and any custom `fields` in `data.attributes`; capture the returned `id`.
2. **Verify** — `Get a Supplier Company` (or `Get a Supplier Company by External ID`).
3. **Add contacts** — `Create a Supplier Contact` for each buyer/seller contact, referencing the company.
4. **Classify** — `Create a Supplier Category`, `Create a Supplier Group`, and `Create a Supplier Company Segmentation` to bucket the supplier for reporting and sourcing.

## Errors
JSON:API `errors[]`. `400`/`422` = validation, `401` = auth, `404` = not found, `409` = duplicate/conflict. See `errors/scoutrfp-problem-types.yml`.
