# BCHT.CH

Persönliche Digital Identity und Digital Card von Stefan Berchtold. Eine reduzierte öffentliche Visitenkarte mit dunkler Gestaltung, feinen Linien und einem dezenten Netzwerk im Hintergrund.

## Bereiche

- **IDENTITY** – Name, Switzerland und die Themenfelder Aviation, Technology, Digital Systems und Automation.
- **CARD** – digitale Karte teilen, Website-Link kopieren oder eine vCard speichern. Die vCard enthält nur Name und Website-URL sowie die notwendigen Formatfelder.
- **PRIVACY** – bewusste Begrenzung der öffentlich sichtbaren Daten.
- **INFO** – minimale Angaben zur digitalen Identität.

## Privacy by Design

Die Website-Anwendung verwendet keine Analytics, Tracking-Skripte, Site-Cookies, externen Fonts oder Formulare und benötigt kein Application-Backend. Es wird keine E-Mail-Adresse öffentlich angezeigt. Diese Aussagen beziehen sich auf die Anwendung, nicht auf mögliche Logs der Hosting-Infrastruktur.

## Technik und Bedienung

Statische Website auf GitHub Pages unter https://bcht.ch, mit Vanilla HTML/CSS/JavaScript und ohne Build-Schritt oder externe Libraries. CSS und JavaScript bleiben vorerst in `index.html`.

Das responsive Fullscreen-Menü unterstützt Tastatur und Touch, Escape zum Schliessen, sichtbaren Tastaturfokus und Fokus-Rückgabe. `prefers-reduced-motion` reduziert Animationen und stellt das Netzwerk statisch dar.

SHARE CARD verwendet die native Web Share API, sofern verfügbar; andernfalls wird der Website-Link kopiert. COPY LINK hat einen Kopier-Fallback und bietet bei blockierter Zwischenablage eine manuelle Auswahl.

## Lokal testen

Das vollständige Repository herunterladen und entpacken, damit `assets/favicon.svg` und `assets/stefan-berchtold.vcf` neben `index.html` verfügbar bleiben. Die HTML-Datei lässt sich direkt öffnen; für die nativen Browserfunktionen empfiehlt sich ein lokaler Server auf localhost oder die HTTPS-Website. Unterstützung für Teilen und vCard-Import hängt vom Browser und Gerät ab.
