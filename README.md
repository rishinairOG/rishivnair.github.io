# rishivnair.github.io

Personal portfolio website for Rishi V Nair — AI & Operations.

## Stack

- Pure HTML + Tailwind CSS (CDN) — no build step
- Three.js (CDN, ES module) for 3D hero background
- Vanilla JavaScript for theme toggling, mobile menu, scroll highlighting

## Sections

- **Hero** — Animated neural network background, profile portrait, CTAs for MenuMatrix and CV
- **Projects** — MenuMatrix (AI menu analysis dashboard), Resume (PDF)
- **Experience** — Work timeline: Gastronomica ME, Tablez Food Company, Oberoi Hotels (2018–present)
- **Contact** — Phone, WhatsApp, email

## Features

- Dark/light mode with `localStorage` persistence
- 3D animated neural network (Three.js) in hero section — WebGL with graceful fallback
  - ~8% emerald accent nodes matching brand color
  - Mouse parallax on desktop
  - Reduced particle count on mobile
  - Theme-aware colors via MutationObserver
- Mobile hamburger menu
- Scroll-based nav highlighting (IntersectionObserver)
- Entrance animations

## Files

```
index.html      — Single-file site
profile.png     — Hero portrait
gastronomica.png, tablez.png, oberoi.png — Company logos
resume.pdf      — CV download
favicon.svg     — Site icon
CNAME           — Custom domain config
```
