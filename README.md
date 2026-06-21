# Hologram (hologram)

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
