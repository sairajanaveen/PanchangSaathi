# Saathi Points — site-wide preview

Two previews are available on this isolated branch:

## 1. Homepage integration preview (recommended)

This shows Saathi Points added to the current PanchangSaathi homepage structure, rather than as a separate rewards website.

Browser preview:
https://raw.githack.com/sairajanaveen/PanchangSaathi/preview/gamification-sitewide/preview/gamification/homepage-integration.html

Source:
https://github.com/sairajanaveen/PanchangSaathi/blob/preview/gamification-sitewide/preview/gamification/homepage-integration.html

The existing homepage flow is retained: Explore/header, Ganesha welcome panel, city/date selector, daily Panchang summary, tool links, primary navigation and the "Your day at a glance" section. The proposed additions are a compact Saathi Points/streak chip in the header and a contextual Saathi journey card beneath the daily summary.

## 2. Feature screens preview

https://raw.githack.com/sairajanaveen/PanchangSaathi/preview/gamification-sitewide/preview/gamification/index.html

Source:
https://github.com/sairajanaveen/PanchangSaathi/blob/preview/gamification-sitewide/preview/gamification/index.html

## Demo behaviour

- Starting demo balance: 120 points
- Daily check-in: +10 points, once per preview session
- Correct Panchang quiz answer: +20 points, once per preview session
- Shared balance and streak within each preview
- Reset demo action on the feature screens

## Important boundaries

- UI prototypes only; no live Panchang calculations, authentication, API, database, payments, or production routes are connected.
- Displayed Panchang and Rahu Kaal values are illustrative copies for layout context; they are not live-calculated by this prototype. The displayed times are drawn from the current homepage at the time the prototype was prepared and must not be relied on as refreshed timings.
- Points are demo-only and have no monetary value.
- Future affiliate discounts and astrology reports are display-only concepts; redemption is disabled.
- State is held in page memory and resets on refresh. No account or persistent browser storage is used.
- Browser preview is served by a third-party raw-file service for testing only; it is not a permanent production host.
- This work exists on the preview/gamification-sitewide branch. It does not change the production website or the private application source.
