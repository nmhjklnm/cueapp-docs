# cueapp-docs

This repo is the public landing/docs site for cueapp.

- Static site: `site/`
- Deployment (GitHub Pages via `gh-pages` branch): `.github/workflows/pages.yml`

If the main cueapp repo is private, the landing page cannot fetch release info from it.
In that case, publish binaries via a separate public releases repo and update the `owner/repo` in `site/index.html`.
