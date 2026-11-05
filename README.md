# data-science-portfolio

Personal data science portfolio, published with **GitHub Pages**.

> **Live site:** https://wang-weicheng-mc644348.github.io/data-science-portfolio/

## What is here

| Path | Purpose |
|---|---|
| `index.html` | the portfolio page (single page, no build step) |
| `assets/style.css` | layout and typography |
| `assets/img/` | figures used on the page (copied from the project repositories) |
| `_archive/index.md` | the previous Jekyll/Markdown version, kept for reference |

The page is plain HTML + CSS, so GitHub Pages serves it directly — there is no
theme dependency and nothing to build. Edit `index.html`, push to `main`, and
the site updates within a minute.

## Featured projects

**1. Crime and House Prices in London Boroughs** — team project, CISC7204
- Repository: [cisc7204-team05-london-housing-crime](https://github.com/WANG-WEICHENG-mc644348/cisc7204-team05-london-housing-crime)
- My role: team reporter and project analyst; led the within-borough change analysis,
  its figure, and the reproducible pipeline.
- Status: ongoing

**2. Did Digital Media Erode Trust in China's Courts?** — individual
- Repository: [data-science-project](https://github.com/WANG-WEICHENG-mc644348/data-science-project)
- Data: China General Social Survey (CGSS) 2017 & 2023
- Status: ongoing

## Local preview

```bash
python -m http.server 8000
# then open http://localhost:8000
```

Or simply push to `main` — GitHub Pages rebuilds automatically.

## Updating a figure

Figures are copied, not hot-linked, so the site never breaks when a repository
changes branch layout. To refresh one:

```bash
cp ../cisc7204-team05-london-housing-crime/figures/fig4_denominator_curve.png \
   assets/img/london_denominator.png
```
