# KEVCE Insights

Static site hosting interactive HTML reports, served via **GitHub Pages**.

**Live site:** https://mondpanther.github.io/kevceinsights/

## How it works
- `index.html` — landing page that links to each insight.
- One self-contained `*.html` file per report (all images and interactivity embedded).
- `.nojekyll` — tells GitHub Pages to serve the files as-is (no Jekyll processing).

## Publishing a new insight
1. Copy the rendered, self-contained HTML into this repo (a clean, hyphenated name,
   e.g. `my-new-insight.html`).
2. Add a linked entry near the top of `index.html`.
3. `git add . && git commit -m "Add: my new insight" && git push`.

The site updates automatically within a minute.

## Reports
- `agri-food-innovation.html` — Agriculture & Food Technology Innovation.
