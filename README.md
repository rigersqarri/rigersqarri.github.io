# Portfolio Landing Page

Static site for [rigersqarri.github.io](https://rigersqarri.github.io).
Plain HTML + CSS, no build step.

## Files

- `index.html` — single-page portfolio
- `styles.css` — all styling

## How to deploy as a GitHub Pages user site

1. Create a new repo on GitHub named **`<your-username>.github.io`** (must match
   your username exactly).
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio landing"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. GitHub Pages activates automatically for `username.github.io` repos. Site
   goes live at `https://<your-username>.github.io` within a minute.

## How to update

Each project on the page links to its own repo. As projects ship:

1. Push the project repo to GitHub.
2. Edit the matching `<article class="project-card coming">` block in
   `index.html` — remove the `coming` class, swap `<span class="status">` for
   a real link to the repo and/or live dashboard.
3. Commit + push the landing repo.
