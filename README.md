# Ricardo Paez, portfolio

Plain HTML and CSS: no build step, no dependencies. Served by GitHub Pages.

- `index.html`: the whole site
- `styles.css`: light and dark themes (follows the visitor's system setting)
- `samples/`: free sample PDFs from stem-packs
- `.nojekyll`: tells Pages to serve the files as-is instead of running Jekyll

Preview locally:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

All links are relative, so the site works whether this repo is named `RAPaez.github.io` (served at the root) or anything else (served at `/<repo-name>/`).
