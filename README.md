# Neg School — Website

This repository contains a minimal static website for Neg School and is configured for a custom domain (negschool.com).

Files added:
- `index.html` — main site
- `styles.css` — site styles
- `CNAME` — contains the custom domain `negschool.com`
- `assets/` — favicon and social preview image

Local preview:
- Open `index.html` in a browser.

Publish with GitHub Pages and CNAME (already added):
1. Push to the `main` branch (done).
2. In the repository settings on GitHub → Pages, confirm branch `main` and folder `/ (root)` is selected and save.
3. Your site will be available at `https://negschool.com` once DNS is configured and validated by GitHub.

DNS configuration for negschool.com (at your registrar):
- A records for the apex domain (negschool.com):
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- CNAME for `www` -> `vijaytamang37-cmd.github.io`

Contact form (Formspree):
- The contact form in `index.html` uses a placeholder action `https://formspree.io/f/your-form-id`.
- Sign up at https://formspree.io, create a form, and replace the action URL with your Formspree endpoint to receive submissions.

Next steps I can do for you:
- Replace the Formspree action with your actual endpoint (paste it here) and push the change.
- Add additional pages (Staff, Admissions details, Events, Gallery).
- Upload your logo and replace the SVG favicon with a PNG if you prefer better compatibility.