# agent-mesh

Source for the essay **"Your Reflection Loop Is Just a Model Arguing With Itself"**, published via GitHub Pages at:

**https://jst-jdennis.github.io/agent-mesh/**

## Structure

- `index.html` — the post (self-contained: inline CSS, web fonts from Google Fonts)
- `.github/workflows/pages.yml` — deploys the static site to GitHub Pages on push to `main`
- `.nojekyll` — serves files verbatim (skips Jekyll processing)

## Publishing

Deployment is automated. Once **Settings → Pages → Source** is set to **"GitHub Actions"**, every push to `main` rebuilds and deploys the site.
