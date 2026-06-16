# Exact Posterior Score (EPS) — project page

Static project page for *Exact Posterior Score Estimation for Solving Linear Inverse Problems*.

## Run locally

```bash
cd sample_website
python3 -m http.server 8000
# open http://localhost:8000
```

It is a fully static site (HTML + CSS + vanilla JS). No build step.

## Structure

- `index.html` — page content; results tables are generated from the data block at the bottom of the file.
- `styles.css` — design system / layout.
- `assets/js/pivot-lab.js` — the interactive "Pivot Lab" canvas visualizing the shifted pivot `μ★` and anisotropic covariance `Σ★` from Theorem 1.
- `assets/eps/` — figures exported from the paper (PNG).

## Notes

- Math is rendered with MathJax (CDN).
- Paper / arXiv / PDF / code links in the hero are placeholders (`#`) — fill them in when available.
- Figures were rendered from the LaTeX sources; re-export to `assets/eps/` if the paper figures change.
