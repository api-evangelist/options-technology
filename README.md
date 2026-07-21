# Options Technology (options-technology)

Options Technology (Options IT) is a capital markets managed services and trading infrastructure provider founded in 1993, backed by private equity firm Abry Partners since 2019, serving over 550 firms globally. Its market data business, built on the 2021 acquisition of ACTIV Financial, sells low-latency raw and normalized exchange feeds delivered over colocated multicast and TCP, real-time streaming into AWS, GCP, and Azure, tickerplant snapshot and time-series services, and lossless data capture with raw .pcap files. The commercial relationship is sales-gated and entitlement-managed, but the ACTIV Web One API - a WebSocket plus WebAssembly JavaScript API distributed via npm - has genuinely public developer documentation, tutorials, and an in-browser playground at weboneapi.activfinancial.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/options-technology/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/options-technology/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Real-Time
- Streaming
- Trading Infrastructure
- Exchange Data
- Managed Services
- Low Latency

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### ACTIV Web One API (AtlasFeed)

WebSocket-based (WebAssembly) JavaScript/TypeScript market data API for browser and Node.js, installed as npm package `@activfinancial/one-api` (latest 1.1.4). Supports snapshots, real-time subscriptions, queries, and time-series history across ACTIV's normalized multi-asset feed, with Promises, async/await, and AsyncIterator interfaces. Clients connect with `activOneApi.connect({ host, user, password })` - tutorials document the host `aop-ny4-replay.activfinancial.com` - and credentials are entitlement-managed and provisioned by sales, not self-serve. Documentation, tutorials, examples, and an in-browser playground are public; no OpenAPI or AsyncAPI spec is published.

- **Human URL:** [https://weboneapi.activfinancial.com/](https://weboneapi.activfinancial.com/)
- **Base URL:** `wss://aop-ny4-replay.activfinancial.com`

#### Tags

- Market Data
- WebSocket
- Streaming
- Snapshots
- Time Series

#### Properties

- [Documentation](https://weboneapi.activfinancial.com/documentation/)
- [Getting Started](https://weboneapi.activfinancial.com/tutorials/)
- [Sandbox / Playground](https://weboneapi.activfinancial.com/playground/)
- [SDK (npm @activfinancial/one-api)](https://www.npmjs.com/package/@activfinancial/one-api)
- [Code Repository (examples)](https://github.com/activfinancial/one-api-examples)

## Common Properties

- [Website](https://www.options-it.com/)
- [Portal](https://weboneapi.activfinancial.com/)
- [Documentation](https://weboneapi.activfinancial.com/documentation/)
- [GitHub Organization](https://github.com/activfinancial)
- [LinkedIn](https://www.linkedin.com/company/options-technology)
- [Blog / News](https://www.options-it.com/news/)
- [Privacy Policy](https://www.options-it.com/privacy-statement/)
- [Support (ACTIV)](https://www.options-it.com/activ-support/)
- [Status Page](https://status.options-it.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
