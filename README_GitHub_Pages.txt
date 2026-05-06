ABACUS GitHub Pages pakket - versie met gebruikersdata

Bestanden:
- index.html
- .nojekyll
- README_GitHub_Pages.txt

naar idee van ABACUS/DeBasis V3.0.1:  Beat The Calculator! - Eugen O.

Upload naar GitHub:
1. Open je repository educatie-web.
2. Kies Add file > Upload files.
3. Upload index.html, .nojekyll en README_GitHub_Pages.txt.
4. Commit de wijzigingen.
5. Wacht tot GitHub Pages opnieuw gebouwd is.

Nieuw in deze versie:
- gebruikersnaam kiezen of toevoegen
- sessieresultaten lokaal bewaren in de browser
- analyse per gebruiker en operatie (+, -, ×, ÷)
- eenvoudige administrator-knop
- CSV-export
- alle gebruiksdata verwijderen
- alle moeilijkheidsparameters zichtbaar

Administrator:
- klik op 'Administrator'
- standaard wachtwoord: oefenen

Let op:
- Webdata wordt lokaal in de browser opgeslagen via localStorage.
- Bij wissen van browsergegevens kan deze data verdwijnen.
- Dit is een eerste basis/prototype voor gebruiksdata.

Extra in versie 4:
- Administrator wachtwoord aangepast naar: oefenen
- Kolom Tijdstip toegevoegd tussen Datum en Gebruiker

Extra in versie 5:
- Bij 'Wisselend' rouleren de operaties eerlijk: +, -, ×, ÷, daarna opnieuw.
- De analyse toont nu ook het totaal aantal gemaakte opgaven per operatie.
- Beheer uitgebreid:
  - administrator-wachtwoord zichtbaar en lokaal wijzigbaar
  - gebruikersnamen zichtbaar
  - gebruikersnamen bewerken
  - gebruiker verwijderen
  - gebruiker verwijderen inclusief sessies

Let op:
- Spelers hebben in deze versie nog geen wachtwoord.
- Het administrator-wachtwoord wordt lokaal op het apparaat opgeslagen.

Correctie in versie 6:
- De analysetabel bevat nu daadwerkelijk de kolommen:
  + opgaven, - opgaven, × opgaven, ÷ opgaven.
- JavaScript-syntax gecontroleerd.

Herstel in versie 7:
- Startfout opgelost waardoor keuzelijsten 'No options' konden tonen.
- Event listeners worden nu pas na het vullen van de schermen gekoppeld.
- Backup maken en backup importeren toegevoegd voor behoud van spelersnamen, sessies en analysegeschiedenis.

Aanpassing in versie 8:
- Bij alle moeilijkheidsgraden zijn nu alle bewerkingen actief en selecteerbaar: +, -, ×, ÷.
- Het label 'Score' is gewijzigd naar 'Goed'.
- 'Beantwoord' telt nu goede antwoorden plus foutpogingen.
- Sessieopslag gebruikt nu 'Beantwoord' in plaats van aangemaakte/gestarte opgaven.
- Backup/import gebruikt JSON en is bedoeld voor volledige app-data: gebruikers, sessies, analyses en instellingen.

Herstel in versie 9:
- Oude browserinstellingen worden automatisch gemigreerd naar alle vier bewerkingen voor alle moeilijkheidsgraden.
- Daardoor tonen Basis en Gevorderd nu ook ÷, ook als localStorage nog oude instellingen bevatte.
- Analyse gebruikt voortaan de som van goed/fout per operatie als bron voor Goed, Fout en Beantwoord.
- Opgeslagen sessies tonen berekende waarden.
- CSV-export bevat expliciete kolommen: goed, fout en beantwoord.
- Beheerlocatie administrator-wachtwoord verduidelijkt.
