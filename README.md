# Sons Of The Forest Route Map

Standalone GitHub Pages site for the optimized Sons of the Forest progression route.

## Pages Entry Points

- `index.html`: redirects to the checklist-tracking map.
- `sons-of-the-forest-route-checklist-map.html`: interactive map with per-location checklist tracking.
- `sons-of-the-forest-progression-guide.md`: written progression guide and coordinate appendix.

The maps use external MapGenie tiles and MapLibre CDN, so the hosted page requires internet access.

## GitHub Pages Deployment

This repo includes `.github/workflows/pages.yml`, which deploys the site from the repository root whenever `main` is pushed.

To host it:

1. Push this repo to GitHub.
2. In the GitHub repo, go to **Settings > Pages**.
3. Set **Build and deployment > Source** to **GitHub Actions**.
4. Push to `main` or run the **Deploy GitHub Pages** workflow manually.

The hosted root URL will redirect to `sons-of-the-forest-route-checklist-map.html`.
