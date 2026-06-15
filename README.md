# Schoology (schoology)

Schoology (a PowerSchool company) is a K-12 LMS. The Schoology REST API exposes districts, schools, buildings, users, groups, courses, sections, enrollments, events, blog posts, discussions, updates, media albums, documents, assignments, grades, grading scales, rubrics, attendance, submissions, pages, SCORM packages, friend requests, invites, networks, grading periods, roles, private messaging, search, and resource collections.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/schoology/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/schoology/refs/heads/main/apis.yml)

## Tags

- EdTech
- LMS
- K-12

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Schoology REST API v1

REST API for the Schoology K-12 LMS. Authenticated via OAuth. Supports realm resources (districts, schools, buildings, users, groups, courses, sections), realm objects (enrollments, events, blog posts, discussions, updates, media albums, documents), course-specific objects (assignments, grades, grading scales, rubrics, categories, attendance, submissions, pages, SCORM), user objects (friend requests, invites, networks, user grades), and other objects (grading periods, roles, private messaging, search, resource collections). Multi-call POST and OPTIONS metadata calls supported. Bulk CSV export available for admins.

- **Human URL:** [https://developers.schoology.com/api-documentation/rest-api-v1](https://developers.schoology.com/api-documentation/rest-api-v1)
- **Base URL:** `https://api.schoology.com/v1/`

#### Tags

- REST
- OAuth
- LMS
- K-12

#### Properties

- [Documentation](https://developers.schoology.com/api-documentation/rest-api-v1)
- [Authentication](https://developers.schoology.com/api-documentation/authentication)
- [Postman Collection](collections/schoology-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schoology-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/schoology.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schoology.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Schoology Event Triggers (Webhooks) API

Documented webhook surface for the Schoology LMS. Schoology-defined "triggers" fire HTTP POST event objects to user-registered "targets", linked via "subscriptions". Manage targets via /v1/triggers/targets (GET, POST, PUT, DELETE) and subscriptions via /v1/triggers/subscriptions (GET, PUT). Schoology expects HTTP 200 from the target; non-200 responses are requeued and retried up to 5 times at 10 minute intervals. Supported trigger families include grade_item, attendance, grades, section_completion, and dropbox_submission.

- **Human URL:** [https://developers.schoology.com/api-documentation/rest-api-triggers-v1/](https://developers.schoology.com/api-documentation/rest-api-triggers-v1/)
- **Base URL:** `https://api.schoology.com/v1/`

#### Tags

- Webhooks
- Event Triggers
- REST
- OAuth
- LMS
- K-12

#### Properties

- [Documentation](https://developers.schoology.com/api-documentation/rest-api-triggers-v1/)
- [Documentation](https://developers.schoology.com/api-documentation/rest-api-triggers-v1/event_objects/)
- [OpenAPI](openapi/schoology-webhooks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/schoology-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schoology-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/schoology)
- [LinkedIn](https://www.linkedin.com/company/schoology)
- [Website](https://www.schoology.com/)
- [Developer](https://developers.schoology.com/)
- [Plans](plans/schoology-plans-pricing.yml)
- [Rate Limits](rate-limits/schoology-rate-limits.yml)
- [Fin Ops](finops/schoology-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
