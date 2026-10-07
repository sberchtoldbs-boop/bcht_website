# BCHT · V0.1

Minimalistische Landingpage für bcht.ch. Vanilla HTML/CSS/JavaScript ohne Build, externe Fonts, Tracking oder Netzwerkabhängigkeiten.

## Vorschau

`index.html` direkt im Browser öffnen. Alternativ im Projektordner `python3 -m http.server 8000` starten und http://localhost:8000 öffnen.

CSS und JavaScript sind für diese erste portable Version in index.html enthalten. assets/favicon.svg ist das lokale Icon. Der Canvas zeichnet ein dezentes perspektivisches Netzwerk mit 30 FPS, maximal doppelter Pixeldichte, Pause bei unsichtbarem Tab und statischer Darstellung bei prefers-reduced-motion. Ohne JavaScript bleibt die vollständige Identität sichtbar.

## Design

BCHT / BERCHTOLD · CH / Private domain. Die Koordinaten 46.8° N / 8.2° E sind eine grobe Schweiz-Referenz, keine Wohnadresse. Keine Navigation oder Kontaktinformationen.

## Stand und nächste Schritte

V0.1 ist ein lokaler Entwurf, noch nicht veröffentlicht. Das ursprüngliche Bildmockup war im Umsetzungschat nicht verfügbar; diese Version basiert auf dem bestätigten Designbrief. Desktop- und Mobilansicht müssen vor Freigabe visuell geprüft werden.

Nach der Designfreigabe: GitHub-Repository und Branch/PR-Workflow einrichten; GitHub Pages konfigurieren. Erst bei funktionierendem Hosting Custom Domain und Web-DNS verbinden. CNAME und kanonische/OG-URL erst beim tatsächlichen Deployment ergänzen. Ein OG-Vorschaubild folgt nach Designfreigabe.

## DNS-Randbedingung

Hostpoint bleibt Registrar/DNS, Infomaniak bleibt Mailanbieter. MX, SPF, DKIM, autoconfig und autodiscover erhalten. Keine pauschalen DNS- oder Nameserveränderungen. Web-A/AAAA und eventuell www erst separat nach Prüfung anpassen; Wildcard-Records nicht blind löschen.
