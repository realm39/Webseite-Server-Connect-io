# ⚡ Nexus-AI

**Nexus-AI – Open Source Tools. Zero Bullsh\*t.**

Ein kuratiertes Verzeichnis von **268 Open-Source-Tools**, die komplett im Browser laufen – ohne Anmeldung, ohne Installation.

🌐 **Live:** https://realm39.github.io/Webseite-Server-Connect-io/

## 📁 Inhalt

| Datei | Zweck |
|---|---|
| `index.html` | Einstiegsseite (SPA-Shell) |
| `assets/index-BCjVynyw.js` | komplettes App-Bundle (React/Vite-Build) |
| `assets/index-CTs05sCP.css` | komplette Styles |
| `favicon.ico` | Icon |
| `fonts/` | Inter & Space Grotesk (self-hosted, Variable Fonts) |
| `robots.txt` | Robots-Datei |
| `LICENSE` | GPL-3.0 |

## ▶️ Lokal starten

```bash
python3 -m http.server 8080
# dann im Browser: http://localhost:8080
```

## 🔗 Datenquellen zur Laufzeit

Die App laed zur Laufzeit live nach:

- **Tool-Daten (268 Tools):** `tools.json` aus einem externen Open-Source-Datensatz
- **GitHub-Sterne:** direkt von `api.github.com`

## ⚖️ Lizenz & Credits

Nexus-AI steht unter der **GPL-3.0** (siehe [`LICENSE`](LICENSE)) und basiert auf einem Open-Source-Verzeichnisprojekt (Quellcode & Daten: `github.com/BraveOPotato/FckSignups`).

Stand: 2026-09-24
