# Vesper — prayer app website

Static marketing site for Vesper, an app that composes a prayer from a short prompt.

## Files
- `index.html` — the landing page (hero with prompt/prayer demo, how it works, traditions, examples, features, CTA)
- `styles.css` — all styles; light and dark themes via CSS tokens
- `assets/` — images and icons (empty for now)
- `v2/` — second version: aggressive marketing variant with pricing, subscriptions, and payment options (`v2/index.html`, `v2/styles.css`)

## Run locally
Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

Then visit http://localhost:8000 (quiet version) or http://localhost:8000/v2/ (marketing version).

## Live
- https://andykwiat.github.io/vesper-site/ — quiet version
- https://andykwiat.github.io/vesper-site/v2/ — marketing version

## Status
Static HTML only. The prompt box and Compose button are a mock-up; no backend yet.
