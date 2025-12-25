# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll static site blog ("Lison's Log") hosted on GitHub Pages at blowxian.github.io. The site uses the Tale theme and content is written in Chinese.

## Common Commands

```bash
# Install dependencies
bundle install

# Run local development server (http://localhost:4000)
bundle exec jekyll serve

# Build for production (outputs to _site/)
bundle exec jekyll build

# Serve with live reload
bundle exec jekyll serve --watch
```

## Architecture

- **_posts/**: Blog posts in Markdown format (named `YYYY-MM-DD-slug.md`)
- **_layouts/**: Page templates (default.html, home.html, post.html)
- **_includes/**: Reusable HTML components (head, navigation, footer, analytics)
- **_sass/tale/**: SCSS styles for the Tale theme
- **assets/**: Static files (images, compiled CSS entry point)
- **_config.yml**: Jekyll configuration (site metadata, plugins, permalink structure)

## Creating New Posts

Add a Markdown file to `_posts/` with this format:

```yaml
---
layout: post
title: "Post Title"
date: YYYY-MM-DD
categories: category-name
published: true
author: Lison
---

Content here...
```

## Deployment

Push to master branch - GitHub Pages automatically builds and deploys.
