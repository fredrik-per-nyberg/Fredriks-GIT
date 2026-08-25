# Fredriks Snake 🐍

Ett Snake-spel byggt för iPhone (och andra touchskärmar) — helt i en enda HTML-fil, utan beroenden.

**Spela här:** https://fredrik-per-nyberg.github.io/Fredriks-GIT/

## Funktioner

- **Touchkontroll** — svep i valfri riktning på spelplanen, eller använd riktningsknapparna under planen. Piltangenter/WASD fungerar på dator.
- **Ormen växer** för varje frukt den äter (10 poäng styck), och farten ökar med längden.
- **Highscore-lista** — topp 10 sparas i webbläsaren (localStorage) med namn, ormskal och datum. Slår du dig in på listan får du skriva in ditt namn.
- **Välj utseende** — åtta ormskal: Smaragd, Eld, Is, Neon, Guld, Regnbåge, Spöke och Giftig. Valet sparas till nästa gång.
- **Paus** med knappen eller `P`. Spelet pausas automatiskt om du lämnar fliken.
- Anpassad för iPhone: säkra zoner (notch), ingen zoom vid dubbeltryck, vibration vid mat, och stöd för "Lägg till på hemskärmen" så det körs i fullskärm som en app.

## Lägg till på hemskärmen (iPhone)

1. Öppna länken ovan i Safari.
2. Tryck på Dela-knappen ▸ **Lägg till på hemskärmen**.
3. Starta spelet från ikonen — då körs det utan adressfält.

## Filer

- `index.html` — spelet (allt i en fil: HTML, CSS och JavaScript).
- `snake.html` — den ursprungliga tangentbordsversionen, sparad som den var.
