# burn-me-twice

Splash page for **Burn Me Twice** — small-batch, fire-roasted local salsa. Deployed on Cloudflare Pages and served at onepulp.org.

## Files

- `index.html` — page content (hero, product story, footer)
- `styles.css` — tie-dye styling and layout
- `images/jar.svg` — jar image placeholder (replace with a real product photo)

## Deploy

Cloudflare Pages is connected to this repo. Pushing to `main` triggers an automatic build and deploy — no manual steps.

Cloudflare caches assets (including `jar.svg`) for up to 4 hours. When you change an image, bump the version in `index.html` (e.g. `images/jar.svg?v=3`) so browsers fetch the new file, and purge the Cloudflare cache if a stale image persists.

## Edit

Clone, edit in VS Code, commit, push:

```
git clone https://github.com/onepulp/burn-me-twice.git
# make edits in VS Code
git add .
git commit -m "description of change"
git push
```
