# Keitaro Ninomiya — Personal Website

A clean, minimal academic personal website built with [Jekyll](https://jekyllrb.com/) and the [Minima](https://github.com/jekyll/minima) theme. Inspired by [Alex Bartik's site](https://www.alexbartik.com/).

## Deploy to GitHub Pages

### Option A: Use `username.github.io` (recommended)

1. Create a new repository on GitHub named **`keitaroninomiya.github.io`** (or `Keitaro-Ninomiya2.github.io` if that's your username — GitHub will redirect).

2. Push this folder to the repo:
   ```bash
   cd keitaroninomiya.github.io
   git init
   git add .
   git commit -m "Initial Jekyll site"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git push -u origin main
   ```

3. GitHub Pages will automatically build and deploy. Your site will be live at:
   - `https://keitaroninomiya.github.io` (if repo is `keitaroninomiya.github.io`)
   - or `https://keitaro-ninomiya2.github.io` (if your GitHub username is `Keitaro-Ninomiya2`)

### Option B: Use a project repo with custom domain

1. Push to any repo and go to **Settings → Pages**.
2. Select the `main` branch and `/ (root)` folder.
3. Your site will be at `https://YOUR_USERNAME.github.io/REPO_NAME/`.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).

## Customize

- **`_config.yml`** — Site title, URL, description
- **`index.md`** — Home page content (CV links, research summary)
- **`about.md`** — About page

## Update your links

Replace the Dropbox links in `index.md` with permanent URLs (e.g., host PDFs in the repo’s `/assets/` folder or use a stable link). Add your Google Scholar profile URL when ready.
