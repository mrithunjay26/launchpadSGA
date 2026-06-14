# Launchpad SGA Website

Launchpad SGA is a static multi-page website for a startup growth agency concept. It includes pricing, contact, update, SEO, sitemap, and progressive-web-app metadata, packaged as a lightweight HTML/CSS/JavaScript site that can be deployed without a build step.

For recruiters, this repo is useful as a concise frontend sample: it shows practical static-site delivery, responsive Bootstrap-based layouts, vendor asset management, metadata, and a small public-facing product funnel.

## What it demonstrates

- Multi-page static site architecture with `pricing.html`, `contact.html`, and `updates.html`.
- Bootstrap-based responsive layout and component styling.
- SEO and social metadata for shareable public pages.
- Sitemap, robots file, and web app manifest setup.
- Lightweight deployment model that works on any static host.

## Tech stack

- HTML
- CSS
- JavaScript
- Bootstrap
- AOS animations
- Static PWA metadata

## Run locally

Open `index.html` directly, or serve the directory:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Project structure

- `index.html` - local entry page for the site.
- `pricing.html` - pricing and plan comparison page.
- `contact.html` - contact and inquiry page.
- `updates.html` - updates page.
- `assets/` - stylesheets, JavaScript, fonts, icons, and images.
- `sitemap.xml`, `robots.txt`, `manifest.json` - public web metadata.

## Reviewer notes

This project is intentionally small. The strongest signal is the ability to ship a complete, static marketing site with routing, metadata, assets, and deployment-ready structure rather than only a single HTML mockup.
