# qinxin-yan.github.io

Plain HTML + CSS personal site. No Jekyll, no build step — edit the `.html` files directly.

## Structure

| File | Page |
|---|---|
| `index.html` | Home (bio, current projects, selected papers, appointments) |
| `research.html` | Journal articles and preprints |
| `talks.html` | Talks |
| `teaching.html` | Teaching and mentoring |
| `cv.html` | Full CV (the "Save as PDF" button prints a clean version) |
| `code.html` | Code repositories |
| `miscellaneous.html` | Notes and essays index |
| `essays/dark-forest.html` | "A Mathematical Dark Forest" (math via MathJax) |
| `assets/style.css` | All styling, including dark mode and print |

The small `*/index.html` folders (`publications/`, `talks/`, `cv/`, …) only redirect the old
Jekyll URLs to the new pages, so existing links keep working.

## Adding a paper

Copy an existing `<li class="pub">…</li>` block in `research.html` (and in `cv.html`,
and `index.html` if it should be featured). Badges: `badge published`, `badge accepted`
(“To appear”); preprints need no badge.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. (Opening `index.html` directly in a browser also works.)

## Deploy

Replace the contents of the `qinxin-yan.github.io` repository with this folder and push.
The `.nojekyll` file tells GitHub Pages to serve the files as-is.
