# Starwood Hotels and Resorts (starwood-hotels-and-resorts)

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
