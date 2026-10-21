# Be you. – Website

Website für **Be you. Fußpflege & Podologin i. A.** (Désirée Brunken, Wilhelmshaven)
Domain: https://www.desires-wellness-ammeer.de

## Hinweise für den Server

- Reine statische Website (HTML/CSS, etwas JavaScript) – kein PHP, keine
  Datenbank, kein Build-Schritt nötig.
- Einfach den gesamten Inhalt dieses Ordners in das Web-Verzeichnis
  (Document Root) der Domain kopieren. Startseite ist `index.html`.
- Bitte HTTPS aktivieren (z. B. Let's Encrypt) und `desires-wellness-ammeer.de`
  auf `https://www.desires-wellness-ammeer.de` weiterleiten.
- Die Datei `CNAME` wird nur für GitHub Pages gebraucht und kann auf dem
  eigenen Server ignoriert werden.
- Achtung E‑Mail: Die Adresse `info@desires-wellness-ammeer.de` läuft über
  dieselbe Domain – MX‑Einträge bitte nicht verändern.

## Externe Dienste

Falls auf dem Server eine Content-Security-Policy gesetzt ist, müssen diese
Quellen erlaubt sein:

| Zweck | Domains |
|---|---|
| Schriften (Google Fonts) | `fonts.googleapis.com`, `fonts.gstatic.com` |
| Online-Buchung (Salonized-Widget, lädt erst nach Klick) | `static-widget.salonized.com`, `*.salonized.com` (Skript und iframe) |

## Vorher/Nachher-Bilder einfügen

Bilder als JPG in `assets/img/` ablegen – ohne HTML zu ändern:

| Dateien | Behandlung |
|---|---|
| `vorher-1.jpg` / `nachher-1.jpg` | Hornhaut & Schrunden an der Ferse |
| `vorher-2.jpg` / `nachher-2.jpg` | Hühnerauge am Zeh |
| `vorher-3.jpg` / `nachher-3.jpg` | Hornhaut zwischen den Zehen |

Bilder austauschen = Datei mit gleichem Namen ersetzen. Für ein weiteres Paar
in `index.html` einen `<figure class="ba">`-Block kopieren und die Nummer
anpassen. Fehlt ein Bild, erscheint automatisch der Platzhalter. Ideal: quadratisch,
ca. 1000×1000 Pixel, Vorher und Nachher aus gleichem Winkel.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite (Leistungen & Preise, Vorher/Nachher, Über mich, Online-Buchung, Kontakt) |
| `impressum.html`, `datenschutz.html` | Rechtstexte |
| `style.css` | Gestaltung |
| `assets/` | Logo, Favicon, Bilder |
| `robots.txt`, `sitemap.xml` | für Suchmaschinen |
