# Steel (steel-dev)

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
