# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a personal academic/portfolio website for Apoorv Umang Saxena, built on the [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/). The theme files are checked directly into the repo (not installed as a gem). The site is deployed via GitHub Pages.

## Commands

```bash
# Install dependencies
bundle install

# Serve locally (auto-reloads on file changes)
bundle exec jekyll serve

# Build site
bundle exec jekyll build

# Preview theme test pages (not the personal site)
bundle exec rake preview  # serves at http://localhost:4000/test/
```

## Site Structure

- **`index.md`** — The main homepage content (bio, publications, work experience, contact). This is where all personal content lives.
- **`_config.yml`** — Site-wide configuration: title, author info, plugins, permalink structure, theme skin.
- **`_data/navigation.yml`** — Top navigation links (currently all commented out).
- **`_layouts/`**, **`_includes/`**, **`_sass/`** — Minimal Mistakes theme files. Avoid editing unless customizing the theme.
- **`assets/`** — Static files (CSS, JS, images, downloadable PDFs like the CV).
- **`seenunseen/`** — A separate sub-project (podcast transcript browser), served as a static site at `/seenunseen`.
- **`docs/`** and **`test/`** — Minimal Mistakes theme documentation/demo; excluded from the built site via `_config.yml`.

## Key Conventions

- **Content lives in `index.md`** — there are no `_posts/` or `_pages/` for the personal site. Everything is on one page with `layout: single`, `author_profile: true`, and `toc: true`.
- **Author profile** is configured in `_config.yml` under the `author:` key (name, avatar, bio, links).
- **CV PDF** is stored at `assets/download/` and linked from `index.md` using `{{site.url}}/download/filename.pdf`.
- **Front matter** for `index.md` uses `author: Apoorv Umang Saxena` to pull sidebar profile data.
- The site uses the Minimal Mistakes `"default"` skin. To change skins, update `minimal_mistakes_skin` in `_config.yml`.
