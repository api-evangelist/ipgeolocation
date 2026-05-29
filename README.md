# IPGeolocation.io (ipgeolocation)

IPGeolocation.io is a multi-product IP intelligence platform offering IP
geolocation, IP security/threat intelligence, ASN lookup, abuse contact,
timezone, astronomy (sunrise, sunset, moon phase, celestial position), and
user-agent parsing APIs. All endpoints are served under
`https://api.ipgeolocation.io` with API-key authentication. The free plan
offers 1,000 credits/day; paid plans (Starter through Premium) scale from
150K to 5M requests/month, with custom Enterprise pricing on top.

**URL:** [https://ipgeolocation.io/](https://ipgeolocation.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Geocoding, IP Geolocation, IP Intelligence, IP Security, ASN Lookup, Abuse Contact, Timezone, Astronomy, User Agent, Threat Intelligence, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### IP Geolocation

Resolve any IPv4 / IPv6 address or domain name to a rich geolocation payload — country, region, city, lat/long, postal, currency, ASN, company, timezone, security signals, abuse contact, and user-agent enrichment. Includes single lookup (`GET /v3/ipgeo`) and bulk lookup (`POST /v3/ipgeo-bulk`, up to 50,000 entries per request, paid plans).

**Human URL:** [https://ipgeolocation.io/ip-location-api.html](https://ipgeolocation.io/ip-location-api.html)

#### Tags

 - IP Geolocation, Geocoding, IP Intelligence

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/ip-geolocation-api.html)
- [OpenAPI](openapi/ipgeolocation-ip-location-openapi.yml)
- [PHP SDK](https://github.com/IPGeolocation/ip-geolocation-api-php)
- [Python SDK](https://github.com/IPGeolocation/ip-geolocation-api-python-sdk)
- [Java SDK](https://github.com/IPGeolocation/ip-geolocation-api-java-sdk)
- [JavaScript SDK](https://github.com/IPGeolocation/ip-geolocation-api-javascript-sdk)
- [TypeScript SDK](https://github.com/IPGeolocation/ip-geolocation-api-typescript-sdk)
- [Node.js SDK](https://www.npmjs.com/package/ip-geolocation-api-javascript-sdk)
- [Ruby SDK](https://github.com/IPGeolocation/ip-geolocation-ruby-sdk)
- [Go SDK](https://github.com/IPGeolocation/ip-geolocation-go-sdk)
- [.NET SDK](https://github.com/IPGeolocation/ip-geolocation-api-dotnet-sdk)
- [Kotlin SDK](https://github.com/IPGeolocation/ip-geolocation-api-kotlin-sdk)
- [Swift SDK](https://github.com/IPGeolocation/ip-geolocation-api-swift-sdk)
- [Rust SDK](https://github.com/IPGeolocation/ip-geolocation-api-rust-sdk)
- [C++ SDK](https://github.com/IPGeolocation/ip-geolocation-api-cpp-sdk)
- [jQuery SDK](https://github.com/IPGeolocation/ip-geolocation-api-jquery-sdk)
- [Naftiko Capability — IP Geolocation](capabilities/ip-location-ip-geolocation.yaml)

### IP Security

Threat-intelligence API that detects VPNs, proxies, Tor exit nodes, relay networks, bot activity, spam sources, residential proxies, cloud and data-center IPs, and assigns a threat score. Single lookup (`GET /v3/security`) and bulk lookup (`POST /v3/security-bulk`).

**Human URL:** [https://ipgeolocation.io/ip-security-api.html](https://ipgeolocation.io/ip-security-api.html)

#### Tags

 - IP Security, Threat Intelligence, VPN Detection, Proxy Detection

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/ip-security-api.html)
- [OpenAPI](openapi/ipgeolocation-security-openapi.yml)
- [Naftiko Capability — IP Security](capabilities/security-ip-security.yaml)

### ASN Lookup

Resolve an IP or ASN to Autonomous System metadata — owning organization, country, type (ISP, hosting, education, government), IP ranges, peers, and upstream/downstream relationships.

**Human URL:** [https://ipgeolocation.io/asn-api.html](https://ipgeolocation.io/asn-api.html)

#### Tags

 - ASN Lookup, Network Intelligence

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/asn-api.html)
- [OpenAPI](openapi/ipgeolocation-asn-openapi.yml)
- [Naftiko Capability — ASN Lookup](capabilities/asn-asn-lookup.yaml)

### IP Abuse Contact

Registry-sourced abuse contact information for any IPv4/IPv6 address — RIR, abuse email, network/route, country, and registry metadata. Useful for security operations, takedown workflows, and compliance.

**Human URL:** [https://ipgeolocation.io/abuse-contact-api.html](https://ipgeolocation.io/abuse-contact-api.html)

#### Tags

 - Abuse Contact, Security Operations

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/abuse-contact-api.html)
- [OpenAPI](openapi/ipgeolocation-abuse-openapi.yml)
- [Naftiko Capability — IP Abuse Contact](capabilities/abuse-ip-abuse-contact.yaml)

### Timezone

Resolve a timezone from name (e.g. `America/New_York`), IP address, or lat/long coordinates. Returns current date/time, UTC offset, DST status, DST transition windows, airport/locode metadata, and a convert endpoint to translate a timestamp between two zones.

**Human URL:** [https://ipgeolocation.io/timezone-api.html](https://ipgeolocation.io/timezone-api.html)

#### Tags

 - Timezone, Date and Time

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/timezone-api.html)
- [OpenAPI](openapi/ipgeolocation-timezone-openapi.yml)
- [Naftiko Capability — Timezone](capabilities/timezone-timezone.yaml)

### Astronomy

Astronomy data for any date and location — sunrise, sunset, solar noon, civil/nautical/astronomical twilight phases, moonrise, moonset, moon phase, illumination percentage, and altitude/azimuth for the sun and moon. Includes a `/astronomy/timeSeries` endpoint for date ranges.

**Human URL:** [https://ipgeolocation.io/astronomy-api.html](https://ipgeolocation.io/astronomy-api.html)

#### Tags

 - Astronomy, Sunrise Sunset, Moon Phase

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/astronomy-api.html)
- [OpenAPI](openapi/ipgeolocation-astronomy-openapi.yml)
- [Naftiko Capability — Astronomy](capabilities/astronomy-astronomy.yaml)

### User Agent

Parse a User-Agent string into browser, engine, device, and operating-system attributes. Supports single (`GET /v3/user-agent` — header-based, or `POST /v3/user-agent` — body-based) and bulk lookup (`POST /v3/user-agent-bulk`).

**Human URL:** [https://ipgeolocation.io/user-agent-api.html](https://ipgeolocation.io/user-agent-api.html)

#### Tags

 - User Agent, Device Detection, Browser Detection

#### Properties

- [Documentation](https://ipgeolocation.io/documentation/user-agent-api.html)
- [OpenAPI](openapi/ipgeolocation-user-agent-openapi.yml)
- [Naftiko Capability — User Agent](capabilities/user-agent-user-agent.yaml)

## Common Properties

- [Website](https://ipgeolocation.io/)
- [Documentation](https://ipgeolocation.io/documentation)
- [Pricing](https://ipgeolocation.io/pricing.html)
- [Sign Up](https://app.ipgeolocation.io/signup)
- [Dashboard](https://app.ipgeolocation.io/)
- [GitHub Organization](https://github.com/IPGeolocation)
- [Combined OpenAPI Spec](https://github.com/IPGeolocation/openapi)
- [CLI](https://github.com/IPGeolocation/cli)
- [MCP Server](https://github.com/IPGeolocation/ipgeolocation-io-mcp)
- [Steampipe Plugin](https://github.com/IPGeolocation/steampipe-plugin-ipgeolocation)
- [Vercel Edge Middleware](https://github.com/IPGeolocation/vercel-middleware)
- [n8n Node](https://github.com/IPGeolocation/n8n-nodes-ipgeolocation)
- [Google Sheets Add-on](https://github.com/IPGeolocation/google-sheets)
- [Elasticsearch Ingest Processor](https://github.com/IPGeolocation/es-ipgeo-ingest-processor)
- [MMDB CLI (mmdbio)](https://github.com/IPGeolocation/mmdbio)
- [Database Reader](https://github.com/IPGeolocation/ipgeolocation-database-reader)
- [Splunk App](https://github.com/IPGeolocation/splunk-docs)
- [public-apis Listing](https://github.com/public-apis/public-apis)
- [Plans](plans/ipgeolocation-plans-pricing.yml)
- [Rate Limits](rate-limits/ipgeolocation-rate-limits.yml)
- [FinOps](finops/ipgeolocation-finops.yml)
- [Vocabulary](vocabulary/ipgeolocation-vocabulary.yml)
- [Rules](rules/ipgeolocation-rules.yml)
- [JSON-LD Context](json-ld/ipgeolocation-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| 7-Product API Suite | IP Geolocation, IP Security, ASN Lookup, Abuse Contact, Timezone, Astronomy, and User-Agent parsing — all behind one API key. |
| Bulk Endpoints | Bulk lookup endpoints (up to 50,000 entries per request) for IP geolocation, IP security, and user-agent parsing on paid plans. |
| 14 Official SDKs | First-party SDKs for PHP, Python, Java, JavaScript, TypeScript, Node, Ruby, Go, .NET, Kotlin, Swift, Rust, C++, and jQuery. |
| MCP Server | Official Model Context Protocol server exposing every product (geo, security, ASN, timezone, astronomy, user-agent) as MCP tools for Claude, Cursor, Copilot, and other MCP-aware clients. |
| Edge and Platform Integrations | Vercel edge middleware, Cloudflare-friendly client, Steampipe plugin, Elasticsearch ingest processor, n8n node, Google Sheets add-on, Splunk app, and WordPress / Shopify / Pipedream / Zapier / Make integrations. |
| MMDB Database Products | Downloadable MMDB databases for offline geolocation, security, ASN, company, abuse-contact, WHOIS, hosting, and residential-proxy lookups (Geo Standard, Geo Advance, Security Pro tiers). |

## Use Cases

| Name | Description |
|------|-------------|
| Personalize and Localize Web Experiences | Detect a visitor's country, currency, and timezone to tailor language, pricing, and content at the edge. |
| Compliance and Geo-Blocking | Enforce sanctions, age-gates, or licensing rules by blocking or redirecting traffic from specific countries or networks at the Vercel/CDN edge. |
| Fraud and Abuse Prevention | Score signups, logins, and transactions using VPN/proxy/Tor detection, threat scoring, and ASN type (hosting vs residential). |
| SOC Triage and Takedown | Resolve abuse contacts and ASN owners for IOCs during incident response and abuse reporting. |
| Scheduling and Astronomy | Power scheduling, lighting automation, agriculture, and observatory tooling with high-precision sunrise/sunset and moon-phase data. |
| Audience Analytics | Enrich logs and analytics events with country, city, ISP, and device info to segment users and dashboards. |

## Integrations

| Name | Description |
|------|-------------|
| Vercel Edge Middleware | Geo-block, redirect, and detect VPN/proxy/Tor at the Vercel edge. |
| Splunk App | Enrich Splunk events with IP intelligence. |
| Elasticsearch Ingest Processor | Enrich documents indexed into Elasticsearch. |
| Steampipe Plugin | Query IP intelligence via SQL. |
| n8n Node | First-party node for n8n workflow automation. |
| Google Sheets Add-on | Look up IPs directly from spreadsheets. |
| Zapier | Trigger workflows on IP intelligence enrichment. |
| Make (Integromat) | Compose IP lookups into Make scenarios. |
| Pipedream | Source step for Pipedream automations. |
| WordPress Plugin | Personalize and protect WordPress sites. |
| Shopify App | Geo-route Shopify customers and enforce regional rules. |
| Microsoft Copilot Connector | Surface IP intelligence inside Microsoft Copilot. |
| Maltego Transform | Pivot from IP to ASN, geo, and security in Maltego investigations. |

## Solutions

| Name | Description |
|------|-------------|
| Real-Time API Lookup | Sub-50ms IP intelligence over HTTPS with a single API key. |
| Downloadable MMDB Databases | Offline-capable MMDB files (Geo Standard, Geo Advance, Security Pro) for embedded or air-gapped use cases. |
| Edge-Native Integrations | Drop-in middleware for Vercel, Cloudflare Workers, and other edge runtimes for personalization and geo-blocking without an extra hop. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [IPGeolocation.io: Abuse Contact API](openapi/ipgeolocation-abuse-openapi.yml)
- [IPGeolocation.io: ASN Lookup API](openapi/ipgeolocation-asn-openapi.yml)
- [IPGeolocation.io: Astronomy API](openapi/ipgeolocation-astronomy-openapi.yml)
- [IPGeolocation.io: IPGeolocation API](openapi/ipgeolocation-ip-location-openapi.yml)
- [IPGeolocation.io: IP Security API](openapi/ipgeolocation-security-openapi.yml)
- [IPGeolocation.io: Date, Time & Timezone API](openapi/ipgeolocation-timezone-openapi.yml)
- [IPGeolocation.io: User Agent API](openapi/ipgeolocation-user-agent-openapi.yml)

### JSON Schema

47 schemas extracted from the seven OpenAPI specs. See [json-schema/](json-schema/).

### JSON Structure

47 JSON Structure (json-structure.org) files generated from the JSON Schemas. See [json-structure/](json-structure/).

### JSON-LD

Eight JSON-LD 1.1 context documents — one per API plus a master combined context — at [json-ld/](json-ld/):

- [ipgeolocation-context.jsonld](json-ld/ipgeolocation-context.jsonld) — combined master context
- [ipgeolocation-ip-location-context.jsonld](json-ld/ipgeolocation-ip-location-context.jsonld)
- [ipgeolocation-security-context.jsonld](json-ld/ipgeolocation-security-context.jsonld)
- [ipgeolocation-asn-context.jsonld](json-ld/ipgeolocation-asn-context.jsonld)
- [ipgeolocation-abuse-context.jsonld](json-ld/ipgeolocation-abuse-context.jsonld)
- [ipgeolocation-timezone-context.jsonld](json-ld/ipgeolocation-timezone-context.jsonld)
- [ipgeolocation-astronomy-context.jsonld](json-ld/ipgeolocation-astronomy-context.jsonld)
- [ipgeolocation-user-agent-context.jsonld](json-ld/ipgeolocation-user-agent-context.jsonld)

### Examples

47 generated JSON example payloads — one per schema — at [examples/](examples/).

## Capabilities

Naftiko capabilities organized as self-contained, flat-file business surfaces. Each file inlines its own `consumes` block plus a REST exposer and an MCP exposer.

| Capability | API | Operations | File |
|---|---|---|---|
| IP Geolocation | IP Geolocation | 2 | [capabilities/ip-location-ip-geolocation.yaml](capabilities/ip-location-ip-geolocation.yaml) |
| IP Security | IP Security | 2 | [capabilities/security-ip-security.yaml](capabilities/security-ip-security.yaml) |
| ASN Lookup | ASN Lookup | 1 | [capabilities/asn-asn-lookup.yaml](capabilities/asn-asn-lookup.yaml) |
| IP Abuse Contact | IP Abuse Contact | 1 | [capabilities/abuse-ip-abuse-contact.yaml](capabilities/abuse-ip-abuse-contact.yaml) |
| Timezone | Timezone | 2 | [capabilities/timezone-timezone.yaml](capabilities/timezone-timezone.yaml) |
| Astronomy | Astronomy | 2 | [capabilities/astronomy-astronomy.yaml](capabilities/astronomy-astronomy.yaml) |
| User Agent | User Agent | 3 | [capabilities/user-agent-user-agent.yaml](capabilities/user-agent-user-agent.yaml) |

## Vocabulary

- [IPGeolocation.io Vocabulary](vocabulary/ipgeolocation-vocabulary.yml) — Unified taxonomy mapping 7 resources, 7 actions, 7 workflows, and 6 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Plans, Rate Limits, and FinOps

- [Plans and Pricing](plans/ipgeolocation-plans-pricing.yml) — 10 plans (Free + Starter/Plus/Pro/Business/Premium/Enterprise + three MMDB database tiers) modeled with API Commons Plans 0.1.
- [Rate Limits](rate-limits/ipgeolocation-rate-limits.yml) — Free 1,000/day hard cap; paid plans have no per-second/minute/hour/day cap (only the monthly credit quota).
- [FinOps](finops/ipgeolocation-finops.yml) — FOCUS 1.3-aligned billing model: tiered monthly subscription + per-block overage meters, plus custom-quoted MMDB licences.

## Rules

- [IPGeolocation Spectral Rules](rules/ipgeolocation-rules.yml) — 38 opinionated rules across 13 categories enforcing IPGeolocation.io API conventions (HTTPS-only, v3-prefixed paths, apiKey query auth, camelCase operationIds, snake/camel schema properties, bulk-must-be-POST, etc.).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
