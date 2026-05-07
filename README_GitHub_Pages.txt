ABACUS GitHub Pages pakket - versie 13 stabiele PWA

naar idee van Eugen O.

Doel:
Eén universele versie voor iPad, Windows en Mac.

Belangrijkste wijziging t.o.v. v12:
- De update-popup “Nieuwe versie beschikbaar — herstart de app” is verwijderd.
- De service worker is vereenvoudigd.
- Offline werking blijft behouden.
- Dit voorkomt de Safari/iPad update-lus.

Upload naar GitHub:
Upload/vervang alle 7 bestanden in de hoofdmap van repository educatie-web:

1. index.html
2. .nojekyll
3. README_GitHub_Pages.txt
4. manifest.webmanifest
5. service-worker.js
6. icon-192.png
7. icon-512.png

Geen icons-map nodig.

Na upload:
1. Commit changes.
2. Wacht 2 minuten.
3. Test eerst in Safari/Edge via:
   https://voxd2025.github.io/educatie-web/

iPad-installatie:
1. Verwijder oud ABACUS-icoon.
2. Wis Safari-websitegegevens voor github.io / voxd2025.github.io.
3. Herstart iPad.
4. Open Safari.
5. Open https://voxd2025.github.io/educatie-web/
6. Wacht 30 seconden.
7. Deelknop > Zet op beginscherm.

Windows:
1. Open Edge.
2. Open https://voxd2025.github.io/educatie-web/
3. Wacht 30 seconden.
4. Menu ... > Apps > Install ABACUS Web.

Vergeten administrator-wachtwoord:
Open:
https://voxd2025.github.io/educatie-web/?resetAdmin=1

Standaard wachtwoord na reset:
oefenen

Backups:
Maak regelmatig een JSON-backup via Administrator > Backup maken.
