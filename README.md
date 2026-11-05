# SiteView — Retired Environmental

Single-file web app. Accounts, data and files live in the `siteview-cloud` Firebase
project; this repository holds only the page (`public/index.html`).

Every push to `main` publishes the page to GitHub Pages through the workflow in
`.github/workflows/pages.yml`. `firebase.json` is here for an optional Firebase
Hosting deploy of the same folder.
