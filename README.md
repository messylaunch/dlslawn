# Davis Lawn Service & Hauling — Website

Conversion-first one-page site. All visuals are hand-built CSS/SVG (no AI images).

- `index.html` — the site (self-contained; `vendor/` holds GSAP/ScrollTrigger locally)
- `BRIEF.md` — the creative brief this was built from + reusable template for future clients + the list of questions to ask Davis to fill the TODOs

## Before launch
Search `index.html` for `TODO` — phone number, service area, city-contract details, reviews, and the GHL form embed slot are all placeholder-marked.

## Run locally
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Deploys as a plain static site (Vercel: framework = Other, no build step).
