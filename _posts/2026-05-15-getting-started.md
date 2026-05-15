---
layout: post
title: "Getting started with GitHub Pages and Jekyll"
date: 2026-05-15
categories: [meta, github-pages]
tags: [jekyll, github-pages, blogging]
---

Welcome to the first post on this blog. I set this up using [GitHub Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/) — the simplest way to publish a Markdown-based blog for free directly from a GitHub repository.

## Why GitHub Pages and Jekyll?

- **No hosting costs** — GitHub Pages is free for public repositories.
- **Git-based workflow** — write a post, commit, push; the site rebuilds automatically.
- **Markdown** — no CMS, no database, just plain text files under version control.
- **Built-in themes** — the `minima` theme looks clean out of the box and requires zero configuration.

## How it works

GitHub Pages detects the `_config.yml` at the root of the repository and builds the site with Jekyll. Any `.md` file placed in the `_posts/` folder with a filename in the format `YYYY-MM-DD-title.md` is treated as a blog post.

```text
mathiasfritsch.github.io/
├─ _config.yml
├─ index.md
├─ about.md
└─ _posts/
   └─ 2026-05-15-getting-started.md
```

## Publishing a new post

1. Create a file in `_posts/` following the naming convention.
2. Add front matter at the top (the `---` block with `layout`, `title`, and `date`).
3. Write the post body in Markdown.
4. Commit and push — GitHub Actions rebuilds the site within a minute or two.

That's it. No build step to run locally, no deployment pipeline to configure.

## What's next

I plan to write about things I'm actively working on — .NET backend patterns, Angular component design, and cloud infrastructure on AWS and Azure. Stay tuned.
