# Schulnoten · GitHub-Pages-Click-Dummy

Diese Dateien enthalten **ausschließlich fiktive Beispieldaten**.
Die Website ist ein öffentlicher Design- und Interaktionsprototyp.
**Keine realen Schülerdaten eingeben.** Keine SQLCipher-Verschlüsselung, keine echten Backups.

- `index.html`: Voll interaktive Vorschau (Desktop, iPad und iPhone), mit JavaScript.
- `iphone.html`: Vereinfachte Vorschau ohne JavaScript, falls die interaktive Variante nicht startet.
- `.nojekyll`: Deaktiviert unnötige Jekyll-Verarbeitung bei GitHub Pages.

## Ohne Build und ohne Server veröffentlichen

1. Auf https://github.com/new ein **öffentliches** Repository `schulnoten-demo` anlegen.
2. Die Dateien `index.html`, `iphone.html` und `.nojekyll` in den Hauptordner des
   Repositorys hochladen und committen. Nicht die ZIP-Datei selbst hochladen.
3. Auf GitHub unter **Settings → Pages** im Bereich **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/(root)`
   - `Save`
4. Nach erfolgreicher Bereitstellung in **Settings → Pages** die tatsächliche
   Website-Adresse öffnen und auf iPhone/iPad testen.

Die URL eines gewöhnlichen Projekt-Repositorys ist üblicherweise:
`https://GITHUB-BENUTZERNAME.github.io/schulnoten-demo/`.

Die Website ist öffentlich zugänglich. Keine Zugangskontrolle!
GitHub Pages ist **nur für die fiktive Demo**, nicht für produktive Schülerdaten.

## Besonderheiten

Die interaktive Demo speichert simulierte Änderungen gegebenenfalls im
`localStorage` des jeweiligen Browsers. Die Daten werden nicht mit anderen
Besuchern synchronisiert. Die iPhone-Fallback-Datei speichert keine Änderungen.

Alle Fonts und Skripte sind in den HTML-Dateien integriert.
Es werden keine externen Ressourcen oder APIs benötigt.

## Spätere Aktualisierung

Neue HTML-Dateien an gleicher Stelle hochladen und committen; GitHub Pages
veröffentlicht die geänderten Inhalte wieder unter derselben Adresse.
