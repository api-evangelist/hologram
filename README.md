# Hologram (hologram)

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

Hologram is a global cellular IoT connectivity platform providing eUICC SIMs that roam across 550+ carrier networks in 200+ countries. The Hologram REST API lets developers activate and manage SIMs and devices, query data and SMS usage, send SMS and cloud messages to devices, manage plans and tags, and open secure Spacebridge tunnels.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hologram/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hologram/refs/heads/main/apis.yml)

## Tags

- IoT
- Cellular
- Connectivity
- SIM
- M2M

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Hologram Devices & SIMs API

List, retrieve, and update devices and their cellular links; activate (claim) single or bulk SIMs; pause/unpause data; change plans; and look up device names and locations.

- **Human URL:** [https://docs.hologram.io/guides/rest-api/beginners-guide-to-the-hologram-rest-api](https://docs.hologram.io/guides/rest-api/beginners-guide-to-the-hologram-rest-api)
- **Base URL:** `https://dashboard.hologram.io/api/1`

#### Tags

- Devices
- SIMs
- Cellular Links
- Activation

#### Properties

- [Documentation](https://docs.hologram.io/guides/rest-api/beginners-guide-to-the-hologram-rest-api)
- [API Reference](https://hologram.docs.apiary.io/)
- [OpenAPI](openapi/hologram-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hologram.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hologram.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hologram Data Usage API

Query cellular data usage as session records, daily, monthly, and billing-period summaries, plus SMS usage, scoped by organization, link, or tag.

- **Human URL:** [https://hologram.docs.apiary.io/](https://hologram.docs.apiary.io/)
- **Base URL:** `https://dashboard.hologram.io/api/1`

#### Tags

- Data Usage
- Sessions
- Billing

#### Properties

- [Documentation](https://docs.hologram.io/guides/rest-api/beginners-guide-to-the-hologram-rest-api)
- [API Reference](https://hologram.docs.apiary.io/)
- [OpenAPI](openapi/hologram-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hologram.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hologram.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hologram SMS & Messaging API

Send SMS to devices, deliver TCP/UDP cloud messages to devices, and push messages to the Hologram Data Engine via authenticated calls or per-device webhook GUIDs.

- **Human URL:** [https://hologram.docs.apiary.io/](https://hologram.docs.apiary.io/)
- **Base URL:** `https://dashboard.hologram.io/api/1`

#### Tags

- SMS
- Messaging
- Cloud Messages

#### Properties

- [Documentation](https://docs.hologram.io/guides/rest-api/beginners-guide-to-the-hologram-rest-api)
- [API Reference](https://hologram.docs.apiary.io/)
- [OpenAPI](openapi/hologram-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hologram.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hologram.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hologram Plans API

List available data plans, retrieve a single plan, and read plan pricing used when activating or changing the plan on a SIM.

- **Human URL:** [https://hologram.docs.apiary.io/](https://hologram.docs.apiary.io/)
- **Base URL:** `https://dashboard.hologram.io/api/1`

#### Tags

- Plans
- Pricing
- Data Plans

#### Properties

- [Documentation](https://docs.hologram.io/guides/rest-api/beginners-guide-to-the-hologram-rest-api)
- [API Reference](https://hologram.docs.apiary.io/)
- [OpenAPI](openapi/hologram-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hologram.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hologram.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hologram Tags API

Create, list, and delete device tags and link or unlink tags to one or many devices for fleet grouping and bulk operations.

- **Human URL:** [https://hologram.docs.apiary.io/](https://hologram.docs.apiary.io/)
- **Base URL:** `https://dashboard.hologram.io/api/1`

#### Tags

- Tags
- Organization
- Grouping

#### Properties

- [Documentation](https://docs.hologram.io/guides/rest-api/beginners-guide-to-the-hologram-rest-api)
- [API Reference](https://hologram.docs.apiary.io/)
- [OpenAPI](openapi/hologram-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hologram.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hologram.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hologram Webhooks API

Pre-authenticated per-device webhook endpoints that accept inbound messages addressed to a device by id and webhook GUID without an API key, for integrating external systems with the Hologram cloud.

- **Human URL:** [https://hologram.docs.apiary.io/](https://hologram.docs.apiary.io/)
- **Base URL:** `https://dashboard.hologram.io/api/1`

#### Tags

- Webhooks
- Inbound
- Device Messages

#### Properties

- [Documentation](https://docs.hologram.io/guides/rest-api/beginners-guide-to-the-hologram-rest-api)
- [API Reference](https://hologram.docs.apiary.io/)
- [OpenAPI](openapi/hologram-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hologram.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hologram.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/hologram-io)
- [LinkedIn](https://www.linkedin.com/company/hologramio)
- [Website](https://www.hologram.io/)
- [Documentation](https://docs.hologram.io/)
- [Plans](plans/hologram-plans-pricing.yml)
- [Rate Limits](rate-limits/hologram-rate-limits.yml)
- [Fin Ops](finops/hologram-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
