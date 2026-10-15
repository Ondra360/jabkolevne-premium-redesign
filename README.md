# JabkoLevně — premium redesign

Responsive, buildless HTML prototype of a premium e-commerce redesign in Czech. It is designed for desktop and mobile, with an interactive catalogue, filters, search suggestions, product detail, favourites, comparison, product finder and local cart state.

> This repository is an independent UX/UI concept, not the production store. Product data, stock, pricing, accounts, orders and payments must be connected to the store's authorised systems before production use.

## Run locally

No package installation or build step is required. Serve the `dist` directory with any static server, for example:

```powershell
cd dist
npx serve .
```

## Publish

The GitHub Actions workflow deploys the contents of `dist/` to GitHub Pages after every push to `main`. In the repository settings, set **Pages → Build and deployment → GitHub Actions** once if Pages is not already enabled.

## Project structure

- `dist/index.html` — complete static site
- `dist/assets/` — local visual assets
- `.github/workflows/deploy-pages.yml` — GitHub Pages deployment

