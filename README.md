# Bright Bee Cleaning — Website

Production landing page for **Bright Bee Cleaning Ltd** — the dependable cleaning partner for property managers, landlords, housing providers, and serviced accommodation operators across **Manchester & the North West of England**.

🔗 **Live site:** https://sheedosa.github.io/Bright_Bee_Website/

## Tech

A single, dependency-free **static site** — plain semantic HTML, CSS, and a small amount of vanilla JavaScript. No build step, no frameworks. Deployed via **GitHub Pages**.

## Structure

```
index.html              Main landing page
404.html                Branded not-found page
robots.txt              Crawler directives
sitemap.xml             Sitemap for search engines
.nojekyll               Serve files as-is (no Jekyll processing)
assets/
  brightbee-logo-cropped.png   Header logo
  hero.jpg                     Hero background
  property-managers.jpg        "For Property Managers" photo
  og-image.jpg                 Social share image
  favicon-16.png / favicon-32.png / apple-touch-icon.png
  hex-gold.svg / hex-light.svg Decorative honeycomb patterns
```

## Features

- Fully responsive (desktop → mobile with hamburger menu)
- Reveal-on-scroll animations (respects `prefers-reduced-motion`)
- SEO: meta description, Open Graph / Twitter cards, canonical URL, `CleaningService` JSON-LD structured data
- Accessibility: skip link, keyboard focus states, alt text, ARIA labels
- Click-to-call, WhatsApp, and email contact actions throughout

## Editing content

All content lives in `index.html`. Key business details to update if they change:

- **Phone:** `07448 946475` (`tel:+447448946475`)
- **WhatsApp:** `https://wa.me/447448946475`
- **Email:** `info@brightbeecleaningltd.co.uk`

## Deploying updates

Commit and push to `main`; GitHub Pages rebuilds automatically within a minute or two.

---

© 2026 Bright Bee Cleaning Ltd.
