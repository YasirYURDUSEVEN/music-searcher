# Iz Ara

Mobile-first static music and sheet-score search app. No build step is required.

## Run locally

Serve this folder over HTTP, for example with `python -m http.server 8765`, then open `http://localhost:8765`.

## Publish on GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the static site on pushes to `main`. In repository settings, select **Settings > Pages > GitHub Actions** as the deployment source.

The site is installable as a PWA on supported mobile browsers. Search requests go to the relevant public archives; the TXT list stays in the browser.
