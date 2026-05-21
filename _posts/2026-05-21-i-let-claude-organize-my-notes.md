---
layout: post
title: "I let Claude organize my notes (and it kind of stunned me)"
description: "What happens when you drop one article into an Obsidian vault and ask Claude to organize it: thirteen linked pages, citations, and a working log."
date: 2026-05-21
tags: [ai-explained, harness-engineering, second-brain, obsidian, claude-code]
---

Yesterday afternoon. I had a folder of half-read articles, a fresh Obsidian vault, and a vague hunch. I dropped one essay into the folder, asked Claude to "ingest" it, and walked away to make coffee.

When I came back, my empty vault had thirteen new pages in it. All linked to each other. With citations. I just stood there for a second.

## The setup (and yes, no code)

Three things on my desk:

- **Obsidian** — a free app that opens a folder of markdown files. That's it. No login, no cloud.
- **A pattern called "LLM Wiki"** — a one-page rulebook telling Claude *how* to write pages, where to put them, and how to link them. I dropped it into the vault and Claude read it every time.
- **Claude Code** — the part that actually reads sources and writes pages.

The deal was simple. I drop articles into a `raw/` folder. Claude owns everything else — summaries, concept pages, an index, a log. I'm the curator. It's the librarian.

## What actually happened

The article I fed it was a long forecast about AI through 2027 — the kind of thing I'd normally skim and forget.

By the time my coffee was done, my vault had:

- One summary of the article
- Six pages on the people and orgs it mentioned, with what each one *did*, cited
- Six pages on the big ideas inside it, with quotes in context
- An updated index showing me everything, grouped by topic
- A log saying "here's what I just did, and here's what I didn't finish"

That last one was the part that stunned me. Claude flagged that the article I'd given it was *incomplete* — the original page had two ending branches that my clip didn't capture. It noticed before I did.

## Why this is different from "AI search"

You've probably heard of the idea where you point an AI at a folder and ask it questions. That's a search. Every time you ask, it starts from scratch. The folder stays as flat as you left it.

This is the opposite. Every new article *rewrites* the pages it touches. The second source I added wove itself into the first one's pages, on its own. Drop in fifty sources and a single concept page would have perspectives from every angle, all citing each other.

I haven't done fifty yet. I've done two. But you can already feel the shape: the vault gets *denser* every time. A search engine gives you the same answer twice. This thing gives you a smarter answer the second time.

## What I'm not pretending

Two sources is not fifty. The "it compounds" magic is mostly still theoretical for me. And honestly — Claude wrote good pages because the article I picked was already well-written. Garbage in, garbage out still applies.

But the loop works. That's the part I didn't expect. A folder, a rulebook, and an AI that actually shows its work.

## Your turn

If you have an Obsidian vault gathering dust, or even just a folder of articles you keep meaning to read — you can try this today. No code. The whole rulebook was a single markdown file.

Find one piece you actually care about. Drop it in. Ask Claude to ingest it. See what comes back.

If you want a head start, I put my whole vault on GitHub: [kimleak/obsidian-llm-wiki](https://github.com/kimleak/obsidian-llm-wiki). The rulebook is one file (`CLAUDE.md`). Copy it into your own vault and you've skipped the boring part.

The notes I used to *take* are starting to take themselves. Strange feeling. Good strange.
