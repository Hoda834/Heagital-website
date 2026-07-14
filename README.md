# Heagital website

Static site for Heagital Ltd, served via GitHub Pages at https://www.heagital.com

## Structure
- `index.html` — the entire site (inline CSS, inline SVG logo)
- `CNAME` — custom domain. Must contain exactly `www.heagital.com`. Do not add a second CNAME anywhere else in the repo.
- `.nojekyll` — skips Jekyll processing
- `.github/workflows/static.yml` — deploys the repo root to GitHub Pages on push to `main`

## Notes
The workflow uploads the whole repo (`path: '.'`). Any stray file committed to the root gets published. Keep it clean.
