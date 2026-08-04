# Schoology (schoology)

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
