# karolis.com

Personal portfolio site for Karolis Zaksauskas — Front-End Developer based in Aberdeen, Scotland.

## Tech Stack

- **Tailwind CSS** via CDN
- **Vanilla JavaScript** — no frameworks, no build step
- **Inter + JetBrains Mono** — Google Fonts

## Features

- Letter-by-letter name reveal (Splitting.js-inspired)
- Rotating code window with syntax-highlighted snippets (Twig, GSAP, CSS, Alpine.js)
- 3D card tilt with cursor-tracking spotlight
- Word-by-word heading reveals on scroll
- CountUp number animations
- Staggered skill tag reveals
- Active navigation highlighting via IntersectionObserver
- Aurora gradient + dot grid hero background
- Responsive with mobile menu
- Full favicon set, OG tags, Twitter card, JSON-LD schema

## File Structure

```
karolis.com/
├── index.html
├── karolis.jpg
├── favicon.svg
├── favicon.ico
├── favicon-96x96.png
├── apple-touch-icon.png
├── web-app-manifest-192x192.png
├── web-app-manifest-512x512.png
├── site.webmanifest
├── robots.txt
└── sitemap.xml
```

## Deploy

Static site — no build step required. Drop it on Netlify, Vercel, Cloudflare Pages, or GitHub Pages.

## Performance

Total site weight: ~136KB. Single HTML file, one optimised image, zero dependencies.
