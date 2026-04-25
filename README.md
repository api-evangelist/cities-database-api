# Cities Database API (cities-database-api)
The Cities Database API by AirLabs provides a global reference dataset of cities keyed to IATA metropolitan area codes, ISO country codes, and geographic coordinates. The API is consumed alongside the AirLabs Airports, Airlines, and Flights APIs to power travel search, mapping, geocoding, and clustering experiences.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cities-database-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Cities, Data, Geography, Locations, Reference Data, Travel

## Timestamps

- **Created:** 2024-03-30
- **Modified:** 2026-04-23

## APIs

### AirLabs Cities API
The AirLabs Cities API exposes a single `GET /cities` endpoint that returns a list of cities filterable by IATA `city_code`, ISO 2 `country_code`, or comma-separated `_fields`. Free-tier responses include name, city_code, latitude, longitude, and country_code; paid tiers add UN/LOCODE, elevation, timezone, population, multilingual names, Wikipedia links, and SEO slugs.

**Human URL:** [https://airlabs.co/docs/cities](https://airlabs.co/docs/cities)

**Base URL:** `https://airlabs.co/api/v9`

#### Tags:

 - Cities, Geography, IATA, Reference Data, Travel

#### Properties

- [Documentation](https://airlabs.co/docs/cities)
- [API Reference](https://airlabs.co/docs)
- [Authentication](https://airlabs.co/account/api-key)
- [OpenAPI](openapi/cities-database-api-openapi.yml)

## Common Properties

- [Website](https://airlabs.co/)
- [Documentation](https://airlabs.co/docs)
- [Pricing](https://airlabs.co/pricing)
- [Sign Up](https://airlabs.co/signup)
- [Login](https://airlabs.co/login)
- [Account](https://airlabs.co/account)
- [Authentication](https://airlabs.co/account/api-key)
- [Privacy Policy](https://airlabs.co/privacy)
- [Terms of Service](https://airlabs.co/terms)
- [Support](https://airlabs.co/contact)
- [Status](https://airlabs.co/status)
- [JSON-LD Context](json-ld/cities-database-api-context.jsonld)
- [JSON Schema](json-schema/cities-database-api-city-schema.json)
- [Spectral Ruleset](rules/cities-database-api-rules.yml)
- [Naftiko Capabilities](capabilities/cities-database-api-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
