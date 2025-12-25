---
layout: post
title: Setting Up GitHub Pages
date: '2019-06-29 20:27:37 +0800'
categories: Dev Log
published: true
author: Lucas Reed
---

### Getting Started

The official GitHub Pages guide covers the basics well. Check it out here:
[GitHub Pages Official Guide](https://pages.github.com)

![](/assets/blog-img0001.png)

### Key Lessons Learned

Here are a few things I discovered during setup:

1. If you want to use a github.io subdomain, your repository name must match your GitHub username exactly. Otherwise, your site will only be accessible as a subfolder under your username's domain.

2. Initially, I tried adding markdown files and `_config.yml` manually. While this works, using Jekyll properly is much more convenient. Jekyll provides a **file structure**, **default page templates**, and access to many useful plugins.

3. To use a non-default theme, you need to add `remote_theme` to your `_config.yml`. But first, add the jekyll-remote-theme dependency:

   1. Add this to your root Gemfile:
```shell
gem "jekyll-remote-theme"
```
   2. Then run:
```shell
$ bundle
```

### Content Creation Tools

There are many tools for writing GitHub Pages content. My go-to is **Typora** — a beautifully designed Markdown editor:
[Typora](https://typora.io)

I also recommend **Prose.io** for online editing. It connects directly to your GitHub account for easy access:
[Prose.io](https://prose.io)
