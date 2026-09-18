# TrauerGuide Stuttgart

Statische Startversion fuer den TrauerOhr TrauerGuide Stuttgart.

## Dateien

- `index.html` ist die aktuell lauffaehige Seite.
- `.cursor/rules/trauerohr-kompass.mdc` enthaelt die Grundregeln fuer Cursor.
- `CURSOR_START_HERE.md` ist die Startdatei fuer die Weiterarbeit in Cursor.
- `CLOUDFLARE_GITHUB_DEPLOYMENT.md` beschreibt den einfachen GitHub-/Cloudflare-Weg.

## Ziel

Der Stuttgart-Kompass bleibt die Vorlage fuer weitere regionale Kompasse. Das Erscheinungsbild soll ruhig, professionell und nah an TrauerOhr bleiben. Im Mittelpunkt stehen Orientierung, Friedhof TO GO und der Ratgeber.

## Aktueller Stand

- Navigation, Bestatter, Friedhoefe und Ratgeber sind in einer einzelnen HTML-Datei enthalten.
- Der Kostenrechner ist entfernt.
- Sichtbar sind Häfner & Züfle sowie eine Beispielkarte fuer weitere Bestatter-Werbung.
- Die Werbung fuer die Digitale Bestattungsvorsorge steht unten unter den Bestatter-Karten als kleiner Hinweis, nicht als Hauptbanner.
- Der Friedhofsbereich ist Friedhof TO GO: Name, Stadtteil, Adresse, Grabfelder, Lageplan wo vorhanden, Kartenlink.

## GitHub / Cloudflare Pages

Einfachste stabile Variante:

- Framework preset: `None`
- Build command: leer lassen
- Output directory: `/`
- Pages-Projekt: bestehendes Git-Projekt (ein Projekt, nicht zwei)
- Oeffentliche Adresse: `trauerguide.trauerohr.com`

## Wichtige Pflege-Regeln

- Keine sensiblen Personendaten speichern.
- Bestatterdaten regelmaessig pruefen.
- Preise und Gebuehren immer mit Quellenstand und Datum dokumentieren.
- Fuer neue Staedte zuerst Inhalte austauschen, dann Design nur minimal anpassen.
- Keine komplexe Plattform einfuehren, solange eine statische Seite ausreicht.
