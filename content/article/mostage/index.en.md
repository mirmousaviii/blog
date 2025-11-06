---
title: "Mostage: A Presentation Framework"
date: 2025-10-14T19:59:06+02:00
draft: false
categories: ["project"]
tags:
  [
    "presentation",
    "slides",
    "markdown",
    "slide-generator",
    "presentation-slides",
    "presentation-maker",
    "presentation-generator",
  ]
icon: "fa-code"
---

When I was preparing technical talks and product demos by markdown-based presentation, I realized that most existing presentation tools were either too limited or too heavy.
I wanted something lightweight, flexible, and developer-friendly, a tool that would let me write slides the same way I write documentation or blog post.

That is how I started creating [Mostage](https://mostage.app/develop.html). It is not just another presentation tool, but a framework for building and customizing web-based slides using **Markdown** and **HTML**.
You can use it directly to create beautiful, interactive presentations, or even build your own tools on top of it. The official **CLI** tool, for example, is powered by the same **Core Library**.

<!--more-->

### Why Mostage?

- **Markdown Support**: Use the same syntax you know from GitHub, documentation, blogs and etc.
- **HTML Support**: Use **HTML** directly for advanced layouts, custom components, or interactivity.
- **Web-Based**: Presentations run smoothly in any browser, no installation needed.
- **Configuration**: Easily configure every aspect of your presentation. Themes, Plugins, Transitions and Layouts are customizable.
- **Theme System**: Mostage includes **built-in themes** and supports easy **custom theme creation**, so you can match your presentation’s style perfectly.
- **Plugin System**: Extend functionality through **plugins**. Use built-in ones or write your own to add animations, dynamic data, or new features.

### The Philosophy is Simple

###### Markdown-First, HTML-Powered:

Use the clean, fast syntax of Markdown for your core content, but break out into HTML anytime you need more power—for complex layouts, animations, or interactive elements.
No new syntax to learn — no limits.

###### Truly Web-Native:

The result is pure, modern HTML, ensuring your presentations work everywhere.
Need to share offline? Export to **PDF**, **PPTX**, or **image formats** with a single command.

### Get Started in Seconds

Here’s how easy it is to start using Mostage via the CLI:

```bash
# Create a new presentation from a template
npx mostage@latest example

# Or start a brand new project
npx mostage@latest new

# Fire up the local development server
npx mostage dev

# Export your slides to any format
npx mostage export
```

- [https://mostage.app/develop](https://mostage.app/develop.html)
- [Demo](https://mostage.app/demo/)
- [GitHub Repository](https://github.com/mostage-app/mostage)
- [NPM](https://www.npmjs.com/package/mostage)

I hope you find this tool useful for your presentations. Feel free to contribute, report issues, or suggest new features. I'm always open to feedback and collaboration.
