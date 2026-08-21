# Bestatter-Kompass Stuttgart

Statische Startversion fuer den TrauerOhr Bestatter-Kompass Stuttgart.

## Dateien

- `index.html` ist die aktuell lauffaehige Seite.
- `.cursor/rules/trauerohr-kompass.mdc` enthaelt die Grundregeln fuer Cursor.
- `.cursor/rules/bildrechte-friedhoefe.mdc` enthaelt verbindliche Regeln fuer Bildrechte.
- `CURSOR_START_HERE.md` ist die Startdatei fuer die Weiterarbeit in Cursor.
- `CLOUDFLARE_GITHUB_DEPLOYMENT.md` beschreibt den einfachen GitHub-/Cloudflare-Weg.
- `prompts/cursor-masterprompt-kompasse.md` ist der Masterprompt fuer weitere Kompasse.
- `prompts/cursor-prompts.md` enthaelt wiederverwendbare Prompts fuer neue Kompasse.
- `friedhof-bildquellen-und-todos.md` dokumentiert Bildstatus, Quellen und offene Grabfeldfotos.
- `friedhof-bildrecherche-stuttgart.md` sammelt konkrete Recherchequellen fuer fehlende Friedhofsbilder.
- `assets/friedhoefe/lageplaene-clean/` enthaelt die bereinigten, aktiv eingebundenen Lageplanbilder.
- `assets/friedhoefe/lageplaene/` enthaelt fruehe Arbeitszuschnitte und sollte nicht direkt in der Seite verwendet werden.

## Ziel

Der Stuttgart-Kompass bleibt die Vorlage fuer weitere regionale Kompasse. Das Erscheinungsbild soll ruhig, professionell und nah an TrauerOhr bleiben. Inhalte duerfen je Stadt angepasst werden, die Struktur soll aber stabil und wartbar bleiben.

## Aktueller Stand

- Navigation, Bestatter-Suche, Kostenrechner, Friedhoefe und Ratgeber sind in einer einzelnen HTML-Datei enthalten.
- Die Werbung fuer die Digitale Bestattungsvorsorge steht unten unter den Bestatter-Karten als kleiner Hinweis, nicht als Hauptbanner.
- Die Seite ist fuer GitHub und Cloudflare Pages als einfache statische Seite vorbereitet.
- Der Friedhofsbereich wurde auf 51 Stuttgart-Eintraege aus der Arbeits-PDF erweitert.
- 19 bereinigte Lageplanbilder wurden lokal eingebunden; fehlende Grabfeldfotos sind sichtbar als offen markiert.
- Vorhandene Lageplaene koennen im Friedhofsbereich angeklickt und vergroessert werden.

## GitHub / Cloudflare Pages

Einfachste stabile Variante:

1. Neues GitHub-Repository fuer den Kompass anlegen.
2. Diese Dateien in das Repository legen.
3. Bei Cloudflare Pages ein neues Projekt aus dem GitHub-Repository erstellen.
4. Build-Einstellungen:
   - Framework preset: `None`
   - Build command: leer lassen
   - Output directory: `/`
5. Subdomain in Cloudflare auf das Pages-Projekt zeigen lassen.

## Wichtige Pflege-Regeln

- Keine sensiblen Personendaten speichern.
- Bestatterdaten regelmaessig pruefen.
- Preise und Gebuehren immer mit Quellenstand und Datum dokumentieren.
- Fuer neue Staedte zuerst Inhalte austauschen, dann Design nur minimal anpassen.
- Keine komplexe Plattform einfuehren, solange eine statische Seite ausreicht.
