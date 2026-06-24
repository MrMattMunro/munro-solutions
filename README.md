# munro.solutions

Static landing site for Munro Solutions Pty Ltd (indie games & software) + the
Floodline privacy policy. Plain HTML/CSS, no build step.

## Files
- `index.html` — landing page
- `privacy.html` — Floodline privacy policy (the URL Google Play requires)
- `style.css` — shared synthwave styling
- `assets/` — Munro logo + Floodline art
- `CNAME` — custom domain for GitHub Pages (munro.solutions)

## Deploy (GitHub Pages)
1. Push to a GitHub repo (e.g. `MrMattMunro/munro-solutions`).
2. Settings → Pages → deploy from `main` / root.
3. DNS (at VentraIP): point `munro.solutions` at GitHub Pages
   (apex A records to GitHub's IPs + a CNAME for `www`), then enable HTTPS.
4. Remove the old WordPress install once DNS has cut over.
