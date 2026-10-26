# Checkiday - National Holiday and Event API (checkiday-national-holiday-api)

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

Industry-leading Holiday and Event API by Checkiday, providing data on more
than 5,000 national, international, and bizarre holidays and observances with
thousands of descriptions, hashtags, images, founders, alternate names, and
multi-year occurrence patterns. Routed through the apilayer marketplace with
X-API-Key (apikey) header authentication and official client libraries for
JavaScript, TypeScript, Python, C#, PHP, Go, Dart, Rust, and Java/Kotlin.
Trusted since 2011 by media organizations including CNN, The New York Times,
and USA Today.

**APIs.json:** [https://apilayer.com/marketplace/checkiday-api](https://apilayer.com/marketplace/checkiday-api)

## Tags

- Calendar
- Holidays
- Events
- Observances
- Dates
- Time
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Checkiday Holiday and Event API

REST API delivering daily holiday and observance data. Provides three
operations — list events for a date (`/events`), look up event details
by id (`/event`), and full-text search across events (`/search`).
Authenticated via the `apikey` header and routed through
`api.apilayer.com/checkiday`. Monthly rate limits are returned with
every response via `x-ratelimit-limit-month` and
`x-ratelimit-remaining-month` headers.

- **Human URL:** [https://apilayer.com/marketplace/checkiday-api](https://apilayer.com/marketplace/checkiday-api)
- **Base URL:** `https://api.apilayer.com/checkiday`

#### Tags

- Calendar
- Holidays
- Events

#### Properties

- [Documentation](https://apilayer.com/marketplace/checkiday-api)
- [API Reference](https://apilayer.com/marketplace/checkiday-api)
- [OpenAPI](openapi/checkiday-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkiday.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkiday.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://apilayer.com/marketplace/checkiday-api)
- [Sign Up](https://apilayer.com/marketplace/checkiday-api#pricing)
- [Pricing](https://apilayer.com/marketplace/checkiday-api#pricing)
- [Rate Limits](rate-limits/checkiday-rate-limits.yml)
- [Plans](plans/checkiday-plans-pricing.yml)
- [SDK](https://github.com/westy92/holiday-event-api-js)
- [SDK](https://github.com/westy92/holiday-event-api-python)
- [SDK](https://github.com/westy92/holiday-event-api-csharp)
- [SDK](https://github.com/westy92/holiday-event-api-php)
- [SDK](https://github.com/westy92/holiday-event-api-go)
- [SDK](https://github.com/westy92/holiday-event-api-dart)
- [SDK](https://github.com/westy92/holiday-event-api-rust)
- [SDK](https://github.com/westy92/holiday-event-api-java)
- [JSON Schema](json-schema/checkiday-event-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/checkiday-event-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/checkiday-get-events-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/checkiday-get-event-info-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/checkiday-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/checkiday-event-summary-structure.json)
- [JSON Structure](json-structure/checkiday-event-detail-structure.json)
- [Code Examples](examples/checkiday-get-events-example.json)
- [Code Examples](examples/checkiday-get-event-info-example.json)
- [Code Examples](examples/checkiday-search-example.json)

## Common Properties

- [Website](https://apilayer.com/marketplace/checkiday-api)
- [Portal](https://apilayer.com/)
- [Marketplace](https://apilayer.com/marketplace)
- [Sign Up](https://apilayer.com/marketplace/checkiday-api#pricing)
- [Login](https://apilayer.com/auth/login)
- [Pricing](https://apilayer.com/marketplace/checkiday-api#pricing)
- [Terms of Service](https://apilayer.com/terms)
- [Privacy Policy](https://apilayer.com/privacy-policy)
- [Support](https://apilayer.com/contact)
- [Contact](https://apilayer.com/contact)
- [Status Page](https://status.apilayer.com/)
- [Blog](https://blog.apilayer.com/)
- [GitHub Organization](https://github.com/westy92)
- [GitHub Repository](https://github.com/westy92/holiday-event-api-js)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [JSON-LD](json-ld/checkiday-national-holiday-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Resources](vocabulary/checkiday-national-holiday-api-vocabulary.yml)
- [Resources](rules/checkiday-rules.yml)
- [Resources](capabilities/holiday-lookup.yaml)
- [Resources](capabilities/event-discovery.yaml)
- [Resources](capabilities/editorial-calendar.yaml)
- [Resources](finops/checkiday-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
