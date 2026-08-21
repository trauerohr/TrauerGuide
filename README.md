# Bestatter-Kompass Stuttgart

Statische Startversion fuer den TrauerOhr Bestatter-Kompass Stuttgart.

## Dateien

- `index.html` ist die aktuell lauffaehige Seite.
- `.cursor/rules/trauerohr-kompass.mdc` enthaelt die Grundregeln fuer Cursor.
- `CURSOR_START_HERE.md` ist die Startdatei fuer die Weiterarbeit in Cursor.
- `CLOUDFLARE_GITHUB_DEPLOYMENT.md` beschreibt den einfachen GitHub-/Cloudflare-Weg.

## Ziel

Der Stuttgart-Kompass bleibt die Vorlage fuer weitere regionale Kompasse. Das Erscheinungsbild soll ruhig, professionell und nah an TrauerOhr bleiben. Im Mittelpunkt stehen die Bestatter-Suche, der Kostenrechner und eine schlichte Friedhofsuebersicht.

## Aktueller Stand

- Navigation, Bestatter-Suche, Kostenrechner, Friedhoefe und Ratgeber sind in einer einzelnen HTML-Datei enthalten.
- Die Werbung fuer die Digitale Bestattungsvorsorge steht unten unter den Bestatter-Karten als kleiner Hinweis, nicht als Hauptbanner.
- Der Friedhofsbereich ist eine textbasierte Uebersicht (Name, Stadtteil, Adresse, kurze Beschreibung, Grabarten, Kartenlink).
- Lageplaene und Grabfeldbilder sind in dieser Version nicht oeffentlich eingebunden.

## Zurueckgestellt: Friedhofs To Go

Friedhofsbilder und Grabfeldbilder wurden für eine spätere separate Friedhofs To Go App zurückgestellt.

Die vorhandenen Dateien unter `assets/friedhoefe/` bleiben erhalten, werden hier aber nicht angezeigt.

## GitHub / Cloudflare Pages

Einfachste stabile Variante:

- Framework preset: `None`
- Build command: leer lassen
- Output directory: `/`
- Pages-Projekt: `bestatter-kompass-stuttgart`
- Subdomain: `bestatter-kompass-stuttgart.trauerohr.com`

## Wichtige Pflege-Regeln

- Keine sensiblen Personendaten speichern.
- Bestatterdaten regelmaessig pruefen.
- Preise und Gebuehren immer mit Quellenstand und Datum dokumentieren.
- Fuer neue Staedte zuerst Inhalte austauschen, dann Design nur minimal anpassen.
- Keine komplexe Plattform einfuehren, solange eine statische Seite ausreicht.
