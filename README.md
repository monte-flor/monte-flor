# Monte Flor

Website for Monte Flor, an organic cut-flower farm on the terraced hills of Galicia, Spain.

Plain static HTML site (Tailwind CSS via CDN, no build step) — the whole site lives in `index.html`. All copy and photos are placeholders and will be personalized.

## Local preview

```bash
python3 -m http.server
```

Then open http://localhost:8000.

## Deployment

Pushes to `main` auto-deploy to GitHub Pages via `.github/workflows/deploy.yml`.
