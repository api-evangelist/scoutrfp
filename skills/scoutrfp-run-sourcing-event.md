---
name: Run a sourcing event
description: Create a sourcing event in Workday Strategic Sourcing, add line items and invited suppliers, then read back the submitted bids.
api: openapi/scoutrfp-events-v1-openapi.json
operations:
  - Create an Event
  - Create a Line Item
  - Bulk Create Line Items
  - Add Suppliers
  - List Bids
  - Get a Bid
  - List Bid Line Items
---

# Run a sourcing event

Use the Workday Strategic Sourcing **Events API** (`https://api.us.workdayspend.com/services/events/v1`) to stand up an RFP/RFQ/auction, invite suppliers, and collect bids.

## Auth & conventions
- Send all three headers on every call: `X-Api-Key` (company API key), `X-User-Token` (personal user token), `X-User-Email`.
- `Content-Type: application/vnd.api+json` and `Accept: application/vnd.api+json` (JSON:API). HTTPS only.
- Rate limit is **5 requests/second** — on `429`, sleep ~1s and retry (see `conventions/scoutrfp-conventions.yml`).
- List endpoints are cursor paginated (`page[size]` up to 100, follow `next` links).

## Steps
1. **Create the event** — `Create an Event` (POST `/events`). Supply the event `type` (rfp/rfq/auction), title, and timeline in the JSON:API `data.attributes`. Capture the returned event `id`.
2. **Add line items** — `Create a Line Item` for a single item, or `Bulk Create Line Items` to load the worksheet in one call, referencing the event `id`.
3. **Invite suppliers** — `Add Suppliers` (or the `...using External IDs` / `...using Contacts` variants) to attach the supplier list to the event.
4. **Collect responses** — poll `List Bids` for the event, then `Get a Bid` and `List Bid Line Items` to read each supplier's submitted pricing.
5. **Award** downstream via the Awards API (`openapi/scoutrfp-awards-v1-openapi.json`, `List Awards`).

## Errors
JSON:API `errors[]` envelope. `401` = bad/missing auth headers, `404` = event/line-item not found, `409` = conflict, `422` = invalid attributes. See `errors/scoutrfp-problem-types.yml`.
