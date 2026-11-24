# Brokerage Portal

Static front end for the brokerage trial-balance and reconciliation portal.

- `index.html` is served by GitHub Pages.
- Data, users and passwords live in a Google Sheet behind a Google Apps Script web app; nothing sensitive is stored in this repository.
- To point the site at a different backend, change `API_URL` near the top of `index.html`.
