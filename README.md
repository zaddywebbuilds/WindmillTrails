# Windmill Trails — website rebuild

A single-page rebuild of [windmilltrails.com](https://windmilltrails.com) for
**Windmill Trails**, a 140-year-old dairy farm on 63 acres in Tylertown, Mississippi,
offering two private stays and overnight horse lodging.

Built as a pitch concept for the owners (Anna & Wilfred Barry).

## What's here

| Path | Purpose |
|---|---|
| `index.html` | The entire site — markup, CSS and JS in one file, no build step |
| `images-web/` | 58 curated, web-optimised photographs |

## Features

- Full-bleed hero with drifting-light canvas and animated stat counters
- Tabbed **Stays** (Dairy Cottage / Barn Loft) with a keyboard-navigable lightbox
- **Horse Motel** facilities, live rate table and check-in requirements
- **A Day Here** — four tabbed moments from morning to after dark
- Draggable **Before & After** restoration slider
- Booking **popup** with date/unit/horse-count request form and thank-you state
- Scroll-reveal, 3D card tilt, scroll-progress bar, marquee
- Responsive to 390px; honours `prefers-reduced-motion`

## Content

Copy and photography are drawn from the existing windmilltrails.com pages and the
Google Maps business listing. Every image appears exactly once, matched to its section.

## Running it

No build step. Open `index.html`, or serve the folder:

```bash
python -m http.server 8899
```

## Contact

436 Airline Hwy, Tylertown, MS 39667 · (225) 278-8934 · Support@WindMillTrails.com
