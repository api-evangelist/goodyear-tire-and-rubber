# Goodyear Tire & Rubber (goodyear-tire-and-rubber)

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

The Goodyear Tire & Rubber Company is a global tire manufacturer that provides developer APIs for intelligent tire data, fleet management, and commercial truck tire services. Goodyear's SightLine technology and GaaS API platform enable programmatic access to tire telematics, catalogs, work orders, and service tickets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/goodyear-tire-and-rubber/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/goodyear-tire-and-rubber/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Connected Vehicles
- Fleet Management
- IoT
- Telematics
- Tires

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Goodyear SightLine API

Goodyear SightLine API provides developer-friendly access to intelligent tire data including tire type, tread depth, tire pressure, load, wear state, and temperature. The API uses REST architecture with robust security protocols for efficient and secure data sharing.

- **Human URL:** [https://developer.goodyearsightline.com/](https://developer.goodyearsightline.com/)
- **Base URL:** `https://developer.goodyearsightline.com`

#### Tags

- Connected Vehicles
- IoT
- Telematics
- Tire Data
- Tires

#### Properties

- [Portal](https://developer.goodyearsightline.com/)
- [OpenAPI](openapi/sightline-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sightline-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sightline-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Goodyear API Management Portal

The Goodyear API Management Portal (GaaS) provides access to Goodyear's suite of APIs for tire and fleet management services.

- **Human URL:** [https://gaas-portal.goodyear.com/](https://gaas-portal.goodyear.com/)
- **Base URL:** `https://gaas-portal.goodyear.com`

#### Tags

- API Management
- Fleet Management
- Tires

#### Properties

- [Portal](https://gaas-portal.goodyear.com/)
- [Sign Up](https://gaas-portal.goodyear.com/signup)
- [OpenAPI](openapi/gaas-portal.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gaas-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gaas-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Goodyear Truck Tire Catalog API

The Goodyear Truck Tire Catalog API provides access to Goodyear's commercial truck tire catalog data.

- **Human URL:** [https://api.catalog.goodyeartrucktires.com/](https://api.catalog.goodyeartrucktires.com/)
- **Base URL:** `https://api.catalog.goodyeartrucktires.com`

#### Tags

- Catalog
- Tires
- Truck Tires

#### Properties

- [Portal](https://api.catalog.goodyeartrucktires.com/)
- [Postman Collection](collections/gaas-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gaas-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sightline-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sightline-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Goodyear Work Order API

The Goodyear Work Order API enables management of service work orders for commercial truck tire services.

- **Human URL:** [https://api.workorder.goodyeartrucktires.com/](https://api.workorder.goodyeartrucktires.com/)
- **Base URL:** `https://api.workorder.goodyeartrucktires.com`

#### Tags

- Fleet Management
- Tires
- Work Orders

#### Properties

- [Portal](https://api.workorder.goodyeartrucktires.com/)
- [Postman Collection](collections/gaas-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gaas-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sightline-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sightline-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Goodyear Service Ticket API

The Goodyear Service Ticket API provides management of service tickets for commercial truck tire services.

- **Human URL:** [https://api.serviceticket.goodyeartrucktires.com/](https://api.serviceticket.goodyeartrucktires.com/)
- **Base URL:** `https://api.serviceticket.goodyeartrucktires.com`

#### Tags

- Fleet Management
- Service Tickets
- Tires

#### Properties

- [Portal](https://api.serviceticket.goodyeartrucktires.com/)
- [Postman Collection](collections/gaas-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gaas-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sightline-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sightline-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/goodyear)
- [LinkedIn](https://www.linkedin.com/company/goodyear)
- [Website](https://www.goodyear.com)
- [Portal](https://developer.goodyearsightline.com/)
- [Portal](https://gaas-portal.goodyear.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
