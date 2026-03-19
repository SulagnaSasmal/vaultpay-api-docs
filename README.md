# VaultPay API Documentation v2.4

Enterprise-grade REST API reference for VaultPay, a fictional payment processing platform. Built as a portfolio demonstration of production-quality API documentation using a single self-contained HTML file.

## Live Demo

Hosted on GitHub Pages: `sulagnasasmal.github.io/vaultpay-api-docs/`

## What's Documented

| Section | Content |
|---------|---------|
| Overview | Platform capabilities, rate limits, versioning policy |
| Authentication | API key authentication, OAuth 2.0, HMAC request signing |
| SDKs & Libraries | Node.js, Python, Java, Go client library references |
| Payments | Create, retrieve, list, and cancel payment requests |
| Transfers | Bank transfers, ACH, Fedwire, SWIFT, RTP / FedNow |
| Accounts | Account management, balance, and transaction history |
| Webhooks | Event types, delivery guarantees, signature verification |
| Error Handling | HTTP status codes, error response schema, retry guidance |

## Tech Stack

- Single HTML file (inline CSS + JS, zero external dependencies)
- IBM Plex Mono, DM Sans, Fraunces (Google Fonts)
- IntersectionObserver-based active nav highlighting
- Sandbox / Live environment toggle
- Dark and light mode support

## Dark / Light Mode

The page supports dark and light themes via a toggle button (◐ / ☀) in the header. The selected theme persists in `localStorage`. System `prefers-color-scheme` is respected on first visit.

## Status

**Phase 1: API Reference Documentation (Complete)**

| Area | Status |
|------|--------|
| Overview & architecture | Complete |
| Authentication (API key + OAuth 2.0 + HMAC) | Complete |
| SDK & library listing | Complete |
| Payments API endpoints | Complete |
| Transfers (ACH, Fedwire, SWIFT, RTP / FedNow) | Complete |
| Accounts API | Complete |
| Webhooks | Complete |
| Error handling & retry guidance | Complete |
| Dark / light theme support | Complete |
| README | Complete |

## Roadmap / Future Enhancements

- Split into multi-page HTML site with per-section deep links
- Live "Try It" console (sandbox API calls from the browser)
- OpenAPI 3.x spec export (`vaultpay-openapi.yaml`)
- Changelog page (`changelog.html`)
- SDK quickstart guides per language

## Usage

Open `index.html` in any browser, or deploy to GitHub Pages. No build step or server required.
