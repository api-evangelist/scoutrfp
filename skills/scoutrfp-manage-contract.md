---
name: Manage a contract
description: Create and maintain contracts and contract types in Workday Strategic Sourcing, addressable by id or external id.
api: openapi/scoutrfp-contracts-v1-openapi.json
operations:
  - List Contract Types
  - Create a Contract
  - Get a Contract
  - Update a Contract
  - Update a Contract by External ID
---

# Manage a contract

Use the Workday Strategic Sourcing **Contracts API** (`https://api.us.workdayspend.com/services/contracts/v1`) to record and maintain contracts.

## Auth & conventions
- Headers: `X-Api-Key`, `X-User-Token`, `X-User-Email`. JSON:API media type. HTTPS only. 5 req/s limit.
- Cursor pagination on list endpoints (`page[size]`).

## Steps
1. **Pick a type** — `List Contract Types` (create one with `Create a Contract Type` if needed) and note the type `id`.
2. **Create** — `Create a Contract` (POST `/contracts`) with the contract `fields`, supplier reference, and type in `data.attributes`. Capture the `id`.
3. **Read** — `Get a Contract` (or `Get a Contract by External ID`) and `Describe Contract object` for the field schema.
4. **Maintain** — `Update a Contract` / `Update a Contract by External ID` (PATCH) for renewals, milestones, and status changes.

## Errors
JSON:API `errors[]`. `401` = auth, `404` = not found, `409` = conflict. See `errors/scoutrfp-problem-types.yml`.
