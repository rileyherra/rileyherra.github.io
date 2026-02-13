---
layout: essay
type: essay
title: "From “Good Enough” to Actually Clean"
date: 12 Feb 2026
published: true
labels:
  - Coding Standards
  - ESLint
---

## When “It Compiles” Was Enough

Before taking ICS 314, my standard for code was simple: if it compiled and ran, I was done. I didn’t really care about formatting rules or style warnings. In past classes, I would see Checkstyle errors and mostly ignore them unless they affected my grade. To me, coding standards seemed like minor details that didn’t actually change the output of the program. If the computer understood my code, that was good enough. After using ESLint with VSCode for the first time, I started to realize that mindset was incomplete.

<img src="/img/coding_standard.jpg"
     style="width: 350px; height: auto; float: right; margin: 0 0 15px 20px; border-radius: 8px;" />

## The ESLint Wake‑Up Call

After using ESLint in VSCode, I started to understand why coding standards matter. At first, all the warnings were annoying. There were red and yellow lines everywhere pointing out things I normally would have ignored. But most of them were easy to fix, and with one command a lot of formatting issues could be corrected automatically. Once I realized cleaning up my code didn’t actually take much extra time, it stopped feeling like pointless work.

<div style="clear: both;"></div>

## More Than Just Formatting

What changed for me was realizing coding standards are not just about how code looks. ESLint catches small things I would normally ignore, like variables I forgot to remove or places where I should be using const instead of let. Those small corrections make the code feel more intentional. It makes you slow down a bit instead of rushing through something messy and calling it done.

## Writing Code Other People Can Read

At some point someone else might look at my code, and that alone changes how I think about writing it. Making code readable is not only important for me, but also when working with a team. It is important that everyone is on the same page and understands what is going on in the project. Even future me will have to come back and understand what I wrote. Clean and consistent code makes that easier and makes the work feel more solid instead of rushed.