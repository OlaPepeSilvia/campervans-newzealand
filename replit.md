# Campervans Australia

Static marketing site for Campervans Australia. Plain HTML and CSS — no build step, no dependencies.

## Stack

- Plain HTML, CSS, and inline JavaScript
- No framework, no bundler, no build step

## Pages

| File | Page |
|------|------|
| `index.html` | Home — hero, booking bar, van carousel, field notes preview |
| `explore-vans.html` | Explore Vans — filterable van grid |
| `van.html` | Van detail — single van + booking request form |
| `field-notes.html` | Field Notes — Brisbane to Cairns field guide |
| `destinations.html` | Destinations — region grid (placeholder cards) |
| `styles.css` | Shared stylesheet (all styles, CSS variables) |

## Running on Replit

The **Start application** workflow runs `python3 -m http.server 5000` and serves the site at port 5000. Start it from the Workflows panel.

## Notes

- Fonts (Inter, Archivo Black) load from Google Fonts — need internet access; fall back to system fonts otherwise.
- Colours are CSS variables at the top of `styles.css` (`--cream`, `--sun`, `--rust`, etc) — change there to restyle site-wide.
- The booking bar, van filters, and request form are front-end only (no backend yet).
- `destinations.html` and "Days 4–14" in `field-notes.html` are placeholder shells ready for real content.
- Deploy as a **Static Deployment** on Replit.

## User preferences

<!-- Add any preferences here -->
