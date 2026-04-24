# Roadmap

> **Last updated:** 2026-04-24 · maintained alongside [GitHub milestones](https://github.com/mariusnop/MagicProphet.com/milestones) · versioning follows [SemVer](https://semver.org/)

MagicProphet is an AI-powered Magic: The Gathering platform — smart card search, collection tracking, EDH deck building, price forecasting, and camera-based card scanning. This page reflects what's shipped, what's next, and what's planned.

Everything here links to real GitHub issues and milestones — nothing is aspirational marketing. Feedback shapes this list directly: issues submitted from inside the app land in [this repository](https://github.com/mariusnop/MagicProphet.com/issues) and influence prioritization.

## ✅ Live in v1.0.0-beta.1 · private beta since 2026-04-14

Available to invited beta users. Release tag: [`v1.0.0-beta.1`](https://github.com/mariusnop/MagicProphet-v2/releases/tag/v1.0.0-beta.1).

- AI-powered card search — [#2](https://github.com/mariusnop/MagicProphet.com/issues/2)
- Watchlists with price alerts — [#3](https://github.com/mariusnop/MagicProphet.com/issues/3)
- Collection management — [#4](https://github.com/mariusnop/MagicProphet.com/issues/4)
- Price comparison (Cardmarket & TCGplayer) — [#5](https://github.com/mariusnop/MagicProphet.com/issues/5)

## 🚧 In development — v1.0.0 public launch · target 2026-05-01

Shipping on web, iOS App Store, and Google Play as the first public release.

Milestone: [v1.0 - Launch](https://github.com/mariusnop/MagicProphet.com/milestone/1)

- Card scanner — snap a photo, instantly identify — [#6](https://github.com/mariusnop/MagicProphet.com/issues/6)

**Finalizing before launch** (tracked on the internal engineering board): final UI polish, search quality decision, mobile build + store submission, production deployment gate (custom domain + image CDN), and end-to-end QA on real devices. Already-live features (search, watchlists, collection, price comparison) ship in this release with polish and final testing.

## 🔧 v1.1 — Post-launch improvements · target 2026-06-15

Quality work shaped by early-user feedback — search polish, and the long-awaited deck builder.

Milestone: [v1.1 - Post-launch improvements](https://github.com/mariusnop/MagicProphet.com/milestone/2)

- Better search results for complex queries — [#8](https://github.com/mariusnop/MagicProphet.com/issues/8)
- Similar card suggestions — [#9](https://github.com/mariusnop/MagicProphet.com/issues/9)
- EDH deck builder — [#10](https://github.com/mariusnop/MagicProphet.com/issues/10)

## 📦 Backlog

Planned but not scheduled. Moved into a release once prioritized — feedback and upvotes influence ordering.

Milestone: [Backlog](https://github.com/mariusnop/MagicProphet.com/milestone/3)

- Improved price forecast with machine learning — [#7](https://github.com/mariusnop/MagicProphet.com/issues/7)
- Market overview / trending page — [#11](https://github.com/mariusnop/MagicProphet.com/issues/11)

## 🚫 Out of scope (for now)

Things we have intentionally chosen **not** to build, so expectations stay grounded:

- Trading or marketplace transactions — MagicProphet helps you find and price cards, but never handles purchases. Buy on Cardmarket or TCGplayer; we link you there.
- Tournament organizer / pairings tooling — outside our focus on collectors and deck builders.
- Card grading or authentication — we don't replace PSA / BGS workflows.
- Social features (forums, friend feeds, comments) — not planned for the first year.

If your idea fits one of these and you have a strong case, open an issue anyway and tag it with `feature-request` — we revisit this list periodically.

## 🏷️ Versioning

We follow [Semantic Versioning](https://semver.org/). Current release tags are published on the private code repo:

- `v1.0.0-beta.X` — private beta releases ahead of public launch
- `v1.0.0` — first public release (web + iOS + Android), target 2026-05-01
- `v1.Y.Z` — incremental public releases

All shipped feature announcements on this repo reference the version they went live in.

## 💬 Feedback

Use the in-app feedback button to report a bug or request a feature — it opens an issue here automatically with the right labels. Or open an [issue directly](https://github.com/mariusnop/MagicProphet.com/issues/new/choose).

Lifecycle labels on this board:

- `accepted` — confirmed and on the roadmap
- `in-progress` — actively being worked on
- `shipping-soon` — in testing, next release
- (closed) — live in a specific version (see the comment on each closed issue)
