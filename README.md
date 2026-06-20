# Teable (teable)

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
