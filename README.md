# Baku landing page

Baku stops AI support agents from paying out fraudulent refunds, credits and codes.

| File | Purpose |
|---|---|
| `index.html` | The whole site. No build step. |
| `.nojekyll` | Tells GitHub Pages to serve files as-is. |

Deploy: GitHub Pages from `main` at `/`. To move to a custom domain, add a `CNAME` file with the domain and point DNS at GitHub Pages.

The sales form opens the visitor's email app with the request pre-filled, or copies it. Swap the address in `index.html` (`salesEmail`) when the Baku mailbox exists.
