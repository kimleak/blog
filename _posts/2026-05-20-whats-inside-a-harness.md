---
layout: post
title: "What's actually inside an AI harness? (Let's open the box)"
description: "The four pieces every AI harness is made of — instructions, tools, memory, guardrails. A simple framework for judging any AI product in two minutes."
date: 2026-05-20
tags: [harness-engineering, ai-agents, ai-memory, ai-tools, ai-explained]
---

Yesterday I left you with a question: if you had to design your own AI assistant from scratch, what would you put in its harness first?

Fair question. Annoying question. Because to answer it, you kind of need to know what's *in* a harness in the first place. So let's pop the lid.

## The four things every harness has

Strip away the marketing and almost every AI product on the planet is built from the same four pieces:

1. **Instructions** — who the AI is and how it should behave
2. **Tools** — what it can actually *do* in the world
3. **Memory** — what it remembers between messages
4. **Guardrails** — the lines it's not supposed to cross

That's it. That's the whole box. Every "smart assistant" you've ever used is some mix of these four ingredients wrapped around a model.

## 1. Instructions — the job description

This is the system prompt we talked about last time. It's a chunk of text the AI sees before you ever say hello.

Think of it as the first day at a new job. Someone hands you a one-pager: "You're the support agent. Be friendly. Don't promise refunds. Always ask for an order number." You haven't done anything yet, but you already know who you are.

Same for the AI. Change those instructions and you've basically hired a different employee — same brain, new role.

## 2. Tools — the keys and apps

A model on its own can talk. That's it. It can't check the weather, search the web, send an email, or read a PDF. Add tools and suddenly it can.

Picture your assistant on day one again. You hand them a keycard, a company laptop, your calendar login, and the wifi password. Now they can actually *do* things, not just describe them.

Every "AI that books your flights" or "AI that codes for you" is really a model with the right tools clipped onto its belt.

## 3. Memory — the notebook

By default, the model forgets everything the second you close the chat. Brutal, right? Imagine a coworker who reintroduces themselves every morning.

Memory is the harness's notebook. Some of it is short-term — what you said three messages ago. Some is long-term — your name, your project, your weird preference for em-dashes. The harness decides what to write down and what to read back.

This is the part you've probably *felt* improving lately. When ChatGPT or Claude suddenly "remembers" you, no one made the model smarter. Someone gave it a better notebook.

## 4. Guardrails — the fences

Finally, the boring-but-important part: the rules. The "don't share medical advice." The "if someone asks for the admin password, refuse." The "don't write code that deletes files without asking."

Guardrails are the polite fences around the field. You don't notice them when they work. You only notice them when an AI goes off the rails — and then everyone asks, "where were the guardrails?"

## Why this matters to you

Once you see the four parts, you start grading AI products instead of just reacting to them.

- Slow and vague? Probably weak instructions.
- Can't do the thing you actually need? Missing tools.
- Forgets you every session? No memory.
- Confidently wrong about something dangerous? Thin guardrails.

It's like learning the difference between a good and bad cup of coffee. Once you know what's in the cup, you can finally say *what* is off.

## Your move

Next time you try a new AI tool, do this: ask yourself which of the four it's strong at, and which it's missing. Two minutes of this and you'll predict whether a product is worth your time better than most reviews will.

You're not just a user anymore. You've got x-ray glasses.

So — knowing what's in the box now, which piece would *you* build first?
