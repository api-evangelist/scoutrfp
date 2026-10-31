# Scout RFP (Workday Strategic Sourcing)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Scout RFP is a strategic sourcing and supplier engagement platform founded in 2014 and acquired by Workday in 2019, where it now ships as Workday Strategic Sourcing. The product covers sourcing events (RFPs/RFIs/RFQs and auctions), supplier management, contracts, projects, spend categories, awards, and supplier payments. Its public developer platform exposes a JSON:API-conformant REST API across eleven versioned services — Suppliers, Events, Reports, Contracts, Projects, Payments, Fields, Awards, Attachments, and Spend Categories — plus a SCIM 2.0 user-provisioning API. Authentication is by company API key plus a per-user personal token, all calls are HTTPS/JSON:API, cursor paginated, and rate limited to five requests per second. The legacy v3 API on api.scoutrfp.com was sunset April 18, 2025 in favor of the versioned services on api.us.workdayspend.com (with EU and CA regional hosts).

**Areas:** Company · Enterprise · Procurement · Strategic Sourcing · Supplier Management · Spend Management · RFP · Contracts · SCIM · JSON:API

## Scout RFP (Workday Strategic Sourcing) on APIs.io

Everything profiled for Scout RFP (Workday Strategic Sourcing) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/scoutrfp/](https://apis.io/providers/scoutrfp/)** — or go straight to one of the APIs or properties below.

### APIs (55)

- [Scout RFP (Workday Strategic Sourcing) attachments API](https://apis.io/apis/scoutrfp/scoutrfp-attachments-api/) — Use the attachments API to create, update, and delete the attachments in Workday Strategic Sourcing. ## Working with Attachments Creating attachments for…
- [Scout RFP (Workday Strategic Sourcing) award_line_items API](https://apis.io/apis/scoutrfp/scoutrfp-award-line-items-api/) — Use the Award Line Items API to query the Award Line Items in Workday Strategic Sourcing. Award Line Items are used for procurement. ## Award Line Item…
- [Scout RFP (Workday Strategic Sourcing) Awards API](https://apis.io/apis/scoutrfp/scoutrfp-awards-api/) — Use the Awards API to query the Awards in Workday Strategic Sourcing. Awards are used for procurement. ## Award Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Bid Line Items API](https://apis.io/apis/scoutrfp/scoutrfp-bid-line-items-api/) — Use the bid line items API to query the bid line items in Workday Strategic Sourcing. ## Bid Line Item Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Bids API](https://apis.io/apis/scoutrfp/scoutrfp-bids-api/) — Use the bids API to query the bids in Workday Strategic Sourcing. Only bids for events of type `RFP` are supported. ## Bid Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Contact Types API](https://apis.io/apis/scoutrfp/scoutrfp-contact-types-api/) — Use the contact types API to create, update, and query the contact types in Workday Strategic Sourcing. ## ContactType Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Contract Milestone Reports API](https://apis.io/apis/scoutrfp/scoutrfp-contract-milestone-reports-api/) — This report returns a list of contract milestone report entries.
- [Scout RFP (Workday Strategic Sourcing) Contract Reports API](https://apis.io/apis/scoutrfp/scoutrfp-contract-reports-api/) — This report returns a list of contract report entries.
- [Scout RFP (Workday Strategic Sourcing) Contract Types API](https://apis.io/apis/scoutrfp/scoutrfp-contract-types-api/) — Use the contract types API to query the contract types in Workday Strategic Sourcing. Contract Types are used in the contract resource. On POST and PATCH…
- [Scout RFP (Workday Strategic Sourcing) Contracts API](https://apis.io/apis/scoutrfp/scoutrfp-contracts-api/) — Use the contracts API to create, update, and query the contracts in Workday Strategic Sourcing. ## Contract Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Discovery API](https://apis.io/apis/scoutrfp/scoutrfp-discovery-api/) — Endpoints to facilitate discovery of SCIM service provider features
- [Scout RFP (Workday Strategic Sourcing) Event Reports API](https://apis.io/apis/scoutrfp/scoutrfp-event-reports-api/) — This report returns a list of event report entries.
- [Scout RFP (Workday Strategic Sourcing) Event Supplier Companies API](https://apis.io/apis/scoutrfp/scoutrfp-event-supplier-companies-api/) — Use the event supplier companies API to manage event suppliers.
- [Scout RFP (Workday Strategic Sourcing) Event Supplier Contacts API](https://apis.io/apis/scoutrfp/scoutrfp-event-supplier-contacts-api/) — Use the event supplier contacts API to manage event suppliers. This API provides 2 advantages over the event supplier companies APIs: - It allows specifying…
- [Scout RFP (Workday Strategic Sourcing) Event Templates API](https://apis.io/apis/scoutrfp/scoutrfp-event-templates-api/) — Use the contract types API to query the event templates in Workday Strategic Sourcing. Event Templates are used as a blueprint for newly created events. ##…
- [Scout RFP (Workday Strategic Sourcing) Events API](https://apis.io/apis/scoutrfp/scoutrfp-events-api/) — Use the events API to create, update, and query the events in Workday Strategic Sourcing. ## Event Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Field Groups API](https://apis.io/apis/scoutrfp/scoutrfp-field-groups-api/) — Use the fields API to create, update, and query the custom fields groups in Workday Strategic Sourcing. Custom field groups act as a collection of custom…
- [Scout RFP (Workday Strategic Sourcing) Field Options API](https://apis.io/apis/scoutrfp/scoutrfp-field-options-api/) — Use the fields API to create, update, and query the custom fields options in Workday Strategic Sourcing. Custom field options exist for single select and…
- [Scout RFP (Workday Strategic Sourcing) Fields API](https://apis.io/apis/scoutrfp/scoutrfp-fields-api/) — Use the fields API to create, update, and query the custom fields in Workday Strategic Sourcing. ## Field Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Line Items API](https://apis.io/apis/scoutrfp/scoutrfp-line-items-api/) — Use the line items API to create, update, and query the worksheet line items in Workday Strategic Sourcing. ## Line Item Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Payment Currencies API](https://apis.io/apis/scoutrfp/scoutrfp-payment-currencies-api/) — Use the payment currencies API to create, update, and query the payment currencies in Workday Strategic Sourcing. ## Payment Currency Object…
- [Scout RFP (Workday Strategic Sourcing) Payment Terms API](https://apis.io/apis/scoutrfp/scoutrfp-payment-terms-api/) — Use the payment terms API to create, update, and query the payment terms in Workday Strategic Sourcing. ## Payment Term Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Payment Types API](https://apis.io/apis/scoutrfp/scoutrfp-payment-types-api/) — Use the payment types API to create, update, and query the payment types in Workday Strategic Sourcing. ## Payment Type Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Performance Review Answer Reports API](https://apis.io/apis/scoutrfp/scoutrfp-performance-review-answer-reports-api/) — This report returns a list of Performance Review Answer report entries.
- [Scout RFP (Workday Strategic Sourcing) Performance Review Reports API](https://apis.io/apis/scoutrfp/scoutrfp-performance-review-reports-api/) — This report returns a list of Performance Review report entries.
- [Scout RFP (Workday Strategic Sourcing) Project Milestone Reports API](https://apis.io/apis/scoutrfp/scoutrfp-project-milestone-reports-api/) — This report returns a list of Project Milestone report entries.
- [Scout RFP (Workday Strategic Sourcing) Project Reports API](https://apis.io/apis/scoutrfp/scoutrfp-project-reports-api/) — This report returns a list of Project report entries.
- [Scout RFP (Workday Strategic Sourcing) Project Supplier Companies API](https://apis.io/apis/scoutrfp/scoutrfp-project-supplier-companies-api/) — Use the project supplier companies API to manage project suppliers.
- [Scout RFP (Workday Strategic Sourcing) Project Supplier Contacts API](https://apis.io/apis/scoutrfp/scoutrfp-project-supplier-contacts-api/) — Use the project supplier contacts API to manage project suppliers. This API provides 2 advantages over the project supplier companies APIs: - It allows…
- [Scout RFP (Workday Strategic Sourcing) Project Types API](https://apis.io/apis/scoutrfp/scoutrfp-project-types-api/) — Use the project types API to query the project types in Workday Strategic Sourcing. Project Types are used in the project resource. On POST and PATCH…
- [Scout RFP (Workday Strategic Sourcing) Projects API](https://apis.io/apis/scoutrfp/scoutrfp-projects-api/) — Use the projects API to create, update, and query the projects in Workday Strategic Sourcing. ## Project Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Savings Reports API](https://apis.io/apis/scoutrfp/scoutrfp-savings-reports-api/) — This report returns a list of Savings report entries.
- [Scout RFP (Workday Strategic Sourcing) Spend Categories API](https://apis.io/apis/scoutrfp/scoutrfp-spend-categories-api/) — Use the Spend Categories API to create, update, and query the Spend Categories in Workday Strategic Sourcing. Spend Categories are used in both the project…
- [Scout RFP (Workday Strategic Sourcing) Supplier Categories API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-categories-api/) — Use the supplier categories API to create, update, and query the supplier categories in Workday Strategic Sourcing. ## Supplier Category Object…
- [Scout RFP (Workday Strategic Sourcing) Supplier Classifications API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-classifications-api/) — ## Supplier Classification Object <SchemaDefinition schemaRef="#/components/schemas/SupplierClassification"…
- [Scout RFP (Workday Strategic Sourcing) Supplier Companies API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-companies-api/) — Use the supplier companies API to create, update, and query the suppliers in Workday Strategic Sourcing. ## Supplier Company Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Supplier Company Risks API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-company-risks-api/) — Use the supplier company risks API to create, update, and query the supplier company risks in Workday Strategic Sourcing. ## Supplier Company Risk Object…
- [Scout RFP (Workday Strategic Sourcing) Supplier Company Segmentation Statuses API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-company-segmentation-statuses-api/) — Use the supplier company segmentation statuses API to create, update, and query the supplier company segmentation statuses in Workday Strategic Sourcing. ##…
- [Scout RFP (Workday Strategic Sourcing) Supplier Company Segmentations API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-company-segmentations-api/) — Use the supplier company segmentations API to create, update, and query the supplier company segmentations in Workday Strategic Sourcing. ## Supplier…
- [Scout RFP (Workday Strategic Sourcing) Supplier Contacts API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-contacts-api/) — ## Supplier Contact Object <SchemaDefinition schemaRef="#/components/schemas/SupplierContact" exampleRef="#/components/examples/SupplierContact"…
- [Scout RFP (Workday Strategic Sourcing) Supplier Groups API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-groups-api/) — Use the supplier groups API to create, update, and query the supplier groups in Workday Strategic Sourcing. ## Supplier Group Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Supplier Reports API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-reports-api/) — This report returns a list of Supplier report entries.
- [Scout RFP (Workday Strategic Sourcing) Supplier Review Reports API](https://apis.io/apis/scoutrfp/scoutrfp-supplier-review-reports-api/) — This report returns a list of Supplier Review report entries.
- [Scout RFP (Workday Strategic Sourcing) Suppliers API](https://apis.io/apis/scoutrfp/scoutrfp-suppliers-api/) — This report returns a list of Suppliers.
- [Scout RFP (Workday Strategic Sourcing) User API](https://apis.io/apis/scoutrfp/scoutrfp-user-api/) — Use the users API to create, update, and query the users in Workday Strategic Sourcing. ## User Object <SchemaDefinition…
- [Scout RFP (Workday Strategic Sourcing) Worksheets API](https://apis.io/apis/scoutrfp/scoutrfp-worksheets-api/) — Use the worksheets API to create, update, and query the worksheets in Workday Strategic Sourcing. ## Worksheet Object <SchemaDefinition…
- [Events API](https://apis.io/apis/scoutrfp/events-api/) — Manage sourcing events including RFPs, RFIs, and reverse auctions. Supports creating events from templates, updating event details, managing supplier…
- [Contracts API](https://apis.io/apis/scoutrfp/contracts-api/) — Manage contracts within the strategic sourcing platform, including creation, retrieval, and updates. Version 1.1 of the API.
- [Awards API](https://apis.io/apis/scoutrfp/awards-api/) — Manage sourcing award decisions for completed events, tracking supplier selection outcomes and award values. Version 1.1.
- [Attachments API](https://apis.io/apis/scoutrfp/attachments-api/) — Upload and manage file attachments associated with sourcing events, contracts, and other procurement objects. Version 1.0.
- [Payments API](https://apis.io/apis/scoutrfp/payments-api/) — Manage payment records associated with procurement transactions and contract fulfillment. Version 1.0.
- [Projects API](https://apis.io/apis/scoutrfp/projects-api/) — Manage procurement projects that organize and group related sourcing events and activities. Version 1.0.
- [Reports API](https://apis.io/apis/scoutrfp/reports-api/) — Access procurement analytics and reporting data from the Workday Strategic Sourcing platform. Version 1.0.
- [SCIM Users API](https://apis.io/apis/scoutrfp/scim-api/) — Manage users in the Workday Strategic Sourcing platform using the SCIM 2.0 standard, enabling integration with identity providers for automated user…
- [Spend Categories API](https://apis.io/apis/scoutrfp/spend-categories-api/) — Manage spend category taxonomies used to classify procurement spending within the Workday Strategic Sourcing platform. Version 1.0.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [scoutrfp](https://apis.io/servers/scoutrfp/scoutrfp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Scoutrfp Agentic Access](https://apis.io/agentic-access/scoutrfp/scoutrfp-agentic-access/)

#### Collections (43)

Postman and Open Collection request collections.

- [Workday Strategic Sourcing attachments API](https://apis.io/collections/scoutrfp/open-scoutrfp-attachments-api/)
- [Workday Strategic Sourcing attachments award_line_items API](https://apis.io/collections/scoutrfp/open-scoutrfp-award-line-items-api/)
- [Workday Strategic Sourcing attachments awards API](https://apis.io/collections/scoutrfp/open-scoutrfp-awards-api/)
- [Workday Strategic Sourcing attachments bid_line_items API](https://apis.io/collections/scoutrfp/open-scoutrfp-bid-line-items-api/)
- [Workday Strategic Sourcing attachments bids API](https://apis.io/collections/scoutrfp/open-scoutrfp-bids-api/)
- [Workday Strategic Sourcing attachments contact_types API](https://apis.io/collections/scoutrfp/open-scoutrfp-contact-types-api/)
- [Workday Strategic Sourcing attachments contract_milestone_reports API](https://apis.io/collections/scoutrfp/open-scoutrfp-contract-milestone-reports-api/)
- [Workday Strategic Sourcing attachments contract_reports API](https://apis.io/collections/scoutrfp/open-scoutrfp-contract-reports-api/)
- [Workday Strategic Sourcing attachments contract_types API](https://apis.io/collections/scoutrfp/open-scoutrfp-contract-types-api/)
- [Workday Strategic Sourcing attachments contracts API](https://apis.io/collections/scoutrfp/open-scoutrfp-contracts-api/)
- [Workday Strategic Sourcing attachments discovery API](https://apis.io/collections/scoutrfp/open-scoutrfp-discovery-api/)
- [Workday Strategic Sourcing attachments event_reports API](https://apis.io/collections/scoutrfp/open-scoutrfp-event-reports-api/)
- [Workday Strategic Sourcing attachments event_supplier_companies API](https://apis.io/collections/scoutrfp/open-scoutrfp-event-supplier-companies-api/)
- [Workday Strategic Sourcing attachments event_supplier_contacts API](https://apis.io/collections/scoutrfp/open-scoutrfp-event-supplier-contacts-api/)
- [Workday Strategic Sourcing attachments event_templates API](https://apis.io/collections/scoutrfp/open-scoutrfp-event-templates-api/)
- [Workday Strategic Sourcing attachments events API](https://apis.io/collections/scoutrfp/open-scoutrfp-events-api/)
- [Workday Strategic Sourcing attachments field_groups API](https://apis.io/collections/scoutrfp/open-scoutrfp-field-groups-api/)
- [Workday Strategic Sourcing attachments field_options API](https://apis.io/collections/scoutrfp/open-scoutrfp-field-options-api/)
- [Workday Strategic Sourcing attachments fields API](https://apis.io/collections/scoutrfp/open-scoutrfp-fields-api/)
- [Workday Strategic Sourcing attachments line_items API](https://apis.io/collections/scoutrfp/open-scoutrfp-line-items-api/)
- [Workday Strategic Sourcing attachments payment_currencies API](https://apis.io/collections/scoutrfp/open-scoutrfp-payment-currencies-api/)
- [Workday Strategic Sourcing attachments payment_terms API](https://apis.io/collections/scoutrfp/open-scoutrfp-payment-terms-api/)
- [Workday Strategic Sourcing attachments payment_types API](https://apis.io/collections/scoutrfp/open-scoutrfp-payment-types-api/)
- [Workday Strategic Sourcing attachments project_milestone_reports API](https://apis.io/collections/scoutrfp/open-scoutrfp-project-milestone-reports-api/)
- [Workday Strategic Sourcing attachments project_reports API](https://apis.io/collections/scoutrfp/open-scoutrfp-project-reports-api/)
- …and 18 more published on APIs.io

#### Overlays (11)

OpenAPI overlays, including conversational phrasing for each operation.

- [Scoutrfp Attachments V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-attachments-v1-overlay/)
- [Scoutrfp Awards V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-awards-v1-overlay/)
- [Scoutrfp Contracts V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-contracts-v1-overlay/)
- [Scoutrfp Events V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-events-v1-overlay/)
- [Scoutrfp Fields V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-fields-v1-overlay/)
- [Scoutrfp Payments V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-payments-v1-overlay/)
- [Scoutrfp Projects V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-projects-v1-overlay/)
- [Scoutrfp Reports V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-reports-v1-overlay/)
- [Scoutrfp Scim V2 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-scim-v2-overlay/)
- [Scoutrfp Spend_Categories V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-spend_categories-v1-overlay/)
- [Scoutrfp Suppliers V1 Overlay](https://apis.io/overlays/scoutrfp/scoutrfp-suppliers-v1-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Scoutrfp Authentication](https://apis.io/security/scoutrfp/scoutrfp-authentication/)
- [Scoutrfp Domain Security](https://apis.io/security/scoutrfp/scoutrfp-domain-security/)
- [Scoutrfp Trust Center](https://apis.io/security/scoutrfp/scoutrfp-trust-center/)

#### Rate limits (1)

Published request limits.

- [Scoutrfp Rate Limits](https://apis.io/rate-limits/scoutrfp/scoutrfp-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.workday.com/en-us/products/spend-management/strategic-sourcing.html)
- [Documentation](https://apidocs.workdayspend.com/)
- [Getting started](https://apidocs.workdayspend.com/)
- [API reference](https://apidocs.workdayspend.com/services/suppliers/v1.html)
- [Changelog](https://apidocs.workdayspend.com/services/suppliers/v1.html)
- [Compliance](https://security.workday.com/)
- [GitHub](https://github.com/ScoutRFP)

## API Evangelist rating

**Kin Score 43.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 58.1 |
| Contract governance | 4.5 |
| Operational transparency | 47.4 |
| Developer ergonomics | 51.8 |
| Access clarity | 7.9 |

**Agent readiness 31.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/scoutrfp/](https://apis.io/providers/scoutrfp/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Scout RFP (Workday Strategic Sourcing): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/scoutrfp/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
