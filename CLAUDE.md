# Claude-Gedächtnis (privat)

Dieses Repo ist das zentrale, private Gedächtnis für alle Claude-Sessions (Desktop, Web, Mobile, Cloud).
Viele Quelldateien liegen nur lokal auf dem Mac. Alles, was eine Session zum Weiterarbeiten braucht, steht deshalb hier.

## Regeln für Claude

1. **Zuerst lesen:** Zu Beginn jeder Session `memory/global.md` lesen, bei Projektbezug zusätzlich `memory/projekte/<projekt>.md`. Erst bei fehlendem Kontext nachfragen.
2. **Aktueller Stand statt Protokoll:** Veraltetes überschreiben, keine Session-Chroniken anlegen.
3. **Richtig einsortieren:** Projektübergreifendes (Arbeitsweise, Tools, Standards) nach `memory/global.md`, Projektspezifisches nach `memory/projekte/<projekt>.md`.
4. **Lokale Dateien destillieren:** Wird eine lokale Datei gelesen, ihre Essenz (Inhalt, Kernzahlen, Erkenntnisse) mit Dateiname und Pfad in `memory/dateien/index.md` oder im Projektfile festhalten.
5. **Umsetzungsreif schreiben:** So, dass eine neue Session (auch mit günstigerem Modell) direkt weiterarbeiten kann.
6. **Nie speichern:** Zugangsdaten, API-Keys, Passwörter, Tokens sowie Rohdaten, die per API oder Connector abrufbar sind.
7. **Proaktiv sichern:** Nach wichtigen Entscheidungen und am Ende längerer Sessions den Stand aktualisieren, committen und pushen.
8. **Stil:** Deutsch, kurz aber vollständig. Statt "—" oder "–" immer "-" verwenden.

## Struktur

| Pfad | Inhalt |
|---|---|
| `memory/global.md` | Arbeitsweise, Konten, Tools, Standards (projektübergreifend) |
| `memory/projekte/` | Eine Datei pro Projekt/Kunde, Vorlage: `_vorlage.md` |
| `memory/projekte/README.md` | Index aller Projekte mit Einzeilern |
| `memory/dateien/index.md` | Destillate lokaler Dateien mit Pfad |
