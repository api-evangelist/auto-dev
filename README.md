# Auto.dev (auto-dev)

Auto.dev provides automotive data APIs for developers and AI agents, including global VIN decoding, used-car vehicle listings with real-time market pricing and dealer data, vehicle specifications, photos, and NHTSA safety recalls. The REST API is served from https://api.auto.dev with API key authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/auto-dev/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/auto-dev/refs/heads/main/apis.yml)

## Tags

- Automotive
- Vehicle Data
- VIN Decoding
- Vehicle Listings
- Recalls

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Auto.dev VIN Decoding API

Decodes any valid 17-character VIN into make, model, year, trim, engine, body, drivetrain, and transmission. Also exposes a specifications endpoint returning detailed build features and base MSRP/invoice pricing.

- **Human URL:** [https://docs.auto.dev/v2/products/vin-decode](https://docs.auto.dev/v2/products/vin-decode)
- **Base URL:** `https://api.auto.dev`

#### Tags

- VIN Decoding
- Vehicle Data
- Specifications

#### Properties

- [Documentation](https://docs.auto.dev/v2/products/vin-decode)
- [API Reference](https://docs.auto.dev/v2/products/vin-decode)
- [OpenAPI](openapi/auto-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/auto-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/auto-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Auto.dev Listings / Search API

Searches used-car inventory from US physical and online dealers, filterable by make, model, year, price, location, and CPO status, with cursor and page-based pagination, plus single-listing lookup by VIN.

- **Human URL:** [https://docs.auto.dev/v2/products/vehicle-listings](https://docs.auto.dev/v2/products/vehicle-listings)
- **Base URL:** `https://api.auto.dev`

#### Tags

- Vehicle Listings
- Used Cars
- Search

#### Properties

- [Documentation](https://docs.auto.dev/v2/products/vehicle-listings)
- [API Reference](https://docs.auto.dev/v2/products/vehicle-listings)
- [OpenAPI](openapi/auto-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/auto-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/auto-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Auto.dev Market Value / Pricing API

Surfaces real-time retail pricing on listings and base MSRP / invoice pricing on the specifications endpoint, alongside a vehicle photos endpoint returning image galleries for inventory and listings.

- **Human URL:** [https://docs.auto.dev/v2/products](https://docs.auto.dev/v2/products)
- **Base URL:** `https://api.auto.dev`

#### Tags

- Market Value
- Pricing
- Vehicle Photos

#### Properties

- [Documentation](https://docs.auto.dev/v2/products)
- [OpenAPI](openapi/auto-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/auto-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/auto-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Auto.dev Dealers API

Returns dealer information embedded in vehicle listings, including dealer name, location, and contact data resolved by zip-code and distance filters for proximity-based inventory discovery.

- **Human URL:** [https://docs.auto.dev/v2/products/vehicle-listings](https://docs.auto.dev/v2/products/vehicle-listings)
- **Base URL:** `https://api.auto.dev`

#### Tags

- Dealers
- Inventory
- Location

#### Properties

- [Documentation](https://docs.auto.dev/v2/products/vehicle-listings)
- [OpenAPI](openapi/auto-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/auto-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/auto-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Auto.dev Recalls API

Returns NHTSA safety recall data by VIN. The open-recalls endpoint filters to only active and unresolved recalls requiring attention, with campaign numbers, components, consequences, and remedy status.

- **Human URL:** [https://docs.auto.dev/v2/products/open-recalls](https://docs.auto.dev/v2/products/open-recalls)
- **Base URL:** `https://api.auto.dev`

#### Tags

- Recalls
- Safety
- NHTSA

#### Properties

- [Documentation](https://docs.auto.dev/v2/products/open-recalls)
- [API Reference](https://docs.auto.dev/v2/products/open-recalls)
- [OpenAPI](openapi/auto-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/auto-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/auto-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/drivly)
- [LinkedIn](https://www.linkedin.com/company/auto-dev)
- [Website](https://www.auto.dev)
- [Documentation](https://docs.auto.dev)
- [Plans](plans/auto-dev-plans-pricing.yml)
- [Rate Limits](rate-limits/auto-dev-rate-limits.yml)
- [Fin Ops](finops/auto-dev-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
