# Kenable Website — Rebrand v4

Static, responsive placeholder website for **Kenable Technologies Private Limited**.

## Brand changes
- Replaced the previous logo with the supplied Kenable full lockup and standalone symbol.
- Updated favicon, social preview, page titles, SEO metadata and structured organisation data.
- Updated all public contact references to `contact@kenable.in`.

## Public positioning
The website keeps the same restrained public focus:
- Industrial IoT
- Smart Homes & Assisted Living
- AgriTech
- Engineering Education, especially higher education with an engineering emphasis

It does not expose internal platforms, methods, architecture, partnerships or commercial models.

## Files
- `index.html` — homepage
- `privacy.html` — privacy notice
- `404.html` — not-found page
- `assets/` — supplied brand assets, favicon, CSS and JavaScript
- `robots.txt` and `sitemap.xml`

## Preview locally
Open `index.html`, or run `python -m http.server 8080` from this directory and visit `http://localhost:8080`.

## Deployment
For GitHub Pages, upload the contents of this folder to a repository root, configure Pages to deploy from `main` / root, then add `www.kenable.in` as the custom domain. Configure GoDaddy DNS for `kenable.in` using GitHub Pages' current A records and a `www` CNAME pointing to `<github-username>.github.io`. Keep email MX and TXT records intact. Enable HTTPS after DNS verification.

## Before launch
- Confirm `contact@kenable.in` is active.
- Confirm whether `www.kenable.in` or `kenable.in` is the preferred canonical host. Current metadata uses `www.kenable.in`.
- Confirm the legal company name and approved logo lockup are correct.
