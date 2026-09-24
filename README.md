## 📁 Inhalt

| Datei | Zweck |
|---|---|
| `index.html` | Einstiegsseite (SPA-Shell) |
| `assets/index-BCjVynyw.js` | komplettes App-Bundle (React/Vite-Build) |
| `assets/index-CTs05sCP.css` | komplette Styles |
| `favicon.ico` | Icon |
| `fonts/` | Inter & Space Grotesk (self-hosted, Variable Fonts) |
| `robots.txt` | Original-Robots-Datei |
| `LICENSE` | GPL-3.0 des Original-Projekts |

## ▶️ Lokal starten

Die Seite ist eine Single-Page-App und laed ihre Daten zur Laufzeit nach – daher **nicht** per Doppelklick auf `index.html`, sondern ueber einen kleinen Webserver oeffnen:

```bash
cd nosignups-mirror
python3 -m http.server 8080
# dann im Browser: http://localhost:8080
```

Jeder andere statische Server geht auch (`npx serve`, nginx, GitHub Pages, ...).

- **Tool-Daten (268 Tools):** `tools.json` aus dem Original-Repo `BraveOPotato/FckSignups`
- **GitHub-Sterne:** direkt von `api.github.com`
- **Formulare** (Tool vorschlagen/melden): an die Cloudflare-Worker des Originalbetreibers
