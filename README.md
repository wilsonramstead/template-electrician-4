# Electrician Website Template (Design 4)

An electrician website template by **Wilson Innovations** — a single-page marketing site for residential and emergency electrical contractors.

- **Build:** self-contained `index.html` — inline CSS + minimal JS, works from `file://` and with JS disabled.
- **Status:** ships with a `noindex` robots meta (remove it when a client site goes live).
- **Fictional placeholder brand:** "Copperline Electric Co." serving the Tampa Bay Area. Swap the business name, phone, service area, reviews, and photos for the real client before launch.

## Sections

- Sticky white header with brand mark and click-to-call button
- Full-bleed photo hero with electric-blue overlay, headline, call/text CTAs and a live "Open 24 Hours" badge
- Trust bar (star rating, 24-hour availability, fair pricing, owner-run & local)
- Services grid (panel replacement & upgrades, transfer switch & generator hookups, lighting installation, emergency electrical, residential wiring & repairs)
- "Always on" 24/7 feature band explaining after-hours response
- Full-width pull-quote divider over a photo background
- Six-card review grid, with the last card as a rating call-to-action panel
- Work strip — three project photos with a "placeholder imagery" note
- Service area, hours table (today's row auto-highlighted) and area chips
- Final call-to-action band over a photo background, then the footer

## Design

- **Palette:** electric blue (`#0b63ff` / `#3a86ff` / deep `#0842b0`) + high-visibility lime accent (`#d3ff2e` / `#e4ff6b`) over charcoal (`#1b1f29`) dark bands and white/mist (`#f5f7fb`) light sections.
- **Fonts:** Exo (technical display) + Host Grotesk (body).
- **Motifs:** lightning-bolt logo mark, pulsing "open now" dot, lime-gradient primary buttons with glow shadow, layered blue photo overlays.
- IntersectionObserver fade-ins respect reduced motion. JS highlights today's row in the hours table. Electrician JSON-LD with `areaServed` (no street address). AA contrast, focus states, lazy-loaded below-fold images.

## Customizing for a client

1. Replace brand name, phone (`tel:` / `sms:` links), and service area.
2. Rewrite the placeholder reviews with the client's real testimonials.
3. Swap the placeholder Unsplash imagery for the electrician's own project photos.
4. Update the JSON-LD business data and Open Graph / social tags.
5. Adjust the hours table if the client isn't a 24-hour operation.
6. Remove the `noindex` robots meta + comment when going live.

Website by Wilson Innovations — https://wilsoninnovations.net
