---
layout: essay
type: essay
title: "Controlled Chaos"
date: 30 Apr 2026
published: true
labels:
  - Final Project
  - Design Patterns
  - React Bits
  - TypeScript
---

## Where the Chaos Started
<img src="/img/git-merge-conflicts.jpg" style="float: right; width: 250px; margin: 0 0 10px 15px;" />

Throughout ICS 314, I didn’t really think much about how code was organized. I would just follow the steps of the WODs and implement my solutions based on whatever the prompt was asking. As long as it worked, I was good. Once we started working on the final group project, that mindset didn’t really hold up anymore. With multiple people pushing changes and `main` constantly getting updated after merges, things could get messy fast. This is when design patterns started to make more sense to me. They’re basically common ways of structuring code so that even with multiple people working on it, everything doesn’t turn into chaos.

## The Project Structure That Kept Us Sane
Our project was set up pretty similar to what we were used to from the WODs, which helped a lot. We had a `src/app` folder for pages and styling, a `components` folder for reusable UI pieces like React Bits components and forms, and other folders like `lib`, `types`, and `test` for more specific things like auth, validation, and testing behavior. Even though I didn’t design this structure myself, working within it showed me how important it is. Instead of everything being thrown into one place, each part of the project had a clear purpose. This kind of separation allowed us to keep things organized so it’s easier to work on and understand.

## Reusing Instead of Rebuilding
My main contribution was working on the visual side using TypeScript, React, and CSS. A big part of that was creating `.tsx` component files and then reusing them across different pages. Instead of rewriting the same layouts or UI elements over and over, we could just call a component wherever we needed it. This made development faster and kept everything consistent. If something needed to change, I could update one component instead of fixing it in multiple places. Looking back, that’s really what design patterns are about because we were reusing solutions instead of starting from scratch every time.

## What Design Patterns Actually Mean to Me
Before this project, design patterns felt like something abstract or just something people talk about in interviews. But now I see them more as practical ideas that show up naturally when you’re working on bigger projects, especially in a team. They help keep code organized and reduce confusion to make collaboration smoother. Even simple things like organizing folders or reusing components reflect design pattern thinking. So to me, design patterns are ways to structure code that make it easier to build and and help control the chaos.