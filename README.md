# Goshen Garden

Static site for [goshen.garden](https://goshen.garden), built with Jekyll.

## Setup

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Then visit http://localhost:4000.

## Structure

```
_pages/         # Static pages (about, the land, philosophy, etc.)
_posts/         # Journal entries (YYYY-MM-DD-title.md)
_layouts/       # Page templates
_includes/      # Partials
assets/css/     # Custom styles
index.md        # Home page
_config.yml     # Site configuration
```

## Writing a journal entry

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` with this front matter:

```yaml
---
layout: post
title: "Your Title"
date: YYYY-MM-DD
---
```
