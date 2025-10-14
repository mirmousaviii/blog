---
title: "Mostage: Een Framework voor Webpresentaties"
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

Toen ik technische presentaties en productdemo’s aan het voorbereiden was, merkte ik dat de meeste bestaande presentatietools te beperkt of te zwaar waren.  
Ik wilde iets lichts, flexibel en ontwikkeld voor developers – een manier om slides te schrijven zoals ik documentatie of blogposts schrijf.

Zo is **[Mostage](https://mo.js.org)** ontstaan.  
Mostage is niet zomaar een tool, maar een **framework** om webgebaseerde presentaties te maken en aan te passen met **Markdown** en **HTML**.  
Je kunt het direct gebruiken om mooie, interactieve slides te bouwen, of je eigen tools erop baseren.  
De officiële **CLI-tool** is bijvoorbeeld gebouwd met dezelfde **Core Library**.

<!--more-->

### Waarom Mostage?

- **Markdown-ondersteuning**: Gebruik de bekende Markdown-syntax die je al kent van GitHub of documentatie.
- **HTML-ondersteuning**: Voeg HTML toe wanneer je meer controle wilt, voor complexe layouts of interactieve elementen.
- **Webgebaseerd**: Je presentatie draait in elke moderne browser, zonder installatie.
- **Configuratie**: Alles is aanpasbaar – thema’s, plugins, overgangen en layouts.
- **Thema-systeem**: Inclusief ingebouwde thema’s en eenvoudig eigen thema’s te maken.
- **Plugin-systeem**: Breid de functionaliteit uit met bestaande of eigen plugins voor animaties, dynamische data of nieuwe features.

### De filosofie is eenvoudig

###### Markdown-First, HTML-Powered

Schrijf je inhoud in snelle, schone Markdown-syntax, en gebruik HTML wanneer je meer mogelijkheden nodig hebt.  
Geen nieuwe syntax om te leren en geen beperkingen.

###### Volledig Web-Native

De output is modern HTML dat overal werkt.  
Wil je offline delen? Exporteer eenvoudig naar **PDF**, **PPTX** of **afbeeldingen** met één enkel commando.

### Binnen enkele seconden aan de slag

Zo eenvoudig kun je beginnen met de Mostage CLI:

```bash
# Maak een nieuwe presentatie met een voorbeeldtemplate
npx mostage@latest example

# Of start een volledig nieuw project
npx mostage@latest new

# Start de lokale ontwikkelserver
npx mostage dev

# Exporteer je presentatie
npx mostage export
```

- [mo.js.org](https://mo.js.org/)
- [Demo](https://mo.js.org/demo/)
- [GitHub Repository](https://github.com/mirmousaviii/mostage)
- [NPM](https://www.npmjs.com/package/mostage)

Ik hoop dat Mostage handig is voor jouw presentaties.
Voel je vrij om bij te dragen, fouten te melden of nieuwe ideeën te delen.
Jouw feedback helpt dit project te verbeteren.
