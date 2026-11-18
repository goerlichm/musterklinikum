# Musterklinikum

23 statische HTML-Seiten für eine fiktive Klinik als RAG-Demo, ohne Build-Schritt. Die Website-Dateien liegen in `public/`; das gemeinsame Stylesheet ist `public/styles.css`.

## Lokal ansehen

Voraussetzungen: Node.js mit npm und Python 3.

```powershell
npm run dev
```

Danach http://localhost:5173 im Browser öffnen. Mit Strg+C wird der Server beendet. Nach Änderungen die Browserseite neu laden.

## Vorhandene Seiten einfügen

HTML-Dateien und zugehörige Ressourcen nach `public/` kopieren. Die Startseite heißt `index.html`. Relative Verweise auf CSS, JavaScript und Bilder beibehalten.

## Nach GitHub hochladen

```powershell
git add .
git commit -m "Statische Webseiten hinzufügen"
git push -u origin HEAD
```

Repository: https://github.com/goerlichm/musterklinikum

Ein Git-Push lädt den Quellcode hoch. Eine öffentliche Website über GitHub Pages ist damit noch nicht eingerichtet.

Die Sitemap in `public/sitemap.xml` enthält noch `https://IHRE-DOMAIN/` als Platzhalter. Sobald eine Hosting-Adresse feststeht, muss diese Basis-URL ersetzt werden. Weitere Hinweise zu den Demo-Inhalten stehen in `public/README.md`.
