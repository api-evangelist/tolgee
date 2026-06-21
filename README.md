# Tolgee (tolgee)

Tolgee is an open-source localization platform for translating web and mobile applications. It provides in-context translation, AI-assisted machine translation, framework SDKs, a CLI, and a REST API. Teams can self-host the open-source platform for free via Docker or use Tolgee Cloud (app.tolgee.io). The REST API exposes projects, localization keys, translations, languages, import/export, and screenshots, authenticated with a project API key sent in the X-API-Key header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tolgee/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tolgee/refs/heads/main/apis.yml)

## Tags

- Localization
- i18n
- Translation
- Open Source
- Developer Tools

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Tolgee Projects API

Create, list, retrieve, update, and delete localization projects, and inspect the current API key's project context, on Tolgee Cloud or a self-hosted instance.

- **Human URL:** [https://docs.tolgee.io/api](https://docs.tolgee.io/api)
- **Base URL:** `https://app.tolgee.io`

#### Tags

- Projects
- Organizations

#### Properties

- [Documentation](https://docs.tolgee.io/api)
- [API Reference](https://docs.tolgee.io/api)
- [OpenAPI](openapi/tolgee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tolgee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tolgee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tolgee Keys API

CRUD and bulk operations for translation keys within a project, including creating a key with translations, searching keys, and complex key editing.

- **Human URL:** [https://docs.tolgee.io/api](https://docs.tolgee.io/api)
- **Base URL:** `https://app.tolgee.io`

#### Tags

- Keys
- Localization

#### Properties

- [Documentation](https://docs.tolgee.io/api)
- [API Reference](https://docs.tolgee.io/api)
- [OpenAPI](openapi/tolgee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tolgee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tolgee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tolgee Translations API

Retrieve, create, and update translations for keys, set translation state, mark values outdated, and read translation history within a project.

- **Human URL:** [https://docs.tolgee.io/api/get-translations](https://docs.tolgee.io/api/get-translations)
- **Base URL:** `https://app.tolgee.io`

#### Tags

- Translations
- i18n

#### Properties

- [Documentation](https://docs.tolgee.io/api/get-translations)
- [API Reference](https://docs.tolgee.io/api)
- [OpenAPI](openapi/tolgee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tolgee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tolgee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tolgee Languages API

Create, list, update, and delete the languages (locales) configured for a project.

- **Human URL:** [https://docs.tolgee.io/api](https://docs.tolgee.io/api)
- **Base URL:** `https://app.tolgee.io`

#### Tags

- Languages
- Locales

#### Properties

- [Documentation](https://docs.tolgee.io/api)
- [API Reference](https://docs.tolgee.io/api)
- [OpenAPI](openapi/tolgee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tolgee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tolgee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tolgee Import/Export API

Export project translations as a ZIP of localization files (JSON, PO, XLIFF, Apple strings, Android XML, and more) and import translation files with a multi-step conflict-resolution workflow.

- **Human URL:** [https://docs.tolgee.io/platform/projects_and_organizations/export](https://docs.tolgee.io/platform/projects_and_organizations/export)
- **Base URL:** `https://app.tolgee.io`

#### Tags

- Import
- Export

#### Properties

- [Documentation](https://docs.tolgee.io/platform/projects_and_organizations/export)
- [API Reference](https://docs.tolgee.io/api)
- [OpenAPI](openapi/tolgee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tolgee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tolgee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tolgee Screenshots API

Upload, list, and delete screenshots attached to localization keys to give translators visual in-context reference.

- **Human URL:** [https://docs.tolgee.io/api](https://docs.tolgee.io/api)
- **Base URL:** `https://app.tolgee.io`

#### Tags

- Screenshots
- Context

#### Properties

- [Documentation](https://docs.tolgee.io/api)
- [API Reference](https://docs.tolgee.io/api)
- [OpenAPI](openapi/tolgee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tolgee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tolgee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/tolgee)
- [LinkedIn](https://www.linkedin.com/company/tolgee)
- [Website](https://tolgee.io)
- [Documentation](https://docs.tolgee.io)
- [Plans](plans/tolgee-plans-pricing.yml)
- [Rate Limits](rate-limits/tolgee-rate-limits.yml)
- [Fin Ops](finops/tolgee-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
