# IAP-Landing-Page

Static landing page for the Identity Anchor Protocol Registry.

## Files

- `index.html`
- `styles.css`

## Run locally

```bash
cd /Users/Dirk/code/IAP/IAP-Landing-Page
python3 -m http.server 5500
```

Open `http://localhost:5500`.

## Deploy

GitHub Pages deploy is automated via:

- `.github/workflows/pages.yml`

Every push to `main` publishes the static site.
