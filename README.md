# David Munene Njuguna — Portfolio

Live at **https://davidmunene.vercel.app/**

A static, responsive portfolio built with plain HTML, CSS and JavaScript. No build step and no dependencies.

## Structure
```
index.html     Page content
styles.css     Styles (theme colours are CSS variables at the top)
script.js      Mobile menu, footer year, scroll-reveal animation
404.html       Not-found page
assets/        Optimised photos (.webp with .jpg fallback)
favicon.svg    "DM" monogram icon
vercel.json    Clean URLs and security headers
robots.txt, sitemap.xml
```

## Run locally
The page uses root-relative paths (`/styles.css`), so serve it rather than opening the file directly:
```sh
python3 -m http.server 8000
```
Then open http://localhost:8000.

## Deploy
Vercel deploys automatically on every push to `main` (project root `/`, "Other" preset, no build command).

## Updating content
- Text lives in `index.html`; each section is marked with a comment.
- To add a photo, export a `.jpg` (max ~900px wide) and a `.webp` into `assets/` and use a `<picture>` element like the existing ones.
