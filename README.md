# Anpoo Sivanadi

Source for [asivanadi0.github.io](https://asivanadi0.github.io), a small static
professional site hosted on GitHub Pages.

## Publishing rule

The site is a factual public index, not a private records store.

- Publish only completed, independently verifiable work.
- Link to primary third-party records: upstream PRs/designs, release notes,
  official event pages, recordings, publications, or formal role listings.
- Do not publish aspirational roles, uncompleted reviews, submitted-but-unaccepted
  talks, private metrics, compensation, employer letters, or legal records.
- Confirm employer/IP approval before describing non-public work.
- Keep dates, titles, and claims consistent with LinkedIn, GitHub, and the CV.
- Remove a claim if the supporting link or source record cannot be preserved.

Open-source, writing, talks, reviewing, and mentorship sections should be added
only after at least one verified item exists. Empty sections are intentionally
omitted.

## Files

- `index.html` — home, selected experience, and education
- `cv.html` — printable public career chronology
- `style.css` — responsive light/dark and print styles
- `404.html` — not-found page
- `robots.txt` and `sitemap.xml` — search discovery
- `.nojekyll` — serve files directly without a Jekyll build

## Monthly workflow

1. Verify the source record and employer clearance.
2. Save the complete third-party artifact in the private source archive.
3. Add the public entry with a direct source link and restrained factual wording.
4. Test keyboard navigation, mobile layout, print output, metadata, and all links.
5. Confirm the public site contains no sensitive or confidential information.
6. Commit and push; archive the live URL after deployment.

## Local preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploying

Pushes to `main` publish automatically to
<https://asivanadi0.github.io>. GitHub Pages can take a few minutes to update.
