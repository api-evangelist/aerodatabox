# AeroDataBox (aerodatabox)

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

AeroDataBox is an affordable aviation and flight data API platform tailored for small and medium businesses, individual developers, researchers, and students. Founded in 2019, the platform provides real-time and historical flight status, aircraft information, airport data, delay statistics, and flight alert webhooks through a RESTful API available on RapidAPI and API.Market. AeroDataBox covers global aviation data across airlines, aircraft, airports, and flight operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aerodatabox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aerodatabox/refs/heads/main/apis.yml)

## Tags

- Aviation
- Flights
- Aerospace
- Flight Data
- Airport Data

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-05-19

## APIs

### AeroDataBox Flight API

Provides real-time and historical flight status information including departure and arrival times, delays, codeshares, and flight number lookups. Supports FIDS (Flight Information Display System) data for airports and individual flight tracking by flight number, IATA/ICAO codes, and date ranges.

- **Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)
- **Base URL:** `https://prod.api.market/api/v1/aedbx/aerodatabox`

#### Tags

- Flights
- Flight Status
- FIDS
- Real-Time
- Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aerodatabox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aerodatabox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AeroDataBox Aircraft API

Search and retrieve aircraft information by tail number, registration, or ICAO24 hex code. Includes airline fleet lookups, aircraft registration history, and aircraft images. Supports searches by term for active aircraft registrations.

- **Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)
- **Base URL:** `https://prod.api.market/api/v1/aedbx/aerodatabox`

#### Tags

- Aircraft
- Tail Numbers
- Fleet
- Airlines
- Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aerodatabox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aerodatabox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AeroDataBox Airport API

Retrieve airport information by IATA/ICAO code including runway data, local time, solar time, and distance calculations between airports. Search airports by geographic location, IP address geolocation, or free-text term.

- **Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)
- **Base URL:** `https://prod.api.market/api/v1/aedbx/aerodatabox`

#### Tags

- Airports
- Runways
- Location Search
- Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aerodatabox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aerodatabox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AeroDataBox Statistical API

Access current and historical airport delay statistics, global delay summaries, daily route statistics, and flight delay data by flight number. Supports date range queries for trend analysis and performance benchmarking.

- **Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)
- **Base URL:** `https://prod.api.market/api/v1/aedbx/aerodatabox`

#### Tags

- Delays
- Statistics
- Routes
- Historical Data
- Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aerodatabox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aerodatabox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AeroDataBox Flight Alert API

Create, manage, and monitor webhook subscriptions for real-time flight status alerts. Subscribe to flight events by flight number or airport and receive push notifications to your endpoint when flight status changes occur.

- **Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)
- **Base URL:** `https://prod.api.market/api/v1/aedbx/aerodatabox`

#### Tags

- Webhooks
- Alerts
- Subscriptions
- Real-Time
- Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aerodatabox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aerodatabox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://doc.aerodatabox.com/)
- [Portal](https://www.aerodatabox.com/)
- [Marketplace](https://rapidapi.com/aerodatabox/api/aerodatabox)
- [Marketplace](https://api.market/store/aedbx/aerodatabox)
- [Pricing](https://www.aerodatabox.com/pricing)
- [Terms of Service](https://www.aerodatabox.com/terms-of-service)
- [Privacy Policy](https://www.aerodatabox.com/privacy-policy)
- [Contact](https://www.aerodatabox.com/contact)
- [Features](undefined)
- [Use Cases](undefined)
- [Spectral Rules](rules/aerodatabox-spectral-rules.yml)
- [Vocabulary](vocabulary/aerodatabox-vocabulary.yaml)
- [JSON-LD](json-ld/aerodatabox-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](undefined)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** http://apievangelist.com
