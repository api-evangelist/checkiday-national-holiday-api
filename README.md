# Checkiday - National Holiday and Event API (checkiday-national-holiday-api)

Industry-leading Holiday and Event API by Checkiday, providing data on more than 5,000 national, international, and bizarre holidays and observances with thousands of descriptions, hashtags, images, founders, alternate names, and multi-year occurrence patterns. Routed through the apilayer marketplace with X-API-Key (apikey) header authentication and official client libraries for JavaScript, TypeScript, Python, C#, PHP, Go, Dart, Rust, and Java/Kotlin. Trusted since 2011 by media organizations including CNN, The New York Times, and USA Today.

**URL:** [Visit APIs.json URL](https://apilayer.com/marketplace/checkiday-api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Calendar, Holidays, Events, Observances, Dates, Time, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Checkiday Holiday and Event API
REST API delivering daily holiday and observance data. Provides three operations — list events for a date (`/events`), look up event details by id (`/event`), and full-text search across events (`/search`). Authenticated via the `apikey` header and routed through `api.apilayer.com/checkiday`. Monthly rate limits are returned with every response via `x-ratelimit-limit-month` and `x-ratelimit-remaining-month` headers.

**Human URL:** [https://apilayer.com/marketplace/checkiday-api](https://apilayer.com/marketplace/checkiday-api)

**Base URL:** `https://api.apilayer.com/checkiday`

#### Tags:

 - Calendar, Holidays, Events

#### Properties

- [Documentation](https://apilayer.com/marketplace/checkiday-api)
- [APIReference](https://apilayer.com/marketplace/checkiday-api)
- [OpenAPI](openapi/checkiday-openapi.yml)
- [Authentication](https://apilayer.com/marketplace/checkiday-api)
- [SignUp](https://apilayer.com/marketplace/checkiday-api#pricing)
- [Pricing](https://apilayer.com/marketplace/checkiday-api#pricing)
- [RateLimits](rate-limits/checkiday-rate-limits.yml)
- [Plans](plans/checkiday-plans-pricing.yml)
- [SDK — JavaScript/TypeScript](https://github.com/westy92/holiday-event-api-js)
- [SDK — Python](https://github.com/westy92/holiday-event-api-python)
- [SDK — C#](https://github.com/westy92/holiday-event-api-csharp)
- [SDK — PHP](https://github.com/westy92/holiday-event-api-php)
- [SDK — Go](https://github.com/westy92/holiday-event-api-go)
- [SDK — Dart](https://github.com/westy92/holiday-event-api-dart)
- [SDK — Rust](https://github.com/westy92/holiday-event-api-rust)
- [SDK — Java/Kotlin](https://github.com/westy92/holiday-event-api-java)
- [JSON Schema — Event Summary](json-schema/checkiday-event-summary-schema.json)
- [JSON Schema — Event Detail](json-schema/checkiday-event-detail-schema.json)
- [JSON Schema — GetEvents Response](json-schema/checkiday-get-events-response-schema.json)
- [JSON Schema — GetEventInfo Response](json-schema/checkiday-get-event-info-response-schema.json)
- [JSON Schema — Search Response](json-schema/checkiday-search-response-schema.json)
- [JSON Structure — Event Summary](json-structure/checkiday-event-summary-structure.json)
- [JSON Structure — Event Detail](json-structure/checkiday-event-detail-structure.json)
- [Example — Get Events](examples/checkiday-get-events-example.json)
- [Example — Get Event Info](examples/checkiday-get-event-info-example.json)
- [Example — Search](examples/checkiday-search-example.json)

## Common Properties

- [Website](https://apilayer.com/marketplace/checkiday-api)
- [Portal](https://apilayer.com/)
- [Marketplace](https://apilayer.com/marketplace)
- [SignUp](https://apilayer.com/marketplace/checkiday-api#pricing)
- [Login](https://apilayer.com/auth/login)
- [Pricing](https://apilayer.com/marketplace/checkiday-api#pricing)
- [TermsOfService](https://apilayer.com/terms)
- [PrivacyPolicy](https://apilayer.com/privacy-policy)
- [Support](https://apilayer.com/contact)
- [Contact](https://apilayer.com/contact)
- [StatusPage](https://status.apilayer.com/)
- [Blog](https://blog.apilayer.com/)
- [GitHubOrganization (SDK author)](https://github.com/westy92)
- [GitHubRepository (reference SDK)](https://github.com/westy92/holiday-event-api-js)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [JSON-LD Context](json-ld/checkiday-national-holiday-api-context.jsonld)
- [Checkiday Vocabulary](vocabulary/checkiday-national-holiday-api-vocabulary.yml)
- [Checkiday Spectral Rules](rules/checkiday-rules.yml)
- [Holiday Lookup Capability](capabilities/holiday-lookup.yaml)
- [Event Discovery Capability](capabilities/event-discovery.yaml)
- [Editorial Calendar Capability](capabilities/editorial-calendar.yaml)
- [Checkiday FinOps](finops/checkiday-finops.yml)

## Features

| Name | Description |
|------|-------------|
| 5,000+ Holidays | Coverage of more than 5,000 national, international, and bizarre holidays and observances across the calendar year. |
| Multi-day Event Awareness | Distinguishes single-day events, multi-day events that start on a date, and multi-day events still ongoing on a date. |
| Rich Event Detail | Each event exposes descriptions in plain text, HTML, and Markdown, plus alternate names, founders, hashtags, sources, and how-to-observe text. |
| Image Assets | Small, medium, and large image variants for each event suitable for editorial and social-media use. |
| Occurrence Patterns | Historical and forward-looking occurrence dates with configurable start and end year ranges, plus per-pattern length and observance rules. |
| Full-text Event Search | Search across all events by name or description with adult-content filtering. |
| Timezone-aware Date Lookups | IANA timezone parameter ensures the "today" date is calculated correctly across regions and DST boundaries. |
| Adult Content Filtering | Optional `adult` flag toggles inclusion of events that may be unsafe for viewing at work or by children. |
| Per-response Rate-limit Visibility | Every response echoes the monthly quota and remaining requests as JSON fields and HTTP headers. |
| Eight Official Client SDKs | First-party libraries for JavaScript, TypeScript, Python, C#, PHP, Go, Dart, Rust, and Java/Kotlin published to their canonical package registries. |

## Use Cases

| Name | Description |
|------|-------------|
| Editorial Calendar Planning | Newsrooms and content teams plan daily articles, social posts, and segments around recognized holidays and observances. |
| Social Media Automation | Schedulers and bots auto-generate hashtag-aware posts celebrating each day's holidays across multiple channels. |
| Marketing Campaign Triggers | E-commerce and retail platforms launch themed promotions tied to seasonal and bizarre holidays. |
| Chatbot and Assistant Enrichment | Conversational AI surfaces today's events when greeting users or building daily briefings. |
| Email and Push Notifications | Newsletter platforms include "today is..." segments using the events feed. |
| Restaurant and Hospitality Specials | Food-themed holidays drive daily menus, specials, and POS promotions. |
| Education and Classroom Activities | Teachers use holiday data to anchor lessons, vocabulary, and discussion topics. |

## Integrations

| Name | Description |
|------|-------------|
| Slack | Post the day's events into team channels via webhook automations. |
| Discord | Community bots (e.g. `1upbyte/Checkiday-Discord`) report the day's holidays in servers. |
| Zapier | Trigger workflows when specific holidays occur or are upcoming. |
| Make (Integromat) | Compose multi-step automations that consume the events feed. |
| HubSpot | Drive marketing-automation workflows from upcoming-holiday triggers. |
| Mailchimp | Inject today's holidays into transactional and broadcast emails. |
| Buffer | Schedule holiday-themed social posts in advance. |
| WordPress | Plugins embed today's holidays in publisher sidebars and blog posts. |
| Shopify | Holiday-aware merchandising and email triggers for storefronts. |
| Sopel IRC | `sopel-checkiday` community plugin surfaces holidays in IRC channels. |

## Solutions

| Name | Description |
|------|-------------|
| Free Tier | 100 monthly requests with no credit card for evaluation and hobby projects. |
| Basic Tier | 5,000 monthly requests at $9.99/month for small applications and indie publishers. |
| Pro Tier | 50,000 monthly requests at $49.99/month for production media and marketing workloads. |
| Enterprise Tier | 250,000 monthly requests at $99.99/month for high-volume publishers and platforms. |
| Custom Volume | Negotiated pricing above 250k requests for enterprises and aggregators. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Checkiday Holiday and Event API](openapi/checkiday-openapi.yml)

### JSON Schema

- [Event Summary](json-schema/checkiday-event-summary-schema.json)
- [Event Detail](json-schema/checkiday-event-detail-schema.json)
- [GetEvents Response](json-schema/checkiday-get-events-response-schema.json)
- [GetEventInfo Response](json-schema/checkiday-get-event-info-response-schema.json)
- [Search Response](json-schema/checkiday-search-response-schema.json)

### JSON Structure

- [Event Summary](json-structure/checkiday-event-summary-structure.json)
- [Event Detail](json-structure/checkiday-event-detail-structure.json)

### JSON-LD

- [Checkiday JSON-LD Context](json-ld/checkiday-national-holiday-api-context.jsonld)

### Examples

- [Get Events](examples/checkiday-get-events-example.json)
- [Get Event Info](examples/checkiday-get-event-info-example.json)
- [Search](examples/checkiday-search-example.json)

### Plans

- [Checkiday Plans and Pricing](plans/checkiday-plans-pricing.yml)

### Rate Limits

- [Checkiday Rate Limits](rate-limits/checkiday-rate-limits.yml)

### FinOps

- [Checkiday FinOps](finops/checkiday-finops.yml)

## Capabilities

Naftiko capabilities composed against the Checkiday Holiday and Event API.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Holiday Lookup](capabilities/holiday-lookup.yaml) | Checkiday | 1 | Application Developer |
| [Event Discovery](capabilities/event-discovery.yaml) | Checkiday | 2 | Product Engineer |
| [Editorial Calendar](capabilities/editorial-calendar.yaml) | Checkiday | 3 | Newsroom / Marketing |

## Vocabulary

- [Checkiday Vocabulary](vocabulary/checkiday-national-holiday-api-vocabulary.yml) — Domain taxonomy mapping 25 terms across events, observance patterns, occurrences, rate limits, and the apilayer delivery surface

## Rules

- [Checkiday Spectral Rules](rules/checkiday-rules.yml) — 10 rules enforcing Checkiday/apilayer API conventions covering operationId casing, summaries, tags, apikey security, rate-limit headers, query constraints, snake_case response fields, and base URL routing

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
