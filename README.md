# karolis.uk

Personal portfolio site for Karolis Zaksauskas, a front-end developer based in Aberdeen, Scotland.

## Tech Stack

- Tailwind CSS via CDN
- Vanilla JavaScript with no build step
- Inter and JetBrains Mono via Google Fonts

## Features

- Letter-by-letter hero name reveal
- Rotating code window with syntax-highlighted snippets
- 3D project card tilt with spotlight effect
- Word-by-word heading reveals on scroll
- Count-up stats and staggered skill tag reveals
- Active navigation highlighting with IntersectionObserver
- Responsive mobile menu
- SEO metadata, favicons, sitemap, and structured data

## Files

- `index.html` contains the full site
- `karolis.jpg` is the profile image
- `site.webmanifest`, `robots.txt`, `sitemap.xml`, and `CNAME` support deployment and SEO
- favicon and manifest PNG/SVG assets support browser and device icons

## Deployment

This is a static site and can be deployed directly from the repository root with GitHub Pages.

For `karolis.uk` on GitHub Pages:

- Keep `CNAME` set to `karolis.uk`
- Point the apex domain at GitHub Pages A records
- Point `www` to `Karolis-Zak.github.io`
- Enable GitHub Pages for the repository and then enable HTTPS
