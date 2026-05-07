# The Unfinisht — Repository Source

This repository contains the source for the public **The Unfinisht** GitHub Pages site.

**The Unfinisht** is an unfinished digital journal about AI, edge computing, machine vision, clusters, dreams, exile, Israel, Russian/English/Yiddish fragments, and questions to eternity.

## Site Structure

- `index.md` — Homepage with project overview and thematic sections
- `about.md` — About page explaining the journal's purpose and approach
- `_config.yml` — Jekyll configuration using the Minima theme
- `.gitignore` — Standard Jekyll and Ruby ignore rules

## Local Development

To preview the site locally:

```bash
# Install dependencies
bundle install

# Start the local server
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## Deployment

The site is deployed via GitHub Pages. To enable:

1. Go to repository **Settings** → **Pages**
2. Select **Deploy from a branch**
3. Choose branch: `main`
4. Choose folder: `/ (root)`
5. Click **Save**

The site will be published at `https://theunfinisht.github.io/`

## Design Philosophy

- **Minimal, text-first** — The Minima theme keeps the focus on words
- **No heavy frameworks** — No JavaScript, no build systems beyond Jekyll
- **Poetic and honest** — Melancholic, slightly prophetic, but sincere
- **Unfinished** — This is a living journal, not a polished product
- **Multilingual echoes** — English with intentional Russian, Yiddish, Hebrew traces

---

*The machine is not complete. The dream is not complete. The question remains online.*
