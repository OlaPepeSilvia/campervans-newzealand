# Campervans Australia

Static marketing site for Campervans Australia. Plain HTML and CSS, no build step, no dependencies. Deploys as a static site on Replit.

## Pages

| File | Page | Notes |
|------|------|-------|
| `index.html` | Home | Hero, booking bar, van carousel, field notes preview |
| `explore-vans.html` | Explore Vans (product parent) | Filterable van grid |
| `van.html` | Van product page | Single van detail + booking request form |
| `field-notes.html` | Field Notes (blog) | Brisbane to Cairns field guide article |
| `destinations.html` | Destinations | Region grid (placeholder cards, ready to expand) |
| `styles.css` | Shared stylesheet | All page styles live here |
| `script.js` | (inline per page) | Small per-page interactions are inline in each file |

## Running locally

No server needed. Open any `.html` file in a browser. For accurate testing (fonts, relative links) serve the folder:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Deploying on Replit

1. Import this repo into Replit (Import from GitHub).
2. Use Deploy > Static Deployment.
3. Replit serves `index.html` at the root URL.

## Notes for the team

- Fonts (Inter, Archivo Black) load from Google Fonts via the `@import` at the top of `styles.css`. They need internet access to render; they fall back to system fonts otherwise.
- All navigation uses real page links (`href="explore-vans.html"` etc), so every page has its own URL. Good for SEO and sharing.
- Colours are defined once as CSS variables (`--cream`, `--sun`, `--rust`, etc) at the top of `styles.css`. Change them there to restyle site-wide.
- The booking bar, filters, and request form are front-end only right now. They do not submit anywhere yet, that is the next piece of work.
- `destinations.html` and the "Days 4-14" block in `field-notes.html` are template shells ready for real content.

## Docs

Reference documentation lives in `/docs`.
