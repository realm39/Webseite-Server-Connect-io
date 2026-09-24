# 🪞 nosignups-mirror

**1:1-Sicherungskopie (statischer Mirror) von [nosignups.net](https://nosignups.net/)** – dem Verzeichnis von 268 Open-Source-Tools, die komplett im Browser ohne Anmeldung laufen.

> ⚖️ **Lizenz & Quelle:** Das Original-Projekt ist Open Source unter der **GPL-3.0** (siehe [`LICENSE`](LICENSE)).
> Quellcode & Daten: [`BraveOPotato/FckSignups`](https://github.com/BraveOPotato/FckSignups).
> Alle Rechte am Original liegen beim jeweiligen Autor. Dieses Repo ist ein unveraenderter Mirror der oeffentlich ausgelieferten Dateien.

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

## 🔗 Was bleibt mit dem Original verbunden?

Der Klon ist Datei-fuer-Datei identisch mit dem Original. Zur Laufzeit holt sich die App weiterhin live:

- **Tool-Daten (268 Tools):** `tools.json` aus dem Original-Repo `BraveOPotato/FckSignups`
- **GitHub-Sterne:** direkt von `api.github.com`
- **Formulare** (Tool vorschlagen/melden): an die Cloudflare-Worker des Originalbetreibers

D. h.: Inhalte aktualisieren sich automatisch, wenn das Original aktualisiert wird; Aenderungen/Sperrungen der Originalquellen wirken sich auch hier aus.

## 📦 Stand des Mirrors

Erstellt am **2026-09-24** von `nosignups.net`.
