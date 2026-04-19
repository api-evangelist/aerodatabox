# AeroDataBox (aerodatabox)

AeroDataBox is an affordable aviation and flight data API platform tailored for small and medium businesses, individual developers, researchers, and students. Founded in 2019, the platform provides real-time and historical flight status, aircraft information, airport data, delay statistics, and flight alert webhooks through a RESTful API available on RapidAPI and API.Market. AeroDataBox covers global aviation data across airlines, aircraft, airports, and flight operations.

**URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Aviation
- Flights
- Aerospace
- Flight Data
- Airport Data

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-04-19

## APIs

### AeroDataBox Flight API

Provides real-time and historical flight status information including departure and arrival times, delays, codeshares, and FIDS data for airports and individual flight tracking.

**Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)

#### Tags

- Flights, Flight Status, FIDS, Real-Time, Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml)

### AeroDataBox Aircraft API

Search and retrieve aircraft information by tail number, registration, or ICAO24 hex code with airline fleet lookups and aircraft images.

**Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)

#### Tags

- Aircraft, Tail Numbers, Fleet, Airlines, Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml)

### AeroDataBox Airport API

Retrieve airport information by IATA/ICAO code including runway data, local time, solar time, and distance calculations. Search airports by location, IP, or text.

**Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)

#### Tags

- Airports, Runways, Location Search, Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml)

### AeroDataBox Statistical API

Access current and historical airport delay statistics, global delay summaries, daily route statistics, and flight delay data by flight number.

**Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)

#### Tags

- Delays, Statistics, Routes, Historical Data, Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml)

### AeroDataBox Flight Alert API

Create, manage, and monitor webhook subscriptions for real-time flight status alerts by flight number or airport.

**Human URL:** [https://doc.aerodatabox.com/](https://doc.aerodatabox.com/)

#### Tags

- Webhooks, Alerts, Subscriptions, Real-Time, Aviation

#### Properties

- [Documentation](https://doc.aerodatabox.com/)
- [OpenAPI](openapi/aerodatabox-openapi.yml)

## Common Properties

- [Documentation](https://doc.aerodatabox.com/)
- [Portal](https://www.aerodatabox.com/)
- [RapidAPI Marketplace](https://rapidapi.com/aerodatabox/api/aerodatabox)
- [API.Market Marketplace](https://api.market/store/aedbx/aerodatabox)
- [Pricing](https://www.aerodatabox.com/pricing)
- [Terms of Service](https://www.aerodatabox.com/terms-of-service)
- [Privacy Policy](https://www.aerodatabox.com/privacy-policy)
- [Contact](https://www.aerodatabox.com/contact)
- [Spectral Rules](rules/aerodatabox-spectral-rules.yml)
- [Vocabulary](vocabulary/aerodatabox-vocabulary.yaml)
- [Flight Tracking Capability](capabilities/flight-tracking.yaml)
- [JSON-LD Context](json-ld/aerodatabox-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Real-Time Flight Status | Live flight tracking with departure and arrival times, current status, and delay information for flights worldwide. |
| FIDS Airport Departures and Arrivals | Flight Information Display System data showing all departures and arrivals at any airport for a given time window. |
| Aircraft Search and Profiles | Lookup aircraft by tail number, registration, or ICAO24 hex code with fleet data, registration history, and images. |
| Airport Search by Location | Find airports by geographic coordinates, IP address geolocation, or free-text search with runway data included. |
| Flight Delay Statistics | Current and historical delay data for airports and specific flight numbers enabling trend analysis and SLA monitoring. |
| Webhook Flight Alerts | Push notification subscriptions for real-time flight status changes, supporting event-driven application architectures. |
| FAA LADD Status | FAA Limiting Aircraft Data Displayed status lookup to determine if an aircraft is opted out of public tracking. |
| Solar Time Calculations | Sunrise, sunset, and solar position data for any airport and date, useful for scheduling and operations planning. |
| Route Statistics | Daily route statistics for airports showing which routes operate and their frequency. |

## Use Cases

| Name | Description |
|------|-------------|
| Flight Tracking Applications | Build consumer or enterprise flight tracking apps using real-time status data for specific flights or all flights at an airport. |
| Travel Booking Notifications | Send flight status alerts to travelers by integrating webhook subscriptions for departure and arrival updates. |
| Airport Operations Intelligence | Monitor airport performance, delay patterns, and route activity for operations research and capacity planning. |
| Airline Research and Analysis | Analyze fleet composition, route networks, and on-time performance for competitive intelligence and market research. |
| Aviation Data Journalism | Access historical delay and route statistics for data-driven journalism and research on aviation trends. |
| Aircraft Valuation and Tracking | Track aircraft registrations and history for aviation finance, insurance, and asset management applications. |
| Trip Planning Tools | Integrate airport search, local time, and solar data into travel planning applications to enhance itinerary building. |

## Integrations

| Name | Description |
|------|-------------|
| RapidAPI | Available on RapidAPI Hub with interactive API playground and usage metering for easy developer onboarding. |
| API.Market | Available on API.Market marketplace with official OpenAPI v3 specifications for download and code generation. |
| Webhook Endpoints | Integrates with any webhook-capable endpoint for real-time flight status push notifications. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AeroDataBox API](openapi/aerodatabox-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Flight](capabilities/shared/flight.yaml) — 2 operations for real-time flight status and FIDS data
- [Aircraft](capabilities/shared/aircraft.yaml) — 2 operations for aircraft lookup and fleet data
- [Airport](capabilities/shared/airport.yaml) — 2 operations for airport data and location search

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Flight Tracking](capabilities/flight-tracking.yaml) | Flight, Aircraft, Airport | 6 | Developer |

## Vocabulary

- [AeroDataBox Vocabulary](vocabulary/aerodatabox-vocabulary.yaml) — Unified taxonomy mapping 7 APIs, 7 resources, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [AeroDataBox Spectral Rules](rules/aerodatabox-spectral-rules.yml) — 20 rules across 8 categories enforcing AeroDataBox API conventions

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
