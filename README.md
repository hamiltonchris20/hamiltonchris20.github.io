# ch-astro.com — Professional Website

A multi-page static site for Chris Hamilton — white background, serif typography, Oxford blue headings, pale blue links.

## Structure

| File | Purpose |
|------|---------|
| `index.html` | Homepage — bio, photo placeholder, external links |
| `research.html` | Research themes and recent work |
| `group.html` | Group members and Princeton dynamics community |
| `publications.html` | Full bibliography with arXiv & ADS links |
| `teaching.html` | Courses, lecture notes, summer school |
| `css/styles.css` | Typography and layout |
| `js/tailwind-config.js` | Tailwind color & font tokens |

## Local preview

```bash
cd /Users/chamilton/Documents/Website
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Typography & colors

- **Baskerville** (system) with **Libre Baskerville** fallback
- **Black** — body text
- **Oxford blue** (`#002147`) — headings (h1, h2), author names in publications
- **Pale blue** (`#6b9ec8`) — all links (global `a` rule)
- **Blue mid** (`#1a4d7a`) — subheadings (h3), navigation labels
