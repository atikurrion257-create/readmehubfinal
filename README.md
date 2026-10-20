# ReadMeHub

Static ReadMeHub review and comparison website, preserved from the supplied HTML prototype.

## Run locally

No build step or dependencies are required. Serve the repository root on port 3000:

```bash
python3 -m http.server 3000 --bind 0.0.0.0
```

Then open `http://localhost:3000`.

## GitHub Pages

The repository includes `.github/workflows/pages.yml`. Pushes to `main` deploy automatically through the free GitHub Pages workflow. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions** if it is not already selected.

The site uses hash-based view switching, so it works from a repository subpath without a server-side router.
