# Teable (teable)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Teable is an open-source, no-code database platform built on PostgreSQL and positioned as an Airtable alternative. It pairs a spreadsheet-style UI with a documented REST API for managing spaces, bases, tables, fields, records, views, and attachments, scaling to millions of rows while keeping data in a real Postgres database.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/teable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/teable/refs/heads/main/apis.yml)

## Tags

- No-Code
- Database
- Airtable Alternative
- Postgres
- Open Source

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Teable Spaces API

Create, list, update, and delete spaces (top-level workspaces) and manage space-level collaborators and their roles.

- **Human URL:** [https://help.teable.ai/en/api-doc/overview](https://help.teable.ai/en/api-doc/overview)
- **Base URL:** `https://app.teable.io/api`

#### Tags

- Spaces
- Workspaces
- Collaborators

#### Properties

- [Documentation](https://help.teable.ai/en/api-doc/overview)
- [API Reference](https://help.teable.ai/en/api-doc/space-list)
- [OpenAPI](openapi/teable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teable Bases API

Manage bases (the Postgres-backed databases inside a space), including create, duplicate, delete, base collaborators, and shareable links.

- **Human URL:** [https://help.teable.ai/en/api-doc/overview](https://help.teable.ai/en/api-doc/overview)
- **Base URL:** `https://app.teable.io/api`

#### Tags

- Bases
- Databases
- Sharing

#### Properties

- [Documentation](https://help.teable.ai/en/api-doc/base-get-all)
- [API Reference](https://help.teable.ai/en/api-doc/base-get-all)
- [OpenAPI](openapi/teable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teable Tables API

Create, list, get, update, duplicate, and delete tables within a base, the spreadsheet-like containers that hold fields and records.

- **Human URL:** [https://help.teable.ai/en/api-doc/overview](https://help.teable.ai/en/api-doc/overview)
- **Base URL:** `https://app.teable.io/api`

#### Tags

- Tables
- Schema

#### Properties

- [Documentation](https://help.teable.ai/en/api-doc/table-list)
- [API Reference](https://help.teable.ai/en/api-doc/table-list)
- [OpenAPI](openapi/teable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teable Fields API

Define and manage table fields (columns) across Teable's rich field types, including create, update, convert field type, duplicate, and delete.

- **Human URL:** [https://help.teable.ai/en/api-doc/overview](https://help.teable.ai/en/api-doc/overview)
- **Base URL:** `https://app.teable.io/api`

#### Tags

- Fields
- Columns
- Schema

#### Properties

- [Documentation](https://help.teable.ai/en/api-doc/field-list)
- [API Reference](https://help.teable.ai/en/api-doc/field-list)
- [OpenAPI](openapi/teable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teable Records API

Full CRUD over records (rows) with rich querying - filter, orderBy, search, projection, pagination, fieldKeyType and cellFormat controls - plus batch create/update/delete, duplicate, and record history.

- **Human URL:** [https://help.teable.ai/en/api-doc/overview](https://help.teable.ai/en/api-doc/overview)
- **Base URL:** `https://app.teable.io/api`

#### Tags

- Records
- Rows
- CRUD

#### Properties

- [Documentation](https://help.teable.ai/en/api-doc/record-get-list)
- [API Reference](https://help.teable.ai/en/api-doc/record-get-list)
- [OpenAPI](openapi/teable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teable Views API

Create and manage views (grid, form, Kanban, gallery, calendar) over a table, including filter, sort, group configuration and shareable view links.

- **Human URL:** [https://help.teable.ai/en/api-doc/overview](https://help.teable.ai/en/api-doc/overview)
- **Base URL:** `https://app.teable.io/api`

#### Tags

- Views
- Grid
- Kanban

#### Properties

- [Documentation](https://help.teable.ai/en/api-doc/view-list)
- [API Reference](https://help.teable.ai/en/api-doc/view-list)
- [OpenAPI](openapi/teable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teable Attachments API

Upload and retrieve file attachments via signed upload flow, then reference them from attachment-type fields on records.

- **Human URL:** [https://help.teable.ai/en/api-doc/overview](https://help.teable.ai/en/api-doc/overview)
- **Base URL:** `https://app.teable.io/api`

#### Tags

- Attachments
- Files
- Uploads

#### Properties

- [Documentation](https://help.teable.ai/en/api-doc/attachment-upload)
- [API Reference](https://help.teable.ai/en/api-doc/attachment-upload)
- [OpenAPI](openapi/teable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/teableio)
- [LinkedIn](https://www.linkedin.com/company/teable)
- [Website](https://teable.io)
- [Documentation](https://help.teable.ai/en/api-doc/overview)
- [Plans](plans/teable-plans-pricing.yml)
- [Rate Limits](rate-limits/teable-rate-limits.yml)
- [Fin Ops](finops/teable-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
