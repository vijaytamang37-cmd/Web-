# Neg School — Website

This repository contains a minimal static website for Neg School and is configured for a custom domain.

Files added:
- `index.html` — main site
- `styles.css` — site styles
- `CNAME` — contains the custom domain `negschool.com`
- `assets/.gitkeep` — placeholder for images and other assets

Local preview:
- Open `index.html` in a browser.

Publish with GitHub Pages and CNAME (already added):
1. Push to the `main` branch (done).
2. In the repository settings on GitHub → Pages, confirm branch `main` and folder `/ (root)` is selected and save.
3. The custom domain `negschool.com` is set via the CNAME file. Configure your DNS to point the domain to GitHub Pages (A records to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 and CNAME for www to `vijaytamang37-cmd.github.io`).

Formspree contact form:
- The contact form in `index.html` uses a placeholder action `https://formspree.io/f/your-form-id`.
- Sign up at https://formspree.io, create a form, and replace the action URL with your Formspree endpoint to receive submissions.
