# Portfolio — Md. Apple Mahmud

Personal portfolio site. Single-page HTML (no build step). Hosted on GitHub Pages at:

**https://mapplee.github.io**

This URL is the one to give Google Play Console as your website.

## Deploy in 5 minutes

You need a repository named **exactly** `mapplee.github.io` on the account `mapplee`. GitHub Pages publishes that repo's `main` branch as your personal site at `https://mapplee.github.io`.

### Option A — Push from this folder

```bash
cd /home/telcobright/self-learning/portfolio

git init
git add index.html README.md
git commit -m "feat: portfolio site"
git branch -M main

# Create the repo on GitHub first (web UI) with the exact name: mapplee.github.io
# Then push:
git remote add origin https://github.com/mapplee/mapplee.github.io.git
git push -u origin main
```

GitHub will publish it automatically within ~1 minute. Open `https://mapplee.github.io` to verify.

### Option B — Drag & drop via web UI

1. Go to https://github.com/new
2. Repository name: `mapplee.github.io` (must match your username exactly)
3. Public, no README
4. Create
5. Click "uploading an existing file" → drop `index.html`
6. Commit
7. Open `https://mapplee.github.io` after ~1 minute

## After it's live

Plug this URL into the Google Play Console "Website" field:

```
https://mapplee.github.io
```

## To update later

Edit `index.html`, commit, push. Live within ~1 minute.
