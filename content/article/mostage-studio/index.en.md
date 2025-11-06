---
title: "Mostage Studio: Web-Based Presentation"
date: 2025-11-05T19:46:00+02:00
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
    "webapp",
    "frontend",
    "mostage",
  ]
icon: "fa-code"
---

A few weeks ago, I wrote about [Mostage](https://mirmousavi.com/article/mostage/), an open-source framework for creating presentations with **Markdown** and **HTML**.  
The idea was to keep things simple: write slides in Markdown, add HTML when needed, and export everything as a clean, web-based presentation.  
The core library and CLI are available on [GitHub](https://github.com/mostage-app/mostage) and [npm](https://www.npmjs.com/package/mostage).

After finishing the library, I wanted to make it easier for anyone to build and share slides without installing anything.  
That idea became the starting point for [Mostage Studio](https://studio.mostage.app).

<!--more-->

### What is Mostage Studio?

**Mostage Studio** is a web app built on top of the [Mostage framework](https://github.com/mostage-app/mostage).  
It provides a simple, clean interface where you can write, edit, and present slides directly in the browser.  
No setup or installation is required — everything runs online.

With **Mostage Studio**, you can:

- Write slides in Markdown and see live previews
- Instantly switch between different themes
- Customize backgrounds, transitions, and layouts
- Add plugins and interactive elements
- Export or share your presentation directly from the browser

### Currently in Development

Mostage Studio is growing quickly, and several new features are being developed to make presentations creative and interactive:

- **AI-Powered Creation** lets you generate complete presentations with intelligent content suggestions.
- **Live Polling System** enables interactive polls and surveys for real-time audience feedback.
- **Audience Q&A with Voting** allows participants to ask questions and vote for their favorites.
- **Live Quiz System** supports interactive quizzes with instant results.
- **Real-time Reactions** captures audience feedback and emotions during your talk.
- **Mobile Remote Control** lets you control slides from your phone with simple gestures.

These features are in progress and will be available in an upcoming public release.

If you enjoy creating content with Markdown or working with modern web tools, give it a try and share your feedback.  
I’d love to hear what you think.

### Tech Stack

The app is developed with **Next.js**, **TypeScript**, and **Tailwind CSS**, powered by the **Mostage Core Library**.  
It is lightweight, fast, and completely open-source.

- Website: [mostage.app](https://mostage.app)
- Try it: [studio.mostage.app](https://studio.mostage.app)
- GitHub: [mostage-app/studio](https://github.com/mostage-app/studio)
