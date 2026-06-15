# Starwood Hotels and Resorts (starwood-hotels-and-resorts)

Starwood Hotels & Resorts Worldwide was a global hotel and leisure company headquartered in Stamford, Connecticut. Prior to its acquisition by Marriott International in September 2016, Starwood operated and franchised hotels, resorts, and residences under iconic brands including Sheraton, Westin, W Hotels, St. Regis, Le Méridien, Four Points, Tribute Portfolio, Design Hotels, Element, and Aloft. The company also operated the Starwood Preferred Guest (SPG) loyalty program, which was later merged into Marriott Bonvoy. At the time of acquisition, Starwood managed over 1,300 properties in approximately 100 countries. Starwood exposed APIs for hotel search, property data, and loyalty program integration that were consumed by travel platforms and partners.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Hotel Search API

The Starwood Hotel Search API allowed partners and developers to search Starwood's portfolio of hotels and resorts by location, dates, and availability. It supported querying by country, province, city, and date range, returning property details including name, address, category, best available rate, and SPG points redemption options. This API underpinned partner booking integrations, OTA connections, and travel management platform integrations.

- **Human URL:** [https://www.starwoodhotels.com/](https://www.starwoodhotels.com/)
- **Base URL:** `https://www.starwoodhotels.com/api`

#### Tags

- Hotels
- Travel
- Hospitality
- Search
- Availability

#### Properties

- [Documentation](https://github.com/StayExpert/starwood)
- [OpenAPI](openapi/starwood-hotel-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/starwood-hotel-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starwood-hotel-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SPG Loyalty API

The Starwood Preferred Guest (SPG) Loyalty API provided programmatic access to the SPG loyalty program, enabling partners to query member point balances, redeem Starpoints, look up member status and tier information, and book award nights. The program offered Preferred, Gold, and Platinum status tiers with corresponding benefits. Following the Marriott acquisition, SPG was eventually merged into the Marriott Bonvoy loyalty program in 2019.

- **Human URL:** [https://www.starwoodhotels.com/preferredguest/](https://www.starwoodhotels.com/preferredguest/)
- **Base URL:** `https://www.starwoodhotels.com/api/spg`

#### Tags

- Loyalty
- Rewards
- Hotels
- Travel
- Hospitality

#### Properties

- [Documentation](https://www.starwoodhotels.com/preferredguest/)
- [Postman Collection](collections/starwood-hotel-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starwood-hotel-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Property Data API

The Starwood Property Data API provided detailed information about individual hotel properties including room types, amenities, dining options, meeting and event spaces, photos, geo-coordinates, and contact information. Partners used this API to populate travel booking sites and corporate travel management systems with accurate Starwood property content.

- **Human URL:** [https://www.starwoodhotels.com/](https://www.starwoodhotels.com/)
- **Base URL:** `https://www.starwoodhotels.com/api/properties`

#### Tags

- Hotels
- Properties
- Travel
- Content
- Hospitality

#### Properties

- [Documentation](https://www.starwoodhotels.com/)
- [Postman Collection](collections/starwood-hotel-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starwood-hotel-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.starwoodhotels.com)
- [Developer  Portal](https://github.com/StayExpert/starwood)
- [LinkedIn](https://www.linkedin.com/company/starwoodhotels)
- [Facebook](https://www.facebook.com/starwood)
- [Blog](https://www.starwoodhotels.com/corporate/)
- [Acquisition](https://marriott.gcs-web.com/news-releases/news-release-details/marriott-international-completes-acquisition-starwood-hotels)
- [Terms of Service](https://www.starwoodhotels.com/corporate/terms.html)
- [Privacy Policy](https://www.starwoodhotels.com/corporate/privacy.html)
- [OpenAPI](openapi/starwood-hotel-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/starwood-hotel-search-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/starwood-hotel-structure.json)
- [JSON-LD](json-ld/starwood-hotels-and-resorts-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/starwood-hotels-and-resorts-vocabulary.yml)
- [Spectral Rules](rules/starwood-hotels-and-resorts-rules.yml)
