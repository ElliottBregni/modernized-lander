# modernized-lander

Landing page for [elliott.bregni.com](https://elliott.bregni.com) — Modernized AI LLC.

Plain HTML + Tailwind (CDN), no build step. Served via GitHub Pages from `main`.

## Local preview

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

Pushing to `main` redeploys via GitHub Pages.

## Custom domain

To point `elliott.bregni.com` at this site:

1. Add a `CNAME` file at the repo root containing `elliott.bregni.com`
2. In your DNS provider, add either:
   - `A` records for the apex pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, **or**
   - `CNAME` for `www` → `elliottbregni.github.io`
3. In repo Settings → Pages, set the custom domain and enable HTTPS once DNS resolves.
