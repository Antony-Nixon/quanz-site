# QuanZ — The Elegance of Hydration

> **A quiet luxury landing page for a modern hydration brand. ✦**

A responsive, luxury-style static website concept for QuanZ, presenting a premium hydration brand through editorial typography, product collections, visual storytelling, and contact-focused calls to action.

[![Static website](https://img.shields.io/badge/site-static%20website-121212)](#run-locally)
[![Responsive design](https://img.shields.io/badge/design-responsive-d4af37)](#experience)
[![HTML and CSS](https://img.shields.io/badge/built%20with-HTML%20%2B%20CSS-e34f26)](https://developer.mozilla.org/en-US/docs/Web/HTML)

## Design story

The page is built around a simple visual idea:

```text
Water → Form → Atmosphere
```

Water provides the subject, product form gives the page structure, and atmosphere creates the premium brand feeling. The result is intentionally closer to an editorial campaign page than a conventional product catalog.

## Experience

The site is designed as a single-page brand experience with:

- Full-screen hero section
- Editorial “about” content
- Product and collection showcases
- Responsive navigation
- Luxury visual language using serif headings, muted neutrals, and gold accents
- Image-led storytelling
- Contact and call-to-action sections
- Responsive behavior for smaller screens

## Run locally

This is a static website and does not require a build system.

With Python:

```bash
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in a browser.

You can also deploy the repository to any static hosting provider such as GitHub Pages, Cloudflare Pages, or Netlify.

## Project structure

```text
index.html       Main page markup and inline presentation logic
favicon.png      Browser icon
*.png / *.jpg    Product, brand, and hero imagery
images.txt       Image-related project note
```

The current page keeps its styling and interaction logic largely inside `index.html`. A future cleanup could separate these concerns into `styles.css` and `script.js`.

## Design system

The visual direction uses:

- Libre Baskerville for editorial headings
- Montserrat for interface and supporting text
- Dark charcoal, warm off-white, white, and gold accents
- Soft rounded corners and spacious sections
- Responsive grids that collapse for mobile layouts

The page currently loads Google Fonts and Font Awesome from external CDNs, so those resources require network access in production.

## Content and assets

The repository contains a collection of brand and product images used by the landing page. Before public commercial use, confirm that all logos, product images, photography, and third-party assets are licensed for the intended audience and deployment.

## Improvement roadmap

- Move inline CSS and JavaScript into dedicated files
- Add an accessible mobile navigation menu
- Audit heading hierarchy, contrast, alt text, and keyboard navigation
- Optimize large raster images for faster loading
- Add Open Graph and social preview metadata
- Add a contact form backed by a secure service
- Add a deployment URL and screenshot to this README
- Add a license and explicit ownership note for the visual assets

## Status

This repository is a static website/brand concept and is not an e-commerce backend. Product claims, pricing, checkout, inventory, and form delivery are not implemented here.

## Author

Built and maintained by Antony Nixon.
