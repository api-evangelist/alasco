# Alasco

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

Alasco is a Munich-based real-estate financial management platform for developers, asset managers, and construction teams, replacing spreadsheet-based cost control with integrated workflows across the development lifecycle. It spans three products - FinCon (financial controlling: projects, properties, contracts, invoices, change orders, cost elements, and financial reporting), CapEx (capital-expenditure planning and cost processing across assets and measures), and ESG (environmental data: buildings, utility meters, tenants, and consumption data). Alasco exposes a REST Public API that follows JSON:API principles, plus an official hosted MCP server for AI-agent integrations. It is ISO/IEC 27001 certified and serves institutional real-estate firms including Hines, JLL, and Ardian.

**Areas:** Company · Ai Enterprise Software · Real Estate · Construction · PropTech · Financial Management · Cost Management · Capital Expenditure · ESG · Sustainability

## Alasco on APIs.io

Everything profiled for Alasco is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/alasco/](https://apis.io/providers/alasco/)** — or go straight to one of the APIs or properties below.

### APIs (40)

- [Alasco Annual Consumption API](https://apis.io/apis/alasco/alasco-annual-consumption-api/) — **Annual Consumption** is the system-computed consumption per meter and calendar year, including emission factors and tenant allocations. The figures are…
- [Alasco Asset API](https://apis.io/apis/alasco/alasco-asset-api/) — An **Asset** is a property you manage capital expenditure for, mirrored from your Alasco asset register. Assets are read-only through this API: capital work…
- [Alasco Audit Log API](https://apis.io/apis/alasco/alasco-audit-log-api/) — The **Audit Log** is a read-only account-level trail of changes. A raw audit feed reports table-level inserts, updates and deletes, and a user audit feed…
- [Alasco Budget Shift API](https://apis.io/apis/alasco/alasco-budget-shift-api/) — A **Budget Shift** is a record of budget moved between **Contract Units** in a **Project** (or added from reserve), with a type, amount and reason. Budget…
- [Alasco Buildings API](https://apis.io/apis/alasco/alasco-buildings-api/) — A **Building** is a property in your Alasco asset register and the anchor for ESG data - its **Utility Meters**, **Tenants** and **Documents** all attach to…
- [Alasco Cash Outflow Cost Element View API](https://apis.io/apis/alasco/alasco-cash-outflow-cost-element-view-api/) — Read-only reporting view of actual cash outflows (paid invoices) allocated per **Cost Element**.
- [Alasco Change Order API](https://apis.io/apis/alasco/alasco-change-order-api/) — A **Change Order** is a formal amendment to a **Contract** - a cost or scope change - carrying claimed, audited and approved amounts and an approval state.…
- [Alasco Change Order Document API](https://apis.io/apis/alasco/alasco-change-order-document-api/) — A **Change Order Document** is a file attached to a **Change Order** (for example the amendment offer or supporting evidence). You can upload and download…
- [Alasco Consumption Intervals API](https://apis.io/apis/alasco/alasco-consumption-intervals-api/) — A **Consumption Interval** is a consumption total for a period (start to end date) for a meter. Intervals are created individually or in bulk -…
- [Alasco Contact API](https://apis.io/apis/alasco/alasco-contact-api/) — A **Contact** is a person or organisation used in invoicing and correspondence, with name, address and contact details. Contacts can be created and updated…
- [Alasco Contract API](https://apis.io/apis/alasco/alasco-contract-api/) — A **Contract** is an agreement with a **Contractor** to deliver work, tracking the committed amount and reserve. In CapEx a contract belongs to a…
- [Alasco Contract Document API](https://apis.io/apis/alasco/alasco-contract-document-api/) — A **Contract Document** is a file (such as the signed contract or its terms) attached to a **Contract**. You can upload and download them; a document left…
- [Alasco Contract Financials API](https://apis.io/apis/alasco/alasco-contract-financials-api/) — Read-only reporting view with one row per **Contract**, summarising its amount, invoiced, approved, paid and outstanding figures.
- [Alasco Contract Unit API](https://apis.io/apis/alasco/alasco-contract-unit-api/) — A **Contract Unit** is a budget package within a **Project** (the FinCon counterpart of a CapEx Measure), carrying an initial budget and a lifecycle…
- [Alasco Contract Unit Financials API](https://apis.io/apis/alasco/alasco-contract-unit-financials-api/) — Read-only reporting view with one row per **Contract Unit**, summarising its budget against the spend of the contracts assigned to it.
- [Alasco Contracting Entity API](https://apis.io/apis/alasco/alasco-contracting-entity-api/) — A **Contracting Entity** is the legal entity on your side that commissions contracts, holding company and commercial-register details. Names are unique per…
- [Alasco Contractor API](https://apis.io/apis/alasco/alasco-contractor-api/) — A **Contractor** is a supplier engaged to carry out contracted work, holding master data such as its identifier, VAT ID and bank details. A contractor can…
- [Alasco Cost Element API](https://apis.io/apis/alasco/alasco-cost-element-api/) — A **Cost Element** is a node in a hierarchical cost structure (a cost group) belonging to a **Cost Element Tree Template**. Cost elements classify a…
- [Alasco Cost Element Contract Financials API](https://apis.io/apis/alasco/alasco-cost-element-contract-financials-api/) — Read-only reporting view breaking down each **Contract**'s costs across the **Cost Elements** they are allocated to.
- [Alasco Cost Element Contract Unit Financials API](https://apis.io/apis/alasco/alasco-cost-element-contract-unit-financials-api/) — Read-only reporting view breaking down **Contract Unit** budget and spend across **Cost Elements**.
- [Alasco Cost Element Financials API](https://apis.io/apis/alasco/alasco-cost-element-financials-api/) — Read-only reporting view of budget and cost aggregated per **Cost Element** within a project.
- [Alasco Cost Element Tree Template API](https://apis.io/apis/alasco/alasco-cost-element-tree-template-api/) — A **Cost Element Tree Template** is a reusable hierarchy of **Cost Elements** that defines a project's cost structure. A template can back many…
- [Alasco Custom Field API](https://apis.io/apis/alasco/alasco-custom-field-api/) — A **Custom Field** holds your account's user-defined values on a **Contract** (the fields themselves are configured in Alasco). It is read-only here and…
- [Alasco Custom Field Definition API](https://apis.io/apis/alasco/alasco-custom-field-definition-api/) — A **Custom Field Definition** describes a custom field - its name, type and which object it applies to (contract or project). Definitions are configured in…
- [Alasco Documents API](https://apis.io/apis/alasco/alasco-documents-api/) — A **Document** is a file attached to one or more **Buildings** (certificates, leases and similar). Documents can be uploaded, downloaded, given an external…
- [Alasco Invoice API](https://apis.io/apis/alasco/alasco-invoice-api/) — An **Invoice** is a contractor's request for payment that moves through states from `NEW` to `PAID`. Submitting an invoice against an **Asset** creates it…
- [Alasco Invoice Document API](https://apis.io/apis/alasco/alasco-invoice-document-api/) — An **Invoice Document** is a file attached to an **Invoice**, such as the invoice PDF or supporting evidence. At least one document is required before an…
- [Alasco Invoice Tag API](https://apis.io/apis/alasco/alasco-invoice-tag-api/) — An **Invoice Tag** is a coloured label (with a name unique per account) you assign to **Invoices** for organisation and filtering. Tags can be created,…
- [Alasco Measure API](https://apis.io/apis/alasco/alasco-measure-api/) — A **Measure** is a planned package of capital work on an **Asset** (for example a renovation or a fit-out), carrying a status, category and priority.…
- [Alasco Outright Sale API](https://apis.io/apis/alasco/alasco-outright-sale-api/) — Read-only reporting view for outright (whole-asset) sales, showing total planned revenues against recorded payments.
- [Alasco Project API](https://apis.io/apis/alasco/alasco-project-api/) — A **Project** is the top-level container for a construction or development engagement. It optionally references a **Property** and a **Cost Element Tree…
- [Alasco Project Financials API](https://apis.io/apis/alasco/alasco-project-financials-api/) — Read-only reporting view with one row per **Project**, summarising budget against cost: current budget, contracted amount, change orders, approved and paid…
- [Alasco Property API](https://apis.io/apis/alasco/alasco-property-api/) — A **Property** is the real-estate asset a **Project** is carried out on, holding its address and location. A project references one property, and the same…
- [Alasco Rent Unit API](https://apis.io/apis/alasco/alasco-rent-unit-api/) — Read-only reporting view of rental units, showing each unit's rent status and projected totals.
- [Alasco Sales Unit API](https://apis.io/apis/alasco/alasco-sales-unit-api/) — Read-only reporting view of sales units, showing listed and sold prices.
- [Alasco Tenant Consumption Links API](https://apis.io/apis/alasco/alasco-tenant-consumption-links-api/) — A **Tenant Consumption Link** attributes a year's **Annual Consumption** to a **Tenant**. Links are created and deleted through the API by tenant external…
- [Alasco Tenants API](https://apis.io/apis/alasco/alasco-tenants-api/) — A **Tenant** is an occupant of a **Building**, identified by your `external_id` and linked to a building by `external_building_id`. Tenants are upserted…
- [Alasco Utility Data Batch Info API](https://apis.io/apis/alasco/alasco-utility-data-batch-info-api/) — **Utility Data Batch Info** records the source and label of a batch of imported utility data. Create one and reference it (via `batch_info_uuid`) when…
- [Alasco Utility Meter Readings API](https://apis.io/apis/alasco/alasco-utility-meter-readings-api/) — A **Utility Meter Reading** is a timestamped meter value. Readings are written individually or in bulk (upsert), keyed by the meter's external id, and feed…
- [Alasco Utility Meters API](https://apis.io/apis/alasco/alasco-utility-meters-api/) — A **Utility Meter** measures consumption (electricity, gas, water, heating or cooling) for a **Building**. Meters are created and updated through the API,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [alasco](https://apis.io/servers/alasco/alasco/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Alasco Agentic Access](https://apis.io/agentic-access/alasco/alasco-agentic-access/)

#### Collections (40)

Postman and Open Collection request collections.

- [CAPEX Annual Consumption API](https://apis.io/collections/alasco/open-alasco-annual-consumption-api/)
- [CAPEX Annual Consumption Asset API](https://apis.io/collections/alasco/open-alasco-asset-api/)
- [CAPEX Annual Consumption Audit Log API](https://apis.io/collections/alasco/open-alasco-audit-log-api/)
- [CAPEX Annual Consumption Budget Shift API](https://apis.io/collections/alasco/open-alasco-budget-shift-api/)
- [CAPEX Annual Consumption Buildings API](https://apis.io/collections/alasco/open-alasco-buildings-api/)
- [CAPEX Annual Consumption Cash Outflow Cost Element View API](https://apis.io/collections/alasco/open-alasco-cash-outflow-cost-element-view-api/)
- [CAPEX Annual Consumption Change Order API](https://apis.io/collections/alasco/open-alasco-change-order-api/)
- [CAPEX Annual Consumption Change Order Document API](https://apis.io/collections/alasco/open-alasco-change-order-document-api/)
- [CAPEX Annual Consumption Consumption Intervals API](https://apis.io/collections/alasco/open-alasco-consumption-intervals-api/)
- [CAPEX Annual Consumption Contact API](https://apis.io/collections/alasco/open-alasco-contact-api/)
- [CAPEX Annual Consumption Contract API](https://apis.io/collections/alasco/open-alasco-contract-api/)
- [CAPEX Annual Consumption Contract Document API](https://apis.io/collections/alasco/open-alasco-contract-document-api/)
- [CAPEX Annual Consumption Contract Financials API](https://apis.io/collections/alasco/open-alasco-contract-financials-api/)
- [CAPEX Annual Consumption Contract Unit API](https://apis.io/collections/alasco/open-alasco-contract-unit-api/)
- [CAPEX Annual Consumption Contract Unit Financials API](https://apis.io/collections/alasco/open-alasco-contract-unit-financials-api/)
- [CAPEX Annual Consumption Contracting Entity API](https://apis.io/collections/alasco/open-alasco-contracting-entity-api/)
- [CAPEX Annual Consumption Contractor API](https://apis.io/collections/alasco/open-alasco-contractor-api/)
- [CAPEX Annual Consumption Cost Element API](https://apis.io/collections/alasco/open-alasco-cost-element-api/)
- [CAPEX Annual Consumption Cost Element Contract Financials API](https://apis.io/collections/alasco/open-alasco-cost-element-contract-financials-api/)
- [CAPEX Annual Consumption Cost Element Contract Unit Financials API](https://apis.io/collections/alasco/open-alasco-cost-element-contract-unit-financials-api/)
- [CAPEX Annual Consumption Cost Element Financials API](https://apis.io/collections/alasco/open-alasco-cost-element-financials-api/)
- [CAPEX Annual Consumption Cost Element Tree Template API](https://apis.io/collections/alasco/open-alasco-cost-element-tree-template-api/)
- [CAPEX Annual Consumption Custom Field API](https://apis.io/collections/alasco/open-alasco-custom-field-api/)
- [CAPEX Annual Consumption Custom Field Definition API](https://apis.io/collections/alasco/open-alasco-custom-field-definition-api/)
- [CAPEX Annual Consumption Documents API](https://apis.io/collections/alasco/open-alasco-documents-api/)
- …and 15 more published on APIs.io

#### Overlays (3)

OpenAPI overlays, including conversational phrasing for each operation.

- [Alasco Capex Overlay](https://apis.io/overlays/alasco/alasco-capex-overlay/)
- [Alasco Esg Overlay](https://apis.io/overlays/alasco/alasco-esg-overlay/)
- [Alasco Fincon Overlay](https://apis.io/overlays/alasco/alasco-fincon-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Alasco Authentication](https://apis.io/security/alasco/alasco-authentication/)
- [Alasco Domain Security](https://apis.io/security/alasco/alasco-domain-security/)
- [Alasco Trust Center](https://apis.io/security/alasco/alasco-trust-center/)
- [Alasco Vulnerability Disclosure](https://apis.io/security/alasco/alasco-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.alasco.com/en/)
- [Documentation](https://developer.alasco.de/getstarted.html)
- [Getting started](https://developer.alasco.de/getstarted.html)
- [API reference](https://developer.alasco.de/)
- [Pricing](https://www.alasco.com/pricing/financial-management)
- [Sign up](https://www.alasco.com/book-a-demo)
- [Support](https://support.alasco.de/hc/de)
- [Changelog](https://developer.alasco.de/changelog.html)
- [Blog](https://www.alasco.com/blog)
- [Security](https://www.alasco.com/security-trust)
- [Compliance](https://www.alasco.com/security-trust)
- [Terms of service](https://www.alasco.com/legal/general-terms-and-conditions)
- [Privacy policy](https://www.alasco.com/privacy-policy)

## API Evangelist rating

**Kin Score 55.0** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 47.4 |
| Contract governance | 4.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 58.9 |
| Access clarity | 60.5 |

**Agent readiness 51.5** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/alasco/](https://apis.io/providers/alasco/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Alasco: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/alasco/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
