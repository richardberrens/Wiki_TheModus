# **Werktuigbouwkundige berekeningen met BINK**
Autodesk Revit biedt weinig tot geen ondersteuning voor het berekenen van een kanalen of leiding stelsel.

Met TheModus is het mogelijk om uw Revit luchtkanalen, tapwater, gas of CV stelsel te laten berekenen met Bink-software. Om de berekening uit kunnen voeren is de Bink leidingberekening applicatie nodig. 

Om een kanaal of leiding stelsel te kunnen berekenen moet het stelsel aan een aantal voorwaarden voldoen:
- Het betreft een gesloten systeem met 1 startpunt en één of meerdere eindpunten (roosters/systeemobjecten).
- Het betreft een systeem met 1 startpunt, één of meerdere eindpunten (roosters/systeemobjecten) en één of meerdere open einden. De open einden worden gezien als een debiet 0. De kanaaldelen die aangesloten zijn op het open eind krijgen de kleinst beschikbare kanaalafmeting.
- Het betreft een systeem zonder startpunt met maar één open eind. Het open eind wordt als beginpunt opgenomen.
- De eindpunten moeten zijn voorzien van een debiet. Debietloze delen krijgen de kleinst beschikbare kanaalafmeting. De eindpunten moeten voorzien zijn van specifieke debietparameters, zie 'Debiet parameters'
- Alle componenten binnen het systeem, met uitzondering van leidingen/kanalen, bevatten de shared parameters IfcExportAs en IfcExportType welke beiden gevuld moeten zijn met de juiste waarden. Zie 'IFC parameters'.

**Werkwijze voor het berekenen van het stelsel:**
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_calculations_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_calculations_16x16.png) | Berekeningen ]**; > **[ ![themodus_prof_button_addin_productivity_calculations_bink_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_calculations_bink_16x16.png) | Bink berekening ]**; 
_Het projectscherm wordt getoond:_
  - Geef de Project gegevens;
    - Projectnaam
    - Projectnummer
    - Gebouw.
  - Selecteer de gewenste discipline:
    - CV
    - Lucht
    - Gas
    - Tapwater
  - Klik op **[ Export ]**
- Selecteer in het model het startelement van de te berekenen leidingen of kanalen;
- Selecteer de gewenste locatie waar het bestand opgeslagen moet worden. Geef de bestandsnaam.
- Klik **[ Opslaan ]**
- Open de Bink applicatie en importeer het aangemaakte bestand;
- Voer de berekening uit met de Bink applicatie en maak een export-bestand aan met de berekende resultaten;
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_calculations_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_calculations_16x16.png) | Berekeningen ]**; > **[ ![themodus_prof_button_addin_productivity_calculations_bink_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_calculations_bink_16x16.png) | Bink berekening ]**; 
_Het projectscherm wordt getoond:_
- Selecteer de discipline. Standaard is de laatst gekozen discipline voor geselecteerd;
- Klik op de knop **[ Import ]**
- Selecteer het door de Bink applicatie aangemaakte export-bestand en klik **[ Openen ]**
_U krijgt nu de melding hoeveel objecten zijn geïmporteerd en het stelsel wordt met de berekende waardes bijgewerkt._
_Klik [hier](https://dgmrsoftware.nl/producten/gebouw-en-installatie/leidingen/)voor meer informatie over Bink.*