# MBE Website

Source of the MBE website, hosted with GitHub Pages.

The pages are written in Markdown and built with Jekyll, which GitHub Pages runs automatically on every push.

## Structure

- `de/`, `en/` – the pages in German and English, one Markdown file per page
- `_layouts/default.html` – shared HTML frame (header, language switch, footer)
- `style.css` – styling
- `index.html` – redirects to `/de/` or `/en/` depending on the browser language
- `_config.yml` – Jekyll settings

## Adding or changing a page

Create the page under the same file name in both `de/` and `en/`, e.g. `de/about.md` and `en/about.md`.
The language switch links the two by their path, so the file names must match.
Each file starts with a title:

```markdown
---
title: About
---

# About us
```

## Local preview

One-time setup (needs Ruby with headers, e.g. `sudo apt install ruby-dev`):

```sh
gem install --user-install bundler
bundle config set --local path vendor/bundle
bundle install
```

Then start the preview and open <http://localhost:4000>:

```sh
bundle exec jekyll serve --livereload
```

## Publishing

The `main` branch is published by GitHub Pages (Settings → Pages).
