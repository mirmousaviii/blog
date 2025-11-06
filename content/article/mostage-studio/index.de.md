---
title: "Mostage Studio: Webbasierte Präsentation"
date: 2025-11-05T19:46:00+02:00
draft: false
categories: ["project"]
tags: ["presentation", "slides", "markdown", "webapp", "frontend", "mostage"]
icon: "fa-code"
---

Vor einigen Wochen habe ich über [Mostage](https://mirmousavi.com/article/mostage/) geschrieben – ein Open-Source-Framework, das ich entwickelt habe, um Präsentationen mit **Markdown** und **HTML** zu erstellen.  
Die Idee war, den Prozess so einfach wie möglich zu gestalten: Folien in Markdown schreiben, bei Bedarf HTML verwenden und alles als saubere, webbasierte Präsentation exportieren.  
Die Kernbibliothek und das CLI-Tool sind auf [GitHub](https://github.com/mostage-app/mostage) und [npm](https://www.npmjs.com/package/mostage) verfügbar.

Nach der Veröffentlichung der ersten Version wollte ich ein Tool entwickeln, mit dem jeder Präsentationen direkt im Browser erstellen und bearbeiten kann – ohne Installation.  
So entstand **[Mostage Studio](https://studio.mostage.app)**.

<!--more-->

### Was ist Mostage Studio?

**Mostage Studio** ist eine moderne Web-App, die auf dem [Mostage Framework](https://github.com/mostage-app/mostage) basiert.  
Sie bietet eine einfache, aufgeräumte Oberfläche, in der man Präsentationen direkt im Browser schreiben, bearbeiten und vorführen kann.  
Es ist keine Installation oder Einrichtung erforderlich – alles läuft online.

Mit **Mostage Studio** kannst du:

- Folien in Markdown schreiben und eine Live-Vorschau sehen
- Zwischen verschiedenen Themes wechseln
- Hintergründe, Übergänge und Layouts anpassen
- Plugins und interaktive Elemente hinzufügen
- Präsentationen direkt aus dem Browser exportieren oder teilen

### Aktuell in Entwicklung

**Mostage Studio** wird ständig weiterentwickelt. Neue Funktionen sind bereits in Arbeit, um Präsentationen noch kreativer und interaktiver zu machen:

- **AI-Powered Creation**: Automatisches Erstellen von Präsentationen mit intelligenten Inhalten und Vorschlägen
- **Live Polling System**: Interaktive Umfragen und Feedbacks in Echtzeit
- **Audience Q&A mit Voting**: Das Publikum kann Fragen stellen und über die besten abstimmen
- **Live Quiz System**: Interaktive Quizze mit sofortigen Ergebnissen
- **Echtzeit-Reaktionen**: Erfassen von Emotionen und Reaktionen des Publikums während der Präsentation
- **Mobile Remote Control**: Steuerung der Präsentation über das Smartphone mit Gesten

All diese Funktionen befinden sich derzeit in Entwicklung und werden nach und nach in den öffentlichen Versionen verfügbar sein.

Wenn du gerne mit Markdown arbeitest oder webbasierte Tools magst, probiere **Mostage Studio** einfach aus und sag mir, was du denkst.  
Dein Feedback hilft, das Projekt weiter zu verbessern.

### Tech Stack

Die App wurde mit **Next.js**, **TypeScript** und **Tailwind CSS** entwickelt und nutzt im Kern die **Mostage Core Library**.  
Sie ist leichtgewichtig, schnell und vollständig Open Source.

- Website: [mostage.app](https://mostage.app)
- Live-Demo: [studio.mostage.app](https://studio.mostage.app)
- Quellcode: [mostage-app/studio](https://github.com/mostage-app/studio)
