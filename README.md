# Steel (steel-dev)

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

Steel is the open-source browser API for AI agents and apps. The Steel Cloud REST API (https://api.steel.dev/v1) launches and manages cloud browser sessions, runs stateless quick actions (scrape, screenshot, pdf, search), and exposes a live session viewer, while long-running automation connects to a per-session Chrome DevTools Protocol (CDP) WebSocket driven with Playwright, Puppeteer, or Selenium. The same surface ships self-hosted under Apache-2.0 as steel-browser.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/steel-dev/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/steel-dev/refs/heads/main/apis.yml)

## Tags

- Browser
- Web Automation
- Scraping
- AI Agents
- Open Source

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Steel Sessions API

Launch, inspect, release, and live-view stateful cloud browser sessions with proxy, fingerprint, dimensions, timezone, ad-blocking, and bandwidth options, plus session context capture and per-session file management.

- **Human URL:** [https://docs.steel.dev/overview/sessions-api](https://docs.steel.dev/overview/sessions-api)
- **Base URL:** `https://api.steel.dev/v1`

#### Tags

- Sessions
- Cloud Browser
- Live Viewer

#### Properties

- [Documentation](https://docs.steel.dev/overview/sessions-api)
- [API Reference](https://docs.steel.dev/api-reference)
- [OpenAPI](openapi/steel-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/steel-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/steel-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Steel Scrape API

Stateless one-off scrape that returns clean page content in html, readability, cleaned_html, and markdown formats, with page metadata, links, and optional inline screenshot and PDF. Includes a search action for query-to-URL resolution.

- **Human URL:** [https://docs.steel.dev/overview/quick-actions-api](https://docs.steel.dev/overview/quick-actions-api)
- **Base URL:** `https://api.steel.dev/v1`

#### Tags

- Scrape
- Extraction
- Markdown

#### Properties

- [Documentation](https://docs.steel.dev/overview/quick-actions-api)
- [API Reference](https://docs.steel.dev/api-reference)
- [OpenAPI](openapi/steel-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/steel-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/steel-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Steel Screenshot & PDF API

Render any URL or the current session page to a PNG screenshot (with full-page option) or a PDF document, with proxy and render-delay controls.

- **Human URL:** [https://docs.steel.dev/overview/quick-actions-api](https://docs.steel.dev/overview/quick-actions-api)
- **Base URL:** `https://api.steel.dev/v1`

#### Tags

- Screenshot
- PDF
- Rendering

#### Properties

- [Documentation](https://docs.steel.dev/overview/quick-actions-api)
- [API Reference](https://docs.steel.dev/api-reference)
- [OpenAPI](openapi/steel-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/steel-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/steel-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Steel CDP / Browser Connect API

Per-session Chrome DevTools Protocol (CDP) WebSocket surfaced as the session `websocketUrl`, used with Playwright connect_over_cdp, Puppeteer connect, or Selenium for full programmatic control of the cloud Chrome instance.

- **Human URL:** [https://docs.steel.dev/overview/guides/connect-with-playwright](https://docs.steel.dev/overview/guides/connect-with-playwright)
- **Base URL:** `https://api.steel.dev/v1`

#### Tags

- CDP
- WebSocket
- Playwright

#### Properties

- [Documentation](https://docs.steel.dev/overview/guides/connect-with-playwright)
- [OpenAPI](openapi/steel-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Review](review.yml)

## Common Properties

- [GitHub Organization](https://github.com/steel-dev)
- [LinkedIn](https://www.linkedin.com/company/steel-dev)
- [Website](https://steel.dev)
- [Documentation](https://docs.steel.dev)
- [Plans](plans/steel-dev-plans-pricing.yml)
- [Rate Limits](rate-limits/steel-dev-rate-limits.yml)
- [Fin Ops](finops/steel-dev-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
