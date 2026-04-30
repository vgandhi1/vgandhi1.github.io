# Vinay Gandhi — GitHub Pages

**Live site:** [https://vgandhi1.github.io/](https://vgandhi1.github.io/)

Personal portfolio and learning notes published with [GitHub Pages](https://pages.github.com/). The root site uses the [Minima](https://github.com/jekyll/minima) theme via Jekyll (`_config.yml`).

---

## What’s in this repository

| File | Description |
|------|-------------|
| [`index.html`](index.html) | Portfolio index: theory, programming, interactive hubs. |
| [`_config.yml`](_config.yml) | Jekyll settings: site title, description, Minima theme. |
| [`theory/`](theory/) | Illustrated ML/DE/ops theory notes (`ml_theory.css`). |
| [`programming/`](programming/) | Python 101 track, Go 101, SQL interview prep. |
| [`interactive/`](interactive/) | **HTML only** — mirror of tools and decks (Homelab, CV/ML, DSA, EV pages); same sources as web-interactive-collection. |
| [`interactive-support/`](interactive-support/) | Non-page assets for the collection: Homelab compose/cheatsheets, collection README (not published as Pages routes). |
| [`assets/demos/`](assets/demos/) | Shared demo media for the portfolio index (e.g. Motel Web Portal screen recording). |

### Interactive hub (GitHub Pages)

- **Canonical hub (sub-site):** [https://vgandhi1.github.io/web-interactive-collection/](https://vgandhi1.github.io/web-interactive-collection/) — primary Tailwind landing page for demos and repo highlights.  
- **Mirror in this repo:** [https://vgandhi1.github.io/interactive/](https://vgandhi1.github.io/interactive/) — same HTML with the portfolio sidebar theme.  
- **Source:** [web-interactive-collection](https://github.com/vgandhi1/web-interactive-collection).

---

## Local preview

Open `index.html` in a browser, or serve the folder with any static server, for example:

```bash
# Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

---

## License & attribution

Content is provided for learning and portfolio use. If you fork or reuse pages, keep author attribution where it appears in the HTML.
