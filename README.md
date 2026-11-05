# blessyantony9.github.io

Personal academic website for Blessy Antony, built with Jekyll and served via GitHub Pages
(native Pages build, no Actions workflow required).

## Structure

- `_pages/` — About (home), Publications, Research, CV
- `_publications/` — one Markdown file per publication (front matter: `title`, `type`
  [`peer-reviewed` / `preprint` / `under-review`], `date`, `venue`, `paperurl`, `citation`)
- `_layouts/`, `_includes/` — minimal custom theme
- `assets/css/main.scss` — site styles (soft neutral palette)
- `files/` — downloadable PDFs (CV, posters, etc.)
- `images/` — site images

## Run locally

```
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
