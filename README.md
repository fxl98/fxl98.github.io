# Xuelu Feng — Personal Homepage

Static academic homepage (plain HTML + CSS, no build step), designed for GitHub Pages.

## Files

- `index.html` — the page content (edit this to update bio, news, publications, etc.)
- `assets/style.css` — styling (light/dark mode follows the system setting)
- `assets/Xuelu_CV.pdf` — CV linked from the sidebar
- `assets/photo.jpg` — **add your photo here** (square, ~400×400 px). If missing, initials are shown instead.

## Deploy to GitHub Pages

1. Create a new **public** repository on GitHub named `<your-username>.github.io`.
2. Push this folder to it:

   ```bash
   git remote add origin git@github.com:<your-username>/<your-username>.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. On GitHub, open **Settings → Pages**, set *Source* to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. After about a minute the site is live at `https://<your-username>.github.io`.

## Updating

Edit `index.html`, commit, and push. GitHub Pages redeploys automatically.
