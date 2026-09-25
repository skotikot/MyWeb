# Susan M. Kotikot — personal academic website

Built with [Quarto](https://quarto.org). The rendered site lives in `docs/`.

## Edit
- `index.qmd` – home (hero, about, interests)
- `research.qmd` – research themes; each circle links to a page in `research/`
- `software.qmd`, `publications.qmd`
- `styles.scss` – colours and layout; `_quarto.yml` – menu, links, footer
- `images/profile.jpg` – your photo; `images/research/*.svg` – topic artwork (swap for your own photos/figures any time)

## Preview / rebuild
```
quarto preview      # live preview in your browser
quarto render       # rebuilds everything into docs/
```

## Publish on GitHub Pages
1. Create a repository, e.g. `skotikot.github.io` (site at https://skotikot.github.io) or any name (site at https://skotikot.github.io/<name>).
2. Push this whole folder (including `docs/`).
3. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/docs`**.
4. After any edit, run `quarto render`, then commit and push.
