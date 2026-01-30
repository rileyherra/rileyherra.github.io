---
layout: essay
type: essay
title: "There's No Such Thing as a Dumb Question?"
date: 29 Jan 2026
published: true
labels:
  - Communication
  - Stack Overflow
---

## Why Smart Questions Matter in Software Engineering

Eric Raymond’s essay *How to Ask Questions the Smart Way* made me realize that getting good help online depends a lot on how you ask. In software engineering, communication matters just as much as technical skills, especially when you’re working with other developers in open source communities. Sites like Stack Overflow are full of people who volunteer their time, so asking clear and detailed questions is one of the best ways to get useful answers.


## Example of a “Smart” Question
<img src="/img/smart-funny.png"
     style="width: 300px; height: auto; float: right; margin: 0 0 12px 16px; border-radius: 12px;" />

A strong example of a smart question is: [Why does macOS MultitouchSupport framework crash if MTDeviceStop is called immediately after MTUnregisterContactFrameCallback?](https://stackoverflow.com/questions/79879212/why-does-macos-multitouchsupport-framework-crash-if-mtdevicestop-is-called-immed)

In this post, the developer describes a crash happening on macOS when working with trackpad touch input. The question is a great example of asking for help the “smart way” because the author clearly explains what they were trying to do, shows the exact steps that cause the problem, and includes a small code example that reproduces the crash. They also provide important context such as the macOS versions and hardware involved, along with specific error messages and the fact that the issue depends on timing. Finally, they explain what they already tried as a workaround instead of expecting others to guess. Instead of posting something vague like “my program doesn’t work,” the developer gives enough detail for others to actually investigate their issue.

<div style="clear: both;"></div>

## Example of a “Not So Smart” Question
<img src="/img/dumb-funny.jpg"
     style="width: 300px; height: auto; float: right; margin: 0 0 12px 16px; border-radius: 12px;" />
     
An example of a poorly asked question is: [R studio is frozen](https://stackoverflow.com/questions/79879198/r-studio-is-frozen)

In this post, the developer only says that RStudio froze and that code which worked yesterday is now stuck. However, they don’t provide any error messages, code snippets, or system details. Because the question is so vague, it’s basically impossible for other developers to diagnose what is actually happening. Instead of receiving answers, the author received downvotes. This demonstrates the negative outcome of asking questions in a “not smart” way because the community cannot help when the question is too vague.

<div style="clear: both;"></div>

## The Big Picture

This exercise helped me see why asking smart questions is such an important part of being a software engineer. A good question shows that you have put effort into understanding the problem, and it gives others enough information to actually help. It also creates answers that can benefit future developers who run into the same issue. On the other hand, unclear questions usually don’t lead anywhere because people can’t solve a problem if they don’t know the details.

## Works Cited

Raymond, Eric Steven. *How To Ask Questions The Smart Way*. Thyrsus Enterprises, 2014. http://www.catb.org/esr/faqs/smart-questions.html