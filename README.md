# Mahendra Gajera — Portfolio

A single-page interactive portfolio for **Mahendra Gajera**, AI Platforms & Automation Engineering Leader. Built as a zero-build, single-file HTML site so it deploys anywhere in under five minutes.

**Live:** `https://<your-username>.github.io/<repo-name>/` (after deploy)

---

## Highlights

- **Animated project reels** — `reels.html` plays cinematic ~45-second showcases of each of the four RangerAI features. Auto-plays through 7 scenes per project with scrub, play/pause, and project switching.
- **Featured Work showcase** — tabbed deep-dives into the four production RangerAI features shipped in RunMyJobs 2026 (Troubleshoot, Product Assistant, Automation Co-pilot, Generate)
- **Voice-over scripts** — `VIDEO-SCRIPTS.md` has ready-to-record 45-second scripts in "Simplified by Mahendra Gajera" style if you want to publish actual recorded videos
- ⌘K / Ctrl+K command palette for keyboard navigation (jumps directly to any project or reel)
- Scroll progress bar, animated counters, status badge
- Click-to-copy email & phone with toast feedback
- Expandable career sub-roles for Automation Anywhere
- Fully responsive, single-file, zero build step

---

## Quick deploy to GitHub Pages

### Option A — using GitHub Desktop or the web UI (easiest, no terminal)

1. Go to [github.com/new](https://github.com/new) and create a new repository.
   - **Name it** `mahendra-portfolio` (or anything you like). If you name it `<your-username>.github.io`, the site will live at the root domain.
   - Set it to **Public**.
2. Click **uploading an existing file** on the empty repo page.
3. Drag and drop **all the files in this folder** (`index.html`, `README.md`, `.gitignore`, `LICENSE`, and the `.github` folder).
4. Click **Commit changes**.
5. Go to **Settings → Pages**.
6. Under **Source**, choose **Deploy from a branch**, select branch **main** and folder **/ (root)**, then click **Save**.
7. Wait ~1 minute. Your site is live at `https://<your-username>.github.io/<repo-name>/`.

### Option B — using the terminal (Git CLI)

```bash
# 1. cd into the folder containing index.html
cd path/to/this/folder

# 2. Initialise the repo
git init
git add .
git commit -m "Initial portfolio"
git branch -M main

# 3. Create an empty repo on github.com first, then push:
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main

# 4. Enable Pages: Settings → Pages → Source: Deploy from a branch → main / root
```

That's it. The site auto-deploys on every push.

---

## Optional — GitHub Actions auto-deploy

A workflow file is included at `.github/workflows/deploy.yml`. It enables a more modern Pages deploy that runs on every push. To use it instead of the branch-based deploy:

1. Push the repo as above.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **GitHub Actions** (instead of "Deploy from a branch").
4. Push any change — the workflow runs automatically.

---

## Customise before publishing

Open `index.html` and search-replace these:

| Find | Replace with |
|------|--------------|
| `linkedin.com/in/mahendragajera` | your actual LinkedIn URL |
| `https://github.com/` (in the contact grid) | your actual GitHub URL |
| `mahendra.gajera@gmail.com` | only if it ever changes |
| `+919825374764` | only if it ever changes |

All content lives directly in `index.html` — no build step, no framework, no JS dependencies beyond Google Fonts. Edit the HTML and refresh.

---

## Hosting alternatives

This is a static HTML file. It works on:

- **Netlify** — drag `index.html` onto [app.netlify.com/drop](https://app.netlify.com/drop). Done in 10 seconds.
- **Vercel** — `vercel deploy` from this folder.
- **Cloudflare Pages** — connect this repo at [pages.cloudflare.com](https://pages.cloudflare.com).
- **Your own server** — upload `index.html` to any web root.

---

## License

MIT — see [LICENSE](./LICENSE). Use it, fork it, adapt it.
