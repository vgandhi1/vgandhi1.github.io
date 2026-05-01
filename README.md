# Vinay Gandhi — GitHub Pages

**Live site:** [https://vgandhi1.github.io/](https://vgandhi1.github.io/)

Personal portfolio and learning notes published with [GitHub Pages](https://pages.github.com/). The root site uses the [Minima](https://github.com/jekyll/minima) theme via Jekyll (`_config.yml`). The **portfolio home** (`index.html`) is a standalone landing page (`portfolio_home.css`); Jekyll-generated posts (if any) use Minima separately.

---

## What’s in this repository

| File | Description |
|------|-------------|
| [`index.html`](index.html) | Portfolio landing — repos, demos, Motel GIF, links to static library, theory & programming. |
| [`portfolio_home.css`](portfolio_home.css) | Styles for the portfolio landing only. |
| [`portfolio_hub.css`](portfolio_hub.css) | Legacy teal sidebar theme (still used only if you reintroduce sidebar pages). |
| [`_config.yml`](_config.yml) | Jekyll settings: site title, description, Minima theme. |
| [`theory/`](theory/) | Illustrated ML/DE/ops theory notes (`ml_theory.css`). |
| [`programming/`](programming/) | Python 101 track, Go 101, SQL prep. |
| [`assets/demos/`](assets/demos/) | Optional media for the portfolio index (e.g. Motel Web Portal screen recording). |

### Static HTML library (separate repo)

Decks, Homelab portal, Monitron, EV reference pages, DSA, glossaries, and simulators live only in **[web-interactive-collection](https://github.com/vgandhi1/web-interactive-collection)** and are published at **[vgandhi1.github.io/web-interactive-collection/](https://vgandhi1.github.io/web-interactive-collection/)**. This user repo **does not** mirror that HTML under `interactive/` anymore.

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
