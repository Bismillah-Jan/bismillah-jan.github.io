# bismillah.github.io

Personal portfolio and blog, built with Jekyll and hosted on GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Adding a blog post

Create a new file in `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
title: "Your post title"
date: 2026-08-07 09:00:00 +0000
tags: [tag1, tag2]
---

Post content goes here.
```

## Adding a project

Edit `projects.md` and add a new `.project-card` block.

## Structure

- `_config.yml` — site settings and navigation
- `_layouts/` — page templates (`default`, `post`)
- `_includes/` — header/footer partials
- `_posts/` — blog posts
- `assets/css/style.scss` — styling (light/dark aware)
- `index.html`, `about.md`, `projects.md`, `blog.html` — top-level pages
