# IPGeolocation.io (ipgeolocation)

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

IPGeolocation.io is a multi-product IP intelligence platform offering IP geolocation, IP security/threat intelligence, ASN lookup, abuse contact, timezone, astronomy (sunrise, sunset, moon phase, celestial position), and user-agent parsing APIs. All endpoints are served under https://api.ipgeolocation.io with API-key authentication. The free plan offers 1,000 credits/day; paid plans (Starter through Premium) scale from 150K to 5M requests/month, with custom Enterprise pricing on top.

**APIs.json:** [https://ipgeolocation.io/](https://ipgeolocation.io/)

## Tags

- Geocoding
- IP Geolocation
- IP Intelligence
- IP Security
- ASN Lookup
- Abuse Contact
- Timezone
- Astronomy
- User Agent
- Threat Intelligence
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### IP Geolocation

Resolve any IPv4 / IPv6 address or domain name to a rich geolocation payload — country, region, city, lat/long, postal, currency, ASN, company, timezone, security signals, abuse contact, and user-agent enrichment. Includes single lookup (GET /v3/ipgeo) and bulk lookup (POST /v3/ipgeo-bulk, up to 50,000 entries per request, paid plans).

- **Human URL:** [https://ipgeolocation.io/ip-location-api.html](https://ipgeolocation.io/ip-location-api.html)
- **Base URL:** `https://api.ipgeolocation.io`

#### Tags

- IP Geolocation
- Geocoding
- IP Intelligence

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/ip-geolocation-api.html)
- [OpenAPI](openapi/ipgeolocation-ip-location-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipgeolocation-ip-location.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipgeolocation-ip-location.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-php)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-python-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-java-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-javascript-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-typescript-sdk)
- [SDK](https://www.npmjs.com/package/ip-geolocation-api-javascript-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-ruby-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-go-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-dotnet-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-kotlin-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-swift-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-rust-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-cpp-sdk)
- [SDK](https://github.com/IPGeolocation/ip-geolocation-api-jquery-sdk)

### IP Security

Threat-intelligence API that detects VPNs, proxies, Tor exit nodes, relay networks, bot activity, spam sources, residential proxies, cloud and data-center IPs, and assigns a threat score. Single lookup (GET /v3/security) and bulk lookup (POST /v3/security-bulk).

- **Human URL:** [https://ipgeolocation.io/ip-security-api.html](https://ipgeolocation.io/ip-security-api.html)
- **Base URL:** `https://api.ipgeolocation.io`

#### Tags

- IP Security
- Threat Intelligence
- VPN Detection
- Proxy Detection

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/ip-security-api.html)
- [OpenAPI](openapi/ipgeolocation-security-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipgeolocation-security.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipgeolocation-security.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ASN Lookup

Resolve an IP or ASN to Autonomous System metadata — owning organization, country, type (ISP, hosting, education, government), IP ranges, peers, and upstream/downstream relationships.

- **Human URL:** [https://ipgeolocation.io/asn-api.html](https://ipgeolocation.io/asn-api.html)
- **Base URL:** `https://api.ipgeolocation.io`

#### Tags

- ASN Lookup
- Network Intelligence

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/asn-api.html)
- [OpenAPI](openapi/ipgeolocation-asn-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipgeolocation-asn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipgeolocation-asn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IP Abuse Contact

Registry-sourced abuse contact information for any IPv4/IPv6 address — RIR, abuse email, network/route, country, and registry metadata. Useful for security operations, takedown workflows, and compliance.

- **Human URL:** [https://ipgeolocation.io/abuse-contact-api.html](https://ipgeolocation.io/abuse-contact-api.html)
- **Base URL:** `https://api.ipgeolocation.io`

#### Tags

- Abuse Contact
- Security Operations

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/abuse-contact-api.html)
- [OpenAPI](openapi/ipgeolocation-abuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipgeolocation-abuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipgeolocation-abuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Timezone

Resolve a timezone from name (e.g. America/New_York), IP address, or lat/long coordinates. Returns current date/time, UTC offset, DST status, DST transition windows, airport/locode metadata, and a convert endpoint to translate a timestamp between two zones.

- **Human URL:** [https://ipgeolocation.io/timezone-api.html](https://ipgeolocation.io/timezone-api.html)
- **Base URL:** `https://api.ipgeolocation.io`

#### Tags

- Timezone
- Date and Time

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/timezone-api.html)
- [OpenAPI](openapi/ipgeolocation-timezone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipgeolocation-timezone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipgeolocation-timezone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Astronomy

Astronomy data for any date and location — sunrise, sunset, solar noon, civil/nautical/astronomical twilight phases, moonrise, moonset, moon phase, illumination percentage, and altitude/azimuth for the sun and moon. Includes a /astronomy/timeSeries endpoint for date ranges.

- **Human URL:** [https://ipgeolocation.io/astronomy-api.html](https://ipgeolocation.io/astronomy-api.html)
- **Base URL:** `https://api.ipgeolocation.io`

#### Tags

- Astronomy
- Sunrise Sunset
- Moon Phase

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/astronomy-api.html)
- [OpenAPI](openapi/ipgeolocation-astronomy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipgeolocation-astronomy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipgeolocation-astronomy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### User Agent

Parse a User-Agent string into browser, engine, device, and operating system attributes. Supports single (GET /v3/user-agent — header-based, or POST /v3/user-agent — body-based) and bulk lookup (POST /v3/user-agent-bulk).

- **Human URL:** [https://ipgeolocation.io/user-agent-api.html](https://ipgeolocation.io/user-agent-api.html)
- **Base URL:** `https://api.ipgeolocation.io`

#### Tags

- User Agent
- Device Detection
- Browser Detection

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/user-agent-api.html)
- [OpenAPI](openapi/ipgeolocation-user-agent-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipgeolocation-user-agent.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipgeolocation-user-agent.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://ipgeolocation.io/)
- [Documentation](https://ipgeolocation.io/documentation)
- [Pricing](https://ipgeolocation.io/pricing.html)
- [Sign Up](https://app.ipgeolocation.io/signup)
- [Dashboard](https://app.ipgeolocation.io/)
- [GitHub Organization](https://github.com/IPGeolocation)
- [OpenAPI](https://github.com/IPGeolocation/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [C L I](https://github.com/IPGeolocation/cli)
- [Tools](https://github.com/IPGeolocation/ipgeolocation-io-mcp)
- [Tools](https://github.com/IPGeolocation/steampipe-plugin-ipgeolocation)
- [Tools](https://github.com/IPGeolocation/vercel-middleware)
- [Tools](https://github.com/IPGeolocation/n8n-nodes-ipgeolocation)
- [Tools](https://github.com/IPGeolocation/google-sheets)
- [Tools](https://github.com/IPGeolocation/es-ipgeo-ingest-processor)
- [Tools](https://github.com/IPGeolocation/mmdbio)
- [Tools](https://github.com/IPGeolocation/ipgeolocation-database-reader)
- [Integrations](https://github.com/IPGeolocation/splunk-docs)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Plans](plans/ipgeolocation-plans-pricing.yml)
- [Rate Limits](rate-limits/ipgeolocation-rate-limits.yml)
- [Fin Ops](finops/ipgeolocation-finops.yml)
- [Vocabulary](vocabulary/ipgeolocation-vocabulary.yml)
- [Rules](rules/ipgeolocation-rules.yml)
- [JSON-LD](json-ld/ipgeolocation-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
