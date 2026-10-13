# Private site

This site is password-protected. The page and every file in `files/` are encrypted with
AES-256-GCM; the key is derived from the password in the browser (PBKDF2-SHA256,
600,000 iterations). Nothing readable is stored in this repository.

Deployed to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.
