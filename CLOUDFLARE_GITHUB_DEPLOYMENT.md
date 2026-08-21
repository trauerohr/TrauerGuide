# GitHub und Cloudflare Pages

## Aktueller technischer Stand

Das Projekt ist eine einfache statische Webseite. Es braucht keinen Build-Schritt.

## GitHub

Empfohlene Struktur im Repository:

```text
/
  index.html
  README.md
  CURSOR_START_HERE.md
  CLOUDFLARE_GITHUB_DEPLOYMENT.md
  friedhof-bildquellen-und-todos.md
  friedhof-bildrecherche-stuttgart.md
  assets/
  prompts/
  .cursor/
```

## Cloudflare Pages

Einstellungen:

- Pages-Projektname: `bestatter-kompass-stuttgart`
- Framework preset: `None`
- Build command: leer lassen
- Output directory: `/`

GitHub Actions (`.github/workflows/deploy.yml`) deployt in genau dieses vorhandene Projekt. Benoetigte Repo-Secrets:

- `CLOUDFLARE_API_TOKEN` (Account-Berechtigung: Cloudflare Pages Edit)
- `CLOUDFLARE_ACCOUNT_ID`

## Subdomain

Ziel:

`bestatter-kompass-stuttgart.trauerohr.com`

Wenn Cloudflare Pages verbunden ist:

1. GitHub-Repository verbinden.
2. Projekt deployen.
3. Custom Domain in Cloudflare Pages hinzufuegen.
4. DNS/Validierung nach Cloudflare-Anweisung setzen.

## Wichtige Veroeffentlichungsregel

Vor dem Livegang pruefen:

- Sind alle Bilder lokal vorhanden?
- Ist bei jedem Bild Quelle/Freigabe dokumentiert?
- Sind unsichere Bilder nicht eingebunden?
- Funktioniert die Bildvergroesserung?
- Ist die Vorsorge-Werbung unten und nicht dominant?
- Stimmen Impressum-/Hauptseitenlinks?
