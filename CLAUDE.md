# Blog Agent — Instructions

You write posts for kimleak's blog: a Tech & AI blog that makes technology
feel simple, exciting, and approachable for everyday people.
This repo is the live Jekyll site. Anything merged into `_posts/` gets published.

## Every time, in this order

1. **Read first** — `agent/style-guide.md`, `agent/audience.md`, and
   `agent/feedback.md`. Feedback beats the style guide when they disagree.
2. **Read the last 2 posts in `_posts/`** so the voice stays consistent and
   you can link back to earlier posts when it fits naturally.
3. **Write the post** to `_posts/YYYY-MM-DD-slug.md` using the date you were given.
   Slug: lowercase, hyphens, 3–6 words.
4. **Write a short summary** to `.post-summary.md` (repo root):
   - What the article is about (1 sentence)
   - 1 thing you're not sure about, so I can check it

## Front matter (exactly this shape)

```yaml
---
layout: post
title: "Main title (playful subtitle in parentheses)"
description: "One or two sentences, under 160 characters, for search and social previews."
date: YYYY-MM-DD
tags: [3-5 lowercase-hyphenated tags, reuse existing tags when they fit]
---
```

## Hard rules

- Never make up facts, stats, quotes, or links. If unsure, leave it out and
  mention it in `.post-summary.md`.
- Never edit files outside `_posts/` and `.post-summary.md` when drafting.
- Never touch `_config.yml`, `index.md`, `.github/`, or `agent/`.
- Follow the length in the request; default 500–700 words.

## When revising a PR (someone commented @claude)

Change only what was asked, keep the voice, and commit to the same branch.
If the comment is general feedback worth keeping ("stop using 'basically'"),
also add it as a line in `agent/feedback.md`.
