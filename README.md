# Routine Tracker (TO_DO_LIST)

Static single-page app — open `index.html` locally or use the live site below.

## Live site

**https://hk204844-ui.github.io/TO_DO_LIST/**

### If the site shows 404 (after making the repo private/public)

1. Open **Settings → Pages** on the repo.
2. Set **Build and deployment → Source** to **GitHub Actions**.
3. Open the **Actions** tab → run **Deploy to GitHub Pages** (or push to `main` triggers it).
4. Wait for the green checkmark, then reload the URL above.

## Local use

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Pushes to `main` run `.github/workflows/deploy-pages.yml` and publish to GitHub Pages.

If you use **Vercel** instead: import this repo, set framework to **Other**, output directory `.`, then redeploy after making the repo public again.
