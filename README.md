# Bethany Athletic Club · Analytics preview

Interactive sample dashboard (Chart.js) prepared with Timberline Data. **Demo data only.**

Tailored for [Bethany Athletic Club](https://bethanyathleticclub.com/) — private athletic club in the Bethany / west Portland area. Public positioning: premier west-side club since 2015; pools, group fitness, track, bistro, family-friendly mission.

## View locally

Keep **`BAC Logo.webp`** in the same folder as `index.html`. Open `index.html` in a browser, or serve the folder with any static file server.

## Publish to GitHub

From this folder (already initialized with `main`):

1. Create a **new empty repository** on [github.com/new](https://github.com/new) (no README/license—this folder is the source of truth). Pick a name, e.g. `bethany-athletic-club-analytics-preview`.
2. In PowerShell:

```powershell
cd "C:\Users\sveti\OneDrive\Desktop\Work\Bethany Athletic Center"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

Use your real username and repo URL. If GitHub shows `master` instead of `main`, run `git branch -M main` before pushing.

**GitHub CLI (optional):** if you use `gh auth login`, you can run `gh repo create YOUR_REPO --public --source=. --remote=origin --push`.

## GitHub Pages

After the repo exists on GitHub:

1. **Settings** → **Pages**
2. **Build and deployment** → Source: **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)**
4. Save. The site will be at `https://<username>.github.io/<repo>/` (may take one to two minutes). Chart.js and assets use relative URLs so the logo and charts load on that path.

## Contents

- `BAC Logo.webp` — club logo (referenced by `index.html`)
- `index.html` — full interactive preview
