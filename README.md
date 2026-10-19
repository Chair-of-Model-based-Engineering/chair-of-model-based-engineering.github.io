# MBE Website

Source of the MBE website, hosted with GitHub Pages.

The pages are written in Markdown and built with Jekyll, which GitHub Pages runs automatically on every push.

## Structure

- `de/`, `en/` – the pages in German and English, one Markdown file per page
- `assets/img/`, `assets/files/` – images and PDFs used by the pages
- `_layouts/default.html` – shared HTML frame (header, navigation, language switch, footer)
- `_data/nav.yml` – entries of the main navigation and the footer links, with their German and English labels
- `_data/team.yml` – contact details of the team
- `_data/theses.yml` – finished theses without a page of their own
- `_includes/` – building blocks used by the pages (contact block, team group, thesis list)
- `style.css` – styling
- `index.html` – redirects to `/de/` or `/en/` depending on the browser language
- `_config.yml` – Jekyll settings

## Adding or changing a page

Create the page under the same file name in both `de/` and `en/`, e.g. `de/about.md` and `en/about.md`.
The language switch links the two by their path, so the file names must match.
To show the page in the navigation, add it to `_data/nav.yml`.

## Adding a thesis

Copy an existing file in `de/theses/bachelor/` or `de/theses/master/` and give it a new name (lowercase, hyphens, no umlauts).
The file name becomes the address: `de/theses/master/my-topic.md` is served at `/de/theses/master/my-topic/`.
Set `title` and `year` in the header:

```markdown
---
title: "My topic"
year: 2026
---
```

The lists on the German and English thesis pages are generated from these files, newest year first.
A finished thesis without a page of its own is entered in `_data/theses.yml` instead.

## Adding or changing a team member

Contact details are entered once in `_data/team.yml` and shown on the team page in both languages.
Put the photo in `assets/img/` and name it in the entry.
The `group` decides the section; within a section, people appear in the order of the file.

For a personal page, create `de/team/<id>.md` and `en/team/<id>.md`, set `page: true` in the entry and start the page with the contact block:

```liquid
{% include person.html id="<id>" detail=true %}
```

## Notes

A page may exist in one language only (many thesis pages are German only).
The language switch then leads to the start of that section in the other language.

Links between pages and to assets are written from the site root, e.g. `/de/team/` or `/assets/img/photo.jpg`.
This requires the site to be served from the root of its domain (an organization site `<org>.github.io` or a custom domain).

A file `de/team.md` and a file `de/team/index.md` both produce the address `/de/team/`; sections with subpages use the second form.
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
