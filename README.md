# GitHub Pages (Static) — No-Change Wrapper

This repo is set up so GitHub Pages can host **your HTML exactly as-is**.

- `index.html` is byte-for-byte copied from your upload.
- `.nojekyll` forces GitHub Pages to serve files as plain static content.

## Deploy steps (GitHub UI)
1. Create a new repo (any name).
2. Upload **everything in this folder** to the repo root.
3. Go to **Settings → Pages**
4. Under **Build and deployment**, pick:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`) / `/ (root)`
5. Save. Your site URL appears on that page.

## Integrity
SHA-256 of `index.html` in this package:
`b0b6650e05cacc8f442118a22748e9f7b8715fd9ad8952ad5724175dc61022c0`
