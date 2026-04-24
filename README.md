# JBC Homepage Redesign

A multi-page prototype redesign of the [Jennifer Bett Communications](https://www.jenniferbett.com) website — concepted as a design exploration, not an official JBC deliverable.

## View the prototype

Live: **https://bczarny.github.io/jbc-homepage-redesign/**

## Pages

Each page is a standalone single-file HTML document (inline CSS + JS, no build step).

**Primary**

- `index.html` — homepage
- `our-work.html` — featured case studies + filterable case-study grid
- `what-we-do.html` — services, sectors, capabilities
- `why-jbc.html` — the JBC difference (principles, differentiators, Office Hours)
- `the-team.html` — leadership + full roster with headshots
- `the-spin.html` — blog listing with topic filters + Office Hours subscribe

**Detail / templates**

- `olipop-case-study.html` — OLIPOP case study detail page
- `spin-article.html` — representative article template ("The 'Founder-Led Era'")

**Company**

- `join-us.html` — careers / life at JBC
- `contact.html` — new-business inquiry form + office locations (with maps)
- `terms-privacy.html` — terms of service & privacy policy

## Assets

- `jbc-logo-trimmed.png` — dark wordmark (nav, mobile menu)
- `jbc-logo-white.webp` — cream wordmark (footer)
- `jbc-logo.png` / `jbc-logo.svg` — reference wordmark assets
- `observer-power-list-2026.jpg` — team photo from Observer's PR Power List 2026 (hero badge on `index.html`)
- `brand-images/` — reserved for locally hosted brand imagery

All case study thumbnails and brand imagery are loaded from JBC's Squarespace CDN so pages render with real brand visuals.

## Homepage structure

1. **Hero** — positioning, founders tagline, Observer PR Power List 2026 badge (top-right)
2. **Stats strip** — four headline numbers ($1B+, 20B+, $64M+, 80%+)
3. **Pullquote** — JBC's founding premise
4. **Scorecard** — how we measure: Strategic Narrative, Brand Health & Quality, Business Outcomes & Attribution
5. **Case studies** — six tiles in horizontal-split layout: OLIPOP · Midi Health · Reale Actives · Sandbar · Sloomoo · Tecovas
6. **Why JBC** — senior-led, independent, built for what's next
7. **Testimonials** — four client + editor quotes
8. **What We Do** — twelve services, sectors strip, Executive Speaking & Awards feature
9. **The Spin promo** — featured post + five recent posts linking to the blog
10. **Instagram promo** — six latest posts from @jbettcomm
11. **CTA + Footer**

## Design system

Shared across all pages:

- **Palette:** cream (`#FFF6EB`), ink (`#0A0A0A`), accent red (`#D64A1F`), cream-2 (`#F6E8D2`), pale (`#FBF0DE`)
- **Type:** Helvetica Neue (display), Fraunces (serif italic accents), IBM Plex Mono (eyebrows/meta)
- **Grid:** `max-width: 1320px` with `clamp()`-based fluid gutters
- **Components:** sticky nav + scroll shadow, full-screen mobile menu, intersection-observer reveals, horizontal-split case study tiles, 3-column logo-anchored footer with Instagram / TikTok / Facebook / Email socials

Breakpoints: 1100 / 1024 / 900 / 640 / 380 px.

## Editing

Pages are single HTML files — open in any editor, save, refresh. No build step, no dependencies.

## Credits

- Copy and brand visuals are adapted from jenniferbett.com for prototype purposes
- Fonts: Helvetica Neue (display), Fraunces (serif italic accents), IBM Plex Mono (mono)
