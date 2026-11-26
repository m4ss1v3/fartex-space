# FARTEX.SPACE — Global Threat Emissions

Static theatrical threat-map dashboard for GitHub Pages. All attacks, IPs, counts and routes are fictional and randomly generated. This is not real threat intelligence.

## Deploy into your existing GitHub Pages repository
1. Back up the current repository or create a branch.
2. Copy `index.html`, `styles.css`, and `app.js` into the existing Pages publishing directory (`main` / root in your current configuration).
3. Commit and push. GitHub Pages will redeploy automatically.
4. Keep `fartex.space` in Settings → Pages. Preserve or create the root `CNAME` file containing exactly `fartex.space` if your publishing setup requires it.
5. Keep your Cloudflare apex A records pointed at GitHub Pages. The `www` CNAME target should be `m4ss1v3.github.io`.

The map uses Leaflet from unpkg and CARTO Dark Matter tiles; fonts use Google Fonts. Internet access is required for these external assets. No backend or API keys are required.
