# Roadmap

> **Last updated:** 2026-08-25 · maintained alongside [GitHub milestones](https://github.com/mariusnop/MagicProphet.com/milestones) · versioning follows [SemVer](https://semver.org/)

MagicProphet is an AI-powered Magic: The Gathering companion: card search in plain language, collection tracking, price forecasts, camera card scanning, and combo discovery for brand-new sets. This page reflects what's shipped, what's next, and what's planned.

Everything here links to a real GitHub issue or milestone. Nothing on this page is aspirational marketing. Feedback shapes the list directly: issues submitted from inside the app land in [this repository](https://github.com/mariusnop/MagicProphet.com/issues) and influence prioritization.

## 🚀 v1.0.0 public launch · 2026-08-30

The first public release, on web, iOS and Android. Everything below is already running in the app and becomes available to everyone at launch.

Milestone: [v1.0 - Launch](https://github.com/mariusnop/MagicProphet.com/milestone/1)

- [AI-powered card search](https://github.com/mariusnop/MagicProphet.com/issues/2): describe what you want in plain language, get ranked matches across 30,000+ cards
- [Watchlists with price alerts](https://github.com/mariusnop/MagicProphet.com/issues/3): keep an eye on cards and get notified when a price moves
- [Collection management](https://github.com/mariusnop/MagicProphet.com/issues/4): track what you own, in which print and condition, and what it is worth
- [Price comparison across Cardmarket and TCGplayer](https://github.com/mariusnop/MagicProphet.com/issues/5)
- [Card scanner](https://github.com/mariusnop/MagicProphet.com/issues/6): point your camera at a card and it lands in your collection
- [Better search results for complex queries](https://github.com/mariusnop/MagicProphet.com/issues/8)
- [Similar card suggestions](https://github.com/mariusnop/MagicProphet.com/issues/9) on every card page
- [Combo Radar](https://github.com/mariusnop/MagicProphet.com/issues/14): possible combos in a brand-new set, before anyone has played with the cards

Before this, MagicProphet ran as an invite-only private beta from 2026-04-14, most recently on version `v1.0.7`.

## 🔧 v1.1 - Post-launch improvements

Shaped by what early users run into first. No fixed date yet, and the order may change.

Milestone: [v1.1 - Post-launch improvements](https://github.com/mariusnop/MagicProphet.com/milestone/2)

- [EDH deck builder](https://github.com/mariusnop/MagicProphet.com/issues/10): pick a commander and a play style, get a full 100-card list
- [Market overview and trending page](https://github.com/mariusnop/MagicProphet.com/issues/11): top movers and price trends in one place instead of card by card
- [Search: query classes that still return weak results](https://github.com/mariusnop/MagicProphet.com/issues/15)

## 📦 Backlog

Planned but not scheduled. Moves into a release once prioritized, and upvotes influence the ordering.

Milestone: [Backlog](https://github.com/mariusnop/MagicProphet.com/milestone/3)

- [Improved price forecast with machine learning](https://github.com/mariusnop/MagicProphet.com/issues/7)

## 🚫 Out of scope (for now)

Things we have intentionally chosen **not** to build, so expectations stay grounded:

- Trading or marketplace transactions. MagicProphet helps you find and price cards, but never handles purchases. Buy on Cardmarket or TCGplayer, we link you there.
- Tournament organizer and pairings tooling, outside our focus on collectors and deck builders.
- Card grading or authentication. We don't replace PSA / BGS workflows.
- Social features (forums, friend feeds, comments), not planned for the first year.

If your idea fits one of these and you have a strong case, open an issue anyway and tag it `feature-request`. We revisit this list periodically.

## 🏷️ Versioning

We follow [Semantic Versioning](https://semver.org/).

- `v1.0.0-beta.X` and `v1.0.X`: private beta builds ahead of the public launch
- `v1.0.0`: first public release on web, iOS and Android, 2026-08-30
- `v1.Y.Z`: incremental public releases after that

When a feature goes live, its issue is closed with a comment naming the version it shipped in.

## 💬 Feedback

Use the in-app feedback button to report a bug or request a feature. It opens an issue here automatically with the right labels. Or open an [issue directly](https://github.com/mariusnop/MagicProphet.com/issues/new/choose).

Lifecycle labels on this board:

- `accepted`: confirmed and on the roadmap
- `in-progress`: actively being worked on
- `shipping-soon`: in testing, lands in the next release
- (closed): live in the app, the closing comment names the version
