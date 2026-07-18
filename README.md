# Personal site (GitHub Pages)

A fast, static personal site built with plain HTML and CSS — no build step, no frameworks.
Hosted for free on [GitHub Pages](https://docs.github.com/en/pages).

## Files

| File | Purpose |
|------|---------|
| `index.html` | The home page |
| `style.css` | All styling |
| `404.html` | Custom "page not found" page |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll and serve files as-is |

## Editing

Just open `index.html` and change the text. Every occurrence of "Your Name",
`you@example.com`, and the project cards is placeholder content meant to be replaced.

## Local preview

Open `index.html` directly in a browser, or run a tiny local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

This repo is named `USERNAME.github.io`, so GitHub Pages publishes it automatically
from the default branch. After pushing, the site is live at:

```
https://USERNAME.github.io
```

It can take a minute or two for the first publish to go live.
