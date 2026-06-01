# Osobní prezentace — Ing. Rostislav Jirák

Statický one-page web (HTML / CSS / vanilla JS, bez backendu). Tmavý glassmorphism design,
interaktivní pozadí a animace. Hostovatelný na **GitHub Pages**, Netlify nebo jakémkoli
statickém hostingu — žádný server, databáze ani build krok není potřeba.

## Struktura

```
index.html        # celá stránka (HTML + CSS + JS v jednom souboru)
assets/           # náhledy projektů (optimalizované JPG)
.nojekyll         # vypíná Jekyll zpracování na GitHub Pages
```

## Lokální spuštění

Stačí otevřít `index.html` v prohlížeči, nebo spustit jednoduchý server:

```bash
python -m http.server 8000
# pak otevři http://localhost:8000
```

## Nasazení na GitHub Pages

1. Nahraj obsah složky do repozitáře na GitHubu.
2. Settings → Pages → Source: `Deploy from a branch`, branch `main`, složka `/ (root)`.
3. Web bude dostupný na `https://<username>.github.io/<repo>/`.
