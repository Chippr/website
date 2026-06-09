# Chippr website

Statische website (HTML/CSS) voor Chippr. Geen build-stap nodig.

## Structuur

```
index.html              startpagina
cases/
  orbisk.html
  beyco.html
  fullcharge.html
assets/
  orbisk.png            vervang door de echte afbeeldingen
  beyco.png
  fullcharge.png
```

De afbeeldingen in `assets/` zijn placeholders. Vervang ze door de echte
afbeeldingen van chippr.dev (zelfde bestandsnamen aanhouden).

## Lokaal bekijken

Open `index.html` in je browser, of start een simpele server:

```
python3 -m http.server 8000
```

Ga daarna naar http://localhost:8000

## Deployen via GitHub Pages

Zie de stappen in het gesprek of in de instructies hieronder.
