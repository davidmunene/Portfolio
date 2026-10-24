# David Munene — Portfolio

A lightweight, responsive personal portfolio built with plain HTML, CSS, and JavaScript. It has no build step or runtime dependencies and is configured for deployment from the repository root on Vercel.

## Run locally

Serve the repository root with any static web server, for example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy

Import the `davidmunene/Portfolio` GitHub repository into Vercel, keep the project root at `/`, and use the Other framework preset with no build command or output directory. The `main` branch is the current repository default. Vercel will serve the static files directly.

## Update content and assets

- Edit section copy and project descriptions in `index.html`.
- Adjust colors, type, and responsive layouts in `styles.css`.
- Update the mobile navigation behavior in `script.js`.
- Replace `David Kings.png` with an updated portrait and keep the hero image path and dimensions in `index.html` in sync; add a CV download only after the current CV is supplied.
- Update verified profile destinations in the `#social` section of `index.html`. Hashnode, X, and Instagram remain pending until their profile URLs are supplied.
- Add verified project repository, course credential, and experience links/details in `index.html` when available.
- Replace the Open Graph image and add a canonical URL and sitemap after the production domain is known.

The three project entries are explicitly labeled as concepts or explorations. Planned features and technical directions are not claims of deployed functionality.