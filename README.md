# Die große Verschiebung – Arbeitsmarkt Deutschland 2025–2035

Interaktive Analyse darüber, wie KI-Weltmodelle, Agentensysteme und Robotik den deutschen Arbeitsmarkt in den nächsten zehn Jahren transformieren – und was das für die Gesellschaft bedeutet.

![Vorschau](Gemini_Generated_Image_r7oonbr7oonbr7oo.png)

## Inhalt

**Sektorenanalyse** – Prognosen für 18 Wirtschaftssektoren (von Industrie über Verwaltung bis Kultur), jeweils mit aktuellen Beschäftigtenzahlen, 2035-Prognosen, Veränderungsraten und einer Einordnung der Arbeitsplatzstabilität. Interaktive Visualisierung mit Filter- und Sortierfunktionen.

**Gesellschaftliche Analyse** – Sechs essayistische Kapitel:
- Der Bruch im Gesellschaftsvertrag
- Demografie und KI: Zwei Krisen, die sich nicht aufheben
- Die Generationenfrage
- Der Mittelstand und die Mitte der Gesellschaft
- Arbeit, Identität und der fehlende Plan B
- Was realistisch passieren wird

## AI-Demo-Projekt

Dieses gesamte Projekt wurde als Demonstration erstellt, um zu zeigen, was mit aktuellen KI-Werkzeugen möglich ist. Sämtliche Bestandteile sind KI-gestützt entstanden:

- **Recherche & Datenaufbereitung** – Synthese aus Destatis, IAB, OECD, McKinsey, Bundesagentur für Arbeit und World Economic Forum
- **Content-Erzeugung** – Sektorenanalysen, Prognosen und gesellschaftliche Essays
- **Code** – Interaktive Single-Page-App (React, JSX, Babel) mit Visualisierungen, Filtern und Animationen
- **Bild** – OG-Preview-Image (Gemini)
- **Deployment** – GitHub Pages via GitHub Actions

Erstellt im Dialog zwischen Mensch und KI (Claude, Anthropic – Modell Claude Opus 4.6).

## Technik

Standalone HTML-Datei ohne Build-Prozess:
- React 18 + Babel (CDN)
- Crimson Text, DM Sans, JetBrains Mono (Google Fonts)
- Responsive Design (Mobile-optimiert)

## Deployment

Die Seite wird automatisch über GitHub Pages deployt, wenn Änderungen auf den `main`-Branch gepusht werden.

### Manuelles Deployment

1. Actions-Tab öffnen
2. Workflow "Deploy to GitHub Pages" auswählen
3. "Run workflow" klicken

### Lokal anschauen

Einfach `index.html` im Browser öffnen.

## Hinweis

Alle Projektionen sind KI-gestützte Schätzungen und keine exakten Vorhersagen. Unsicherheitsmarge: ±15%. Stand: Februar 2026.
