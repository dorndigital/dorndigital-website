# DornDigital — statische Website

Diese Website besteht aus HTML, CSS und SVG. Es wird kein Build-Tool benötigt.

## Dateien

- `index.html` — Startseite
- `impressum/index.html` — Impressum
- `datenschutz/index.html` — Datenschutzhinweise
- `styles.css` — responsive Gestaltung
- `assets/` — DornDigital-Zeichen und Favicon
- `_headers` — Sicherheits- und Browser-Header für Cloudflare Pages

## Veröffentlichung über GitHub und Cloudflare Pages

1. Den Inhalt dieses Ordners in das Stammverzeichnis eines GitHub-Repositories legen und nach GitHub übertragen.
2. In Cloudflare unter **Workers & Pages → Create application → Pages → Connect to Git** das Repository verbinden.
3. Für die unveränderte statische Website keinen Framework-Preset auswählen. Build command leer lassen und als Build output directory `.` eintragen. Root directory bleibt leer, wenn die Dateien direkt im Repository-Stamm liegen.
4. Den ersten Pages-Deploy abwarten und anschließend unter **Custom domains** `dorndigital.de` hinzufügen. Die dort angezeigten DNS-Einstellungen beim Registrar IONOS eintragen.

Cloudflare kann Deployments bei neuen Commits auf dem verbundenen GitHub-Branch automatisch aktualisieren.

## Vor der Veröffentlichung prüfen

- Ob die angegebene Anschrift und die geschäftliche Situation noch stimmen.
- Ob die Anbieterkennzeichnung und die angegebenen Kontaktwege nach Aufnahme des Geschäftsbetriebs weiterhin vollständig und aktuell sind.
- Ob der Cloudflare-Account Pages verwendet und welche Sicherheits-, Protokoll- und Cookie-Funktionen dort aktiv sind.
- Ob die Datenschutzinformationen zu tatsächlichem Hosting, Domain-/DNS-Konfiguration und etwaigen später ergänzten Funktionen passen.
- Ob sich nach Aufnahme des Geschäftsbetriebs Pflichtangaben wie Rechtsform, Register- oder Umsatzsteuerangaben ändern.

Die Rechtstexte sind auf die geplante statische Konfiguration abgestimmt. Sie ersetzen keine Prüfung der konkreten Konfiguration und der individuellen rechtlichen Pflichten vor dem Livegang.
