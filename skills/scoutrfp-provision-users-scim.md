---
name: Provision users with SCIM
description: Create, read, update, and deactivate Workday Strategic Sourcing users through the SCIM 2.0 provisioning API.
api: openapi/scoutrfp-scim-v2-openapi.json
operations:
  - List Users
  - Create a User
  - Get a user
  - Patch a User
  - Replace a User
  - Deactivate a user
---

# Provision users with SCIM

Use the Workday Strategic Sourcing **SCIM 2.0 API** (`https://api.us.workdayspend.com/scim/v2`) for identity lifecycle management from your IdP.

## Auth & conventions
- Authenticate with the company `X-Api-Key` header or HTTP Basic (`basic_authentication`).
- Media type is `application/scim+json` (NOT JSON:API). HTTPS only. 5 req/s limit.
- Errors use the SCIM `urn:ietf:params:scim:api:messages:2.0:Error` schema, not JSON:API.

## Steps
1. **Discover** — `List Schemas`, `List Resource Types`, `List Service Provider Configs` to learn supported attributes.
2. **Reconcile** — `List Users` (SCIM filter) to find existing accounts before creating.
3. **Provision** — `Create a User` (POST `/Users`) with the SCIM `userName`, `name`, `emails`, `active`.
4. **Update** — `Patch a User` for incremental changes or `Replace a User` (PUT) for full replacement.
5. **Deprovision** — `Deactivate a user` (DELETE) when the employee leaves.

## Errors
SCIM error envelope. `400` = bad request, `403` = forbidden, `404` = not found, `409` = uniqueness conflict. See `errors/scoutrfp-problem-types.yml`.
