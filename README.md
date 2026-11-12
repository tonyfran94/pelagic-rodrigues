# PELAGIC Rodrigues — GitHub Pages

Static website for the PELAGIC Rodrigues fishing and marine dashboard.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **public** repository named `pelagic-rodrigues`.
2. Upload `index.html` and this `README.md` to the repository's top level (the root folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the Pages deployment to finish. Your site will be available at:
   `https://YOUR-GITHUB-USERNAME.github.io/pelagic-rodrigues/`

If you name the repository `YOUR-GITHUB-USERNAME.github.io`, the site URL will instead be:
`https://YOUR-GITHUB-USERNAME.github.io/`

## Notes

- This is a static HTML site; no server is required.
- The dashboard uses external services/CDNs and browser-side API requests. Those services must remain reachable and may impose rate limits or CORS restrictions.
- A 20-second refresh interval means the page requests updates every 20 seconds; it does not guarantee that upstream marine/weather providers publish new observations that often.
- Check the marine and weather data provider terms, attribution requirements, and API limits before making the site public.
