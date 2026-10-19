<p align="center">
  <img src="https://raw.githubusercontent.com/Omnific-Tech/.github/main/profile/assets/banner.svg" alt="Omnific Tech — Practical software. Thoughtful engineering." width="100%" />
</p>

[Website](https://omnific.dev/) · [Nexus Terminal](https://nexus.omnific.dev/welcome) · [Aeon](https://app.aeon.omnific.dev/) · [Portfolio](https://portfolio.omnific.dev/)

Omnific Tech builds products that turn complex information into practical tools.

Founded by [Jimly Firdaus](https://portfolio.omnific.dev/), Omnific Tech develops software shaped by real engineering and everyday needs. Each product starts with a firsthand problem and is built to help others facing similar challenges.

The focus is on clear information, reliable systems, and products that remain useful in practice.

## Products

### Nexus Terminal

The flagship product: a financial market intelligence platform bringing market data, macroeconomic indicators, regulatory filings, prediction markets, and news into one workspace.

Automated data ingestion, AI research, and API/MCP integrations connect the terminal to a wider research workflow. Built with Go, Python, React, PostgreSQL, and Redis.

[Discover Nexus Terminal](https://nexus.omnific.dev/welcome) · [Open terminal](https://nexus.omnific.dev/) · [Android APK](https://github.com/Omnific-Tech/nexus-android/releases/latest) · [Android source](https://github.com/Omnific-Tech/nexus-android) · [Documentation](https://docs.omnific.dev/)

### Aeon

Earthquake and air quality awareness for Indonesia, powered by BMKG data. Follow recent earthquakes, explore PM2.5 monitoring stations, read official haze updates, and choose the provinces and thresholds that matter to you.

Available on the web and Android, with configurable push notifications.

[Open Aeon](https://app.aeon.omnific.dev/) · [Android APK](https://github.com/Omnific-Tech/aeon-android/releases/latest) · [Android source](https://github.com/Omnific-Tech/aeon-android)

## Development & Open Source

Reusable tools and product-independent infrastructure, built from our production needs. Product Android repositories contain their APK wrappers and release pipelines; the product web applications and backends are maintained separately.

### Herald notification toolkit

| Repository | What it provides |
| --- | --- |
| [herald-oss](https://github.com/Omnific-Tech/herald-oss) | Product-agnostic notification broker: authenticated publishing, routing, retries, and acknowledgements for Android FCM and browser Web Push |
| [herald-android-oss](https://github.com/Omnific-Tech/herald-android-oss) | Reusable Android notification core and Trusted Web Activity template with app-specific identity and branding |
| [herald-web-oss](https://github.com/Omnific-Tech/herald-web-oss) | Browser Web Push client and the page side of the Android subscription bridge |
| [aeon-android](https://github.com/Omnific-Tech/aeon-android) | Aeon's Android app configuration, vendored core, and signed APK distribution |
| [nexus-android](https://github.com/Omnific-Tech/nexus-android) | Nexus Terminal's Android app configuration, vendored core, and signed APK distribution |

Herald handles delivery; each product owns its content, user experience, and notification preferences. Android releases include checksums, signing certificate fingerprints, and dependency notices alongside the APK.

### Developer tools

- [Vesta](https://github.com/Omnific-Tech/vesta): experimental, opt-in keepalives for idle Claude Code and Codex sessions.
- [Go Periodic](https://github.com/Omnific-Tech/go-periodic): restart-safe periodic background tasks for Go.
- [Go API + MCP template](https://github.com/Omnific-Tech/go-api-mcp-template): a reusable API service with authenticated MCP support.
- [React + Vite template](https://github.com/Omnific-Tech/react-vite-template): a starting point for React, TypeScript, and Tailwind applications.

---

**Contact:** [developer@omnific.dev](mailto:developer@omnific.dev)
