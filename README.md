# OAuth Park

Interactive OAuth 2.0 / OpenID Connect simulation in Russian.

## Publish on GitHub Pages

Extract this ZIP and upload the files (not the ZIP) to the root of pshenkoalex/oauth_pages.
Use Settings > Pages > Deploy from a branch > main > / (root).
No build step is required. All application paths are relative and work under /oauth_pages/.

## Run locally

python3 -m http.server 8000

Open http://localhost:8000 in a browser. Opening index.html through file:// does not load JS modules.

The simulator includes four flows, five blocking error scenarios, pause/step/speed/timeline controls, a Russian reference guide with primary sources, and an implementation review checklist.

This is an educational model, not a live authentication server. Tokens and HTTP examples are fictional.
