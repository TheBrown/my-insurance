# APA Happy 5 — Insurance Quick Guide

A privacy-safe, mobile-friendly static website for quickly checking common APA Happy 5 coverage limits and cashless treatment steps.

## Files

- `index.html` — complete website, no build process required.

## Local preview

Open `index.html` in a browser, or from this directory run:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy to Cloudflare Pages

1. Create a new Pages project in Cloudflare.
2. Choose **Direct Upload** (or connect a Git repository).
3. Upload the contents of this folder.
4. No build command is required.
5. Set the output/root directory to the folder containing `index.html`.
6. Optionally connect a custom domain such as `insurance.saleumsack.com`.

## Deploy to Vercel

1. Create a new Vercel project.
2. Import this folder/repository.
3. Framework preset: **Other**.
4. No build command is required.
5. Deploy.
6. Optionally add a custom domain.

## Privacy

The page intentionally does **not** publish:

- policy number
- national ID/passport number
- date of birth
- signature
- private contact information

Only the practical coverage summary and public APA links are included.
