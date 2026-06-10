# openfab-website

The marketing & ecosystem site for **OpenFab** — served at **[open-fab.ai](https://open-fab.ai)**
via GitHub Pages.

A single-page static site (vanilla HTML/CSS/JS, no build step). GitHub Pages serves the
repository root directly.

```
index.html      # the page
style.css       # dark theme
app.js          # sticky nav + scroll reveal (progressive enhancement)
assets/         # screenshots (from open-fab-ai/openfab) + architecture.svg
CNAME           # open-fab.ai  (GitHub Pages custom domain)
.nojekyll       # serve files as-is, skip Jekyll
```

## Local preview

```bash
python3 -m http.server 8080   # then open http://127.0.0.1:8080
```

## Deploy

Pushed to `main` → GitHub Pages publishes automatically. The custom domain is configured in
repo **Settings → Pages** and pinned by the `CNAME` file.

The project itself lives at **[github.com/open-fab-ai/openfab](https://github.com/open-fab-ai/openfab)**.
Apache-2.0 · Governance: AOSF.
