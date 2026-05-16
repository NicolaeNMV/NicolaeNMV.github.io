# Personal Blog

Personal blog built with [Astro](https://astro.build/) and deployed to GitHub Pages.

## Development

```sh
npm install
npm run dev
```

## Writing

Add posts as Markdown files in `src/content/blog`.

Each post needs frontmatter like this:

```md
---
title: My Post
description: A short summary of the post.
pubDate: 2026-05-16
draft: false
---
```

## Deployment

The site is configured for the GitHub Pages URL:

```txt
https://NicolaeNMV.github.io/
```

The workflow in `.github/workflows/deploy.yml` builds the site and deploys `dist` when changes are pushed to `main`.
