# LIQAA Public Roadmap

> What we're building, in priority order. Updated quarterly. PRs welcome to suggest features — open an issue on the [main SDK repo](https://github.com/hartemyaakoub/liqaa-js/issues).

This roadmap is **directional, not contractual**. Dates slip. Features may be re-scoped or cut. We share it because it's useful for partners planning integrations.

Last updated: **2026-05-03**

---

## Now — Q2 2026

### Shipping or shipped this quarter

- **Polyglot SDKs** — PHP, Python, Go (in addition to JS / React)
- **OpenAPI 3.1 spec** published as standalone repo
- **MCP server** — `@liqaa/mcp` for AI-agent integration
- **Public changelog** repo with RSS-friendly releases
- **Recording API GA** — currently beta, full launch by end of Q2
- **Status page on dedicated subdomain** (`status.liqaa.io`)
- **`security.txt`** + bug bounty program (via [HackerOne](https://hackerone.com))

## Next — Q3 2026

### High-confidence shipments

- **Live transcripts (GA)** — Whisper-class on-device or via partner; Pro+
- **Real-time translation** — caption translation across English / Arabic / French
- **Recording bucket flexibility** — bring-your-own S3-compatible (R2, Wasabi, Backblaze)
- **Vue 3 / Svelte / Solid adapters** — same DX as React
- **Background blur + virtual backgrounds** via WebRTC Insertable Streams
- **Multi-currency pricing** — auto-detect, settle in DZD / EUR / GBP / USD
- **Mobile SDKs** (native) — iOS (Swift Package), Android (Kotlin)
- **CLI** — `liqaa rooms list`, `liqaa logs tail`, etc.
- **Console v2** — usage analytics, retention cohorts, plan usage forecasts

## Later — Q4 2026

### Intent, not commitment

- **Self-hosted edition** — Helm chart for on-prem (Enterprise tier)
- **End-to-end encrypted application data** with customer-managed keys
- **SOC 2 Type II** audit completion
- **HIPAA BAA** template for telehealth partners
- **GDPR / DPIA** templates and EU residency option
- **Live polls + Q&A** — for webinars and town-halls
- **In-call AI** — note-taker, action items, smart summaries (opt-in)
- **WebHooks v2** — gRPC-streaming alternative to HTTP for high-fanout

## Horizon — 2027

### Where we're heading

- **Federated identity** — SAML / SCIM for Enterprise
- **Edge regions** — North America, South Asia (currently EU + MENA)
- **WebRTC over QUIC** — when browser support reaches viable threshold
- **Liqaa for hardware** — embedded devkit for kiosk / appliance deployments
- **Open call quality benchmark** — public dashboard comparing latency vs Daily / Twilio / Zoom

---

## Voting on what's next

Want to push something up the priority list?

1. **Open an issue** on [hartemyaakoub/liqaa-js](https://github.com/hartemyaakoub/liqaa-js/issues) with the `roadmap` label.
2. **Upvote** existing issues with — we look at top-voted weekly.
3. **Email** [partners@tkawen.com](mailto:partners@tkawen.com) for enterprise-blocker requests with concrete contract value attached.

## Out of scope

We will **not** build:

- General-purpose meeting product competing with Zoom / Google Meet (we're API-only)
- Phone calling / SIP trunking beyond what `data-room` already does
- Voicemail, IVR, or full PBX features (use Twilio + LIQAA)
- A standalone AI assistant unrelated to calls

This focus is the point. We're a video infrastructure layer, not a meeting app.

## License

[CC0 1.0](./LICENSE) — public domain. Adapt for your own roadmap freely.
