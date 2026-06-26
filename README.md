# Vinay Gandhi — Portfolio & Engineering Hub

**Live site:** [https://vgandhi1.github.io/](https://vgandhi1.github.io/)

Personal portfolio for AI systems, manufacturing software, and EV platforms. The site links to GitHub repositories for evidence, hosts illustrated theory and programming guides on this domain, and points to a separate **[interactive lab](https://vgandhi1.github.io/interactive-lab/)** for slide decks, EV references, and browser tools.

| Site | Repository | URL |
|------|------------|-----|
| Portfolio (this repo) | [vgandhi1/vgandhi1.github.io](https://github.com/vgandhi1/vgandhi1.github.io) | `https://vgandhi1.github.io/` |
| Interactive lab | [vgandhi1/interactive-lab](https://github.com/vgandhi1/interactive-lab) | `https://vgandhi1.github.io/interactive-lab/` |

---

## What’s on the site

The landing page (`index.html`) is a **custom static** minimal landing (styled by `portfolio_min.css`) leading with applied AI + data work. A comprehensive **full project catalog** lives at [`index-full.html`](index-full.html) (`portfolio_home.css`) — every repo grouped by pillar with filter tabs; linked from the `index.html` footer (“Full catalog”). The minimal `index.html` is organized into:

| Section | Anchor | Content |
|---------|--------|---------|
| **About** | `#about` | Background, skills, active build ([AEGIS](https://github.com/vgandhi1/aegis)) |
| **Projects** | `#projects` | GitHub work grouped by engineering pillar (Data, AI, Software, Product) with filter tabs |
| **Learn** | `#learn` | Links to theory notes and programming tracks on this domain |
| **Interactive lab** | — | External hub for decks, EV docs, and simulators |
| **Project execution guide** | [project_execution.html](project_execution.html) | Visual roadmap — build order and three-pillar entry paths |
| **Factory AI Platform** | [factory-ai.html](factory-ai.html) | Flagship build deep-dive (AEGIS / SentinelFlow) |
| **MVP demos** | [mvp.html](mvp.html) | Live product walkthroughs |

**Project pillars** on the landing page: **Data Engineering** (OMNI-Mesh, telemetry, ELT), **AI Engineering** (factory AI, agentic/RAG, CV/ML, robotics), **Software Systems** (streaming backends, EV/OTA, web apps), and **Product Management** (APEX-recover, TeleOp). Use the filter tabs on `#projects` or the [roadmap pillars section](project_execution.html#pillars) for role-aligned entry paths.

**Product demo:** Motel Web Portal walkthrough GIF (`assets/demos/motel-portal-demo.gif`) — source: [Motel-web-portal](https://github.com/vgandhi1/Motel-web-portal).

---

## Repository structure

```
vgandhi1.github.io/
├── index.html                 # Main portfolio landing page (minimal)
├── index-full.html            # Full project catalog (comprehensive archive; noindex)
├── portfolio_min.css          # Styles for index.html (minimal landing)
├── portfolio_home.css         # Styles for index-full.html (full catalog)
├── portfolio_hub.css          # Shared/legacy hub styles
├── _config.yml                # Jekyll / GitHub Pages metadata (remote Minima theme)
├── assets/demos/              # Demo media (e.g. motel-portal-demo.gif)
├── theory/                    # Illustrated ML/AI theory notes
│   ├── ml_theory_hub.html     # Hub
│   ├── ml_theory.css
│   └── theory_*.html          # Topic pages (DE, classical ML, DL, RAG, MLOps, …)
├── interview-prep/            # Interview prep guides
│   └── ml-ai-interview-guide.html
├── programming/               # Language & interview tracks
│   ├── python_101.html        # Python hub (+ data/ML, PyTorch, FastAPI pages)
│   ├── python_101_common.css
│   ├── Go_101_Backend_Systems.html
│   └── SQL_Interview_Prep_FactoryAnalytics.html
├── Go_101_Backend_Systems.html              # Legacy copies at repo root
├── SQL_Interview_Prep_FactoryAnalytics.html
├── ml_theory_hub.html                       # Legacy redirect/hub at root
├── project_execution.html                   # Visual portfolio roadmap
├── project_execution.css                    # Roadmap page styles
├── factory-ai.html                          # Factory AI Platform deep-dive
└── mvp.html                                 # MVP product demos
```

### Theory hub (`theory/`)

Static, self-contained pages with inline SVG diagrams:

- [Data engineering](theory/theory_data_engineering.html)
- [Classical ML](theory/theory_classical_ml.html)
- [Deep learning](theory/theory_deep_learning.html)
- [Applied AI engineering](theory/theory_applied_ai_engineering.html)
- [RAG vs fine-tuning](theory/theory_rag_vs_finetune.html)
- [MLOps](theory/theory_mlops.html)
- [LLMOps](theory/theory_llmops.html)
- [DevOps](theory/theory_devops.html)

Entry: [theory/ml_theory_hub.html](theory/ml_theory_hub.html)

### Programming tracks (`programming/`)

- **Python 101** — hub plus [Data & ML](programming/python_101_data_ml.html), [PyTorch](programming/python_101_pytorch.html), [FastAPI](programming/python_101_fastapi_eng.html)
- **Go 101** — backend systems ([programming/Go_101_Backend_Systems.html](programming/Go_101_Backend_Systems.html))
- **SQL interview prep** — factory analytics ([programming/SQL_Interview_Prep_FactoryAnalytics.html](programming/SQL_Interview_Prep_FactoryAnalytics.html))

### Interactive lab (separate repo)

Decks, EV references, homelab portal, and browser tools (DSA, AI glossaries, hedging simulator, Git 101, etc.) live in **[interactive-lab](https://github.com/vgandhi1/interactive-lab)** — not duplicated here.

- Hub: [vgandhi1.github.io/interactive-lab/](https://vgandhi1.github.io/interactive-lab/)
- Case studies: `#case-studies`
- Tools: `#tools`

---

## Tech stack

| Layer | Choice |
|-------|--------|
| Portfolio UI | Static HTML + CSS (`portfolio_min.css` for `index.html`, `portfolio_home.css` for `index-full.html`) |
| Theory / programming | Static HTML + shared CSS, JetBrains Mono + Source Sans 3 |
| Hosting | [GitHub Pages](https://pages.github.com/) |
| Optional build | Jekyll (`_config.yml`, `remote_theme: jekyll/minima`) for Pages compatibility; primary entry remains `index.html` |

---

## Local preview

**Quick static server** (recommended for `index.html`, theory, and programming pages):

```bash
cd vgandhi1.github.io-main   # or your clone path
python3 -m http.server 8000
```

Open [http://localhost:8000/](http://localhost:8000/).

**Optional — Jekyll** (if you change `_config.yml` or add Jekyll posts):

```bash
bundle install
bundle exec jekyll serve
```

---

## Deploying to GitHub Pages

1. Push to the default branch of the **`vgandhi1.github.io`** user/organization Pages repo.
2. In **Settings → Pages**, set source to that branch (root `/`).
3. Custom domain (optional): `vgandhi1.github.io` is the default user site URL.

The interactive lab is deployed from its own repo as a **project site** at `/interactive-lab/`.

---

## Contact

- **GitHub:** [@vgandhi1](https://github.com/vgandhi1)
- **LinkedIn:** [vinaygandhi274](https://www.linkedin.com/in/vinaygandhi274/)
- **Email:** gandhivinay2008@gmail.com

---

## License & attribution

Content is provided for learning, demonstration, and portfolio use. If you fork or reuse layouts or copy, please keep attribution to **Vinay Gandhi** in source and visible credits where appropriate.
