# Baku landing page

Baku stops AI support agents from paying out fraudulent refunds, credits and codes.

| File | Purpose |
|---|---|
| `index.html` | The whole site. No build step. |
| `.nojekyll` | Tells GitHub Pages to serve files as-is. |

Deploy: GitHub Pages from `main` at `/`. Custom domain: joinbaku.ai (see `CNAME`).

The request form opens the visitor's email app with the request pre-filled. Contact address: hello@joinbaku.ai (`id="mail"` in `index.html`). Edit `page.html` (gitignored artifact source) or `index.html` directly.
