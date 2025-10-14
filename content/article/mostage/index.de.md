---
title: "Mostage: Ein Präsentations-Framework"
date: 2025-10-14T19:59:06+02:00
draft: false
categories: ["project"]
tags:
  [
    "presentation",
    "slides",
    "markdown",
    "slide-generator",
    "presentation-framework",
    "presentation-tool",
  ]
icon: "fa-code"
---

Als ich technische Vorträge und Produktdemos vorbereitete, fiel mir auf, dass die meisten bestehenden Präsentationstools entweder zu eingeschränkt oder zu überladen waren.  
Ich wollte etwas Leichtes, Flexibles und Entwicklerfreundliches – ein Werkzeug, mit dem ich Folien so einfach schreiben kann wie Dokumentationen oder Blogposts.

So entstand **[Mostage](https://mo.js.org)**.  
Mostage ist nicht nur ein weiteres Präsentationstool, sondern ein **Framework** für das Erstellen und Anpassen von webbasierten Folien mit **Markdown** und **HTML**.  
Du kannst es direkt verwenden, um schöne, interaktive Präsentationen zu erstellen, oder eigene Tools darauf aufbauen.  
Das offizielle **CLI-Tool** basiert ebenfalls auf der gleichen **Core Library**.

<!--more-->

### Warum Mostage?

- **Markdown-Unterstützung**: Verwende die vertraute Syntax aus GitHub, Dokumentationen oder Blogs.
- **HTML-Unterstützung**: Nutze HTML direkt für komplexe Layouts, benutzerdefinierte Komponenten oder Interaktivität.
- **Webbasiert**: Präsentationen laufen reibungslos in jedem modernen Browser – keine Installation erforderlich.
- **Konfigurierbar**: Passe alles an – Themes, Plugins, Übergänge und Layouts.
- **Theme-System**: Enthält integrierte Themes und ermöglicht es dir, eigene Themes einfach zu erstellen.
- **Plugin-System**: Erweitere die Funktionalität mit Plugins. Verwende vorhandene oder entwickle eigene für Animationen, dynamische Inhalte oder neue Features.

### Die Philosophie ist einfach

###### Markdown-First, HTML-Powered

Schreibe den Kerninhalt mit der schnellen und klaren Markdown-Syntax, und verwende HTML, wenn du mehr Kontrolle brauchst – für komplexe Layouts, Animationen oder interaktive Elemente.  
Keine neue Syntax, keine Grenzen.

###### Vollständig Web-Nativ

Das Ergebnis ist modernes, sauberes HTML, das überall funktioniert.  
Wenn du offline teilen möchtest, kannst du deine Präsentation mit nur einem Befehl als **PDF**, **PPTX** oder **Bilddatei** exportieren.

### In wenigen Sekunden loslegen

So einfach ist der Einstieg mit dem Mostage CLI:

```bash
# Neue Präsentation aus Vorlage erstellen
npx mostage@latest example

# Oder ein komplett neues Projekt starten
npx mostage@latest new

# Lokalen Entwicklungsserver starten
npx mostage dev

# Präsentation exportieren
npx mostage export
```

- [mo.js.org](https://mo.js.org/)
- [Demo](https://mo.js.org/demo/)
- [GitHub Repository](https://github.com/mirmousaviii/mostage)
- [NPM](https://www.npmjs.com/package/mostage)

Ich hoffe, Mostage hilft dir beim Erstellen deiner nächsten Präsentation.
Feedback, Fehlerberichte oder Vorschläge sind immer willkommen – dein Input trägt zum Wachstum dieses Projekts bei.
