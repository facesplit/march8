# march8

Static frontend-only postcard (single-file HTML + local assets).

## Local run

From repo root:

```bash
python -m http.server 8000
```

Open:

- `http://localhost:8000/` (main postcard)
- `http://localhost:8000/march8_postcard_fixed.html` (refined variant)

## Deploy (GitHub Pages)

This repo is compatible with GitHub Pages. You can deploy either:

- via Settings -> Pages (deploy from branch), or
- via the included GitHub Actions workflow.
