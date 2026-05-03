# Starwood Hotels and Resorts

Starwood Hotels & Resorts Worldwide was a global hotel and leisure company headquartered in Stamford, Connecticut. Prior to its acquisition by Marriott International in September 2016, Starwood operated and franchised hotels, resorts, and residences under iconic brands including Sheraton, Westin, W Hotels, St. Regis, Le Méridien, Four Points, Tribute Portfolio, Design Hotels, Element, and Aloft. The company also operated the Starwood Preferred Guest (SPG) loyalty program, which was later merged into Marriott Bonvoy. At the time of acquisition, Starwood managed over 1,300 properties in approximately 100 countries.

**Website:** [https://www.starwoodhotels.com](https://www.starwoodhotels.com)

## APIs

### Hotel Search API

Search Starwood's portfolio of hotels and resorts by location, dates, and availability. Supports querying by country, province, city, and date range, returning property details including name, address, SPG category, best available rate, and Starpoints redemption options.

- **Documentation:** [https://github.com/StayExpert/starwood](https://github.com/StayExpert/starwood)
- **OpenAPI:** [openapi/starwood-hotel-search-openapi.yml](openapi/starwood-hotel-search-openapi.yml)

### SPG Loyalty API

Programmatic access to the Starwood Preferred Guest (SPG) loyalty program, enabling partners to query member point balances, redeem Starpoints, look up member status and tier information, and book award nights.

- **Documentation:** [https://www.starwoodhotels.com/preferredguest/](https://www.starwoodhotels.com/preferredguest/)

### Property Data API

Detailed information about individual hotel properties including room types, amenities, dining options, meeting and event spaces, photos, geo-coordinates, and contact information.

- **Documentation:** [https://www.starwoodhotels.com/](https://www.starwoodhotels.com/)

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| Hotel Search API | [openapi/starwood-hotel-search-openapi.yml](openapi/starwood-hotel-search-openapi.yml) |

### JSON Schema

| Schema | File |
|--------|------|
| Hotel | [json-schema/starwood-hotel-search-schema.json](json-schema/starwood-hotel-search-schema.json) |

### JSON Structure

| Structure | File |
|-----------|------|
| Hotel | [json-structure/starwood-hotel-structure.json](json-structure/starwood-hotel-structure.json) |

### JSON-LD Context

| Context | File |
|---------|------|
| Starwood Hotels and Resorts | [json-ld/starwood-hotels-and-resorts-context.jsonld](json-ld/starwood-hotels-and-resorts-context.jsonld) |

### Examples

| Example | File |
|---------|------|
| Search Hotels | [examples/starwood-search-hotels-example.json](examples/starwood-search-hotels-example.json) |

### Spectral Rules

| Ruleset | File |
|---------|------|
| Starwood Hotels and Resorts | [rules/starwood-hotels-and-resorts-rules.yml](rules/starwood-hotels-and-resorts-rules.yml) |

### Naftiko Capabilities

| Capability | Description |
|-----------|-------------|
| [Hotel Booking](capabilities/hotel-booking.yaml) | Hotel search, property lookup, and availability workflow for OTA and travel management platforms |

**Shared Definitions:**

| Shared | File |
|--------|------|
| Hotel Search | [capabilities/shared/hotel-search.yaml](capabilities/shared/hotel-search.yaml) |

### Vocabulary

| Vocabulary | File |
|-----------|------|
| Starwood Hotels and Resorts | [vocabulary/starwood-hotels-and-resorts-vocabulary.yml](vocabulary/starwood-hotels-and-resorts-vocabulary.yml) |

## Resources

- [Developer Portal (Third-Party SDK)](https://github.com/StayExpert/starwood)
- [LinkedIn](https://www.linkedin.com/company/starwoodhotels)
- [Marriott Acquisition Announcement](https://marriott.gcs-web.com/news-releases/news-release-details/marriott-international-completes-acquisition-starwood-hotels)
- [Terms of Service](https://www.starwoodhotels.com/corporate/terms.html)
- [Privacy Policy](https://www.starwoodhotels.com/corporate/privacy.html)
