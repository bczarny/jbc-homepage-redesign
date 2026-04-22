# JBC Homepage Redesign

A multi-page prototype redesign of the [Jennifer Bett Communications](https://www.jenniferbett.com) website — concepted as a design exploration, not an official JBC deliverable.

## View the prototype

Live: **https://bczarny.github.io/jbc-homepage-redesign/**

## What's in here

Each page is a standalone single-file HTML document (inline CSS + JS, no build step).

- `index.html` — homepage (duplicated as `jbc-homepage-redesign.html` for compatibility)
- `our-work.html` — client roster + case study index
- `olipop-case-study.html` — OLIPOP case study detail page
- `what-we-do.html` — services, sectors, capabilities
- `why-jbc.html` — the JBC difference (principles, differentiators, Office Hours)
- `the-team.html` — leadership + full roster with headshots
- `the-spin.html` — blog listing with topic filters + Office Hours subscribe
- `spin-article.html` — representative article template ("The 'Founder-Led Era'")
- `jbc-logo-trimmed.png` / `jbc-logo.png` / `jbc-logo.svg` — JBC wordmarks
- `brand-images/` — imagery used on case study tiles

## Homepage structure

1. **Hero** — positioning, founders, tagline
2. **Stats strip** — headline numbers
3. **Our Work** — six case study tiles (OLIPOP, Parachute, theSkimm, Sloomoo Institute, Grove Collaborative, FASHIONPHILE)
4. **Why JBC** — senior-led, independent, accountable
5. **Testimonials** — client and editor quotes
6. **What We Do** — twelve services, sectors strip, Executive Speaking & Awards feature
7. **CTA + Footer**

Imagery is pulled from JBC's Squarespace CDN so pages render with real brand visuals.

## Design system

Shared across all pages:

- **Palette:** cream (`#FFF6EB`), ink (`#0A0A0A`), accent red (`#D64A1F`), cream-2 (`#F6E8D2`)
- **Type:** Helvetica Neue (display), Fraunces (serif italic accents), IBM Plex Mono (eyebrows/meta)
- **Grid:** `max-width: 1320px` with `clamp()`-based fluid gutters
- **Components:** sticky nav + scroll shadow, full-screen mobile menu, intersection-observer reveals, dark Office Hours spotlight, cream-2 pull-quote band

Breakpoints: 1100 / 1024 / 640 / 380 px.

## Editing

Pages are single HTML files — open in any editor, save, refresh. No build step, no dependencies.

## Credits

- Copy and brand visuals are adapted from jenniferbett.com for prototype purposes
- Fonts: Helvetica Neue (display), Fraunces (serif italic accents), IBM Plex Mono (mono)
