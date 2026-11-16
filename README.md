# TrendScope

A mobile-first dashboard prototype for exploring search trends and potential monetization ideas.

## Included in this first version

- Mobile-friendly dashboard with Tamil Nadu, India and World views.
- Platform and monetization-category filters.
- Searchable sample opportunity cards.
- Links to Google Trends and YouTube searches to investigate topics.
- Basic installable-web-app metadata and offline shell.
- GitHub Actions workflow to publish the static site to GitHub Pages.

## Important data note

The cards currently contain **sample ideas, not live trend rankings, search volumes, growth rates, or verified earning estimates**. The first version does not yet connect to live platform APIs. Platform access, quotas, and terms vary; integrations will be added separately and must label source data clearly.

## Publish with GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. The workflow in `.github/workflows/pages.yml` deploys the site after a push to `main`.
4. Check the **Actions** tab for deployment status. The published URL will appear in Settings → Pages.

## Files

- `index.html` — dashboard UI and interactions
- `manifest.json` — installable app metadata
- `sw.js` — basic offline shell
- `.github/workflows/pages.yml` — Pages deployment
