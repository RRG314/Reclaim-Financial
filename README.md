# Reclaim Financial – Demo (Static Web App)

This is a static single-page demo. You can deploy it for **free** on any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).

## Quick Preview (local)
Just open `index.html` in a browser.

## Deploy: GitHub Pages (free)
1. Create a new GitHub repo (public is fine).
2. Upload **index.html** to the root of the repo.
3. In **Settings → Pages**, set **Source** to **Deploy from a branch**, pick **main** and root (`/`), then **Save**.
4. Your site will be available at `https://<your-username>.github.io/<repo-name>/` within a minute.

## Deploy: Netlify (free)
1. Go to https://app.netlify.com/ and click **Add new site → Deploy manually**.
2. Drag & drop this folder; Netlify will publish immediately.

## Deploy: Vercel (free)
1. Create a new project on https://vercel.com/.
2. Import the GitHub repo that contains this `index.html` (no build step required).
3. Vercel will deploy automatically.

## Deploy: Cloudflare Pages (free)
1. Go to https://dash.cloudflare.com/ → **Pages** → **Create a project**.
2. Connect your GitHub repo; set **Build command** to `None` and **Build output directory** to `/`.
3. Deploy.

---

### Notes
- No backend is required; this is fully client-side.
- If you later add routing or assets, keep them in the same folder and ensure paths are relative.
