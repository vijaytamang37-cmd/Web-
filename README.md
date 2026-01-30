# Neg School — Starter Website

This repository contains a minimal static website for Neg School, ready to publish via GitHub Pages with a custom domain (negschool.com).

Files added
- `index.html` — main site
- `styles.css` — basic styling and responsive rules
- `CNAME` — contains the custom domain `negschool.com`
- `assets/.gitkeep` — placeholder so the `assets` folder is tracked

Local preview
- Open `index.html` in a browser for a quick local preview.

Publishing (GitHub Pages)
1. Commit and push to the `main` branch (already done by this commit).
2. In the repository Settings → Pages, ensure the branch is set to `main` and folder `/ (root)`.
3. GitHub will use the `CNAME` file to configure the custom domain `negschool.com`. You will need to configure your DNS to point your domain to GitHub Pages (see GitHub Pages docs).

Contact form
- A simple contact form is included that uses Formspree. Replace the placeholder action `https://formspree.io/f/your-form-id` in `index.html` with your actual Formspree form endpoint.

Notes
- Change site content, logo, and colors by editing `index.html` and `styles.css`.
- To add images, put them in `assets/` and reference them from HTML.
