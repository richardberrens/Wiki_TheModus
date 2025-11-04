# **Importeer BIM van Techline**
Vele bedrijven maken voor hun prefab oplossingen gebruik van Techline Prefab. Als bron wordt dan het BIM model gebruikt.

Eenmaal de prefab gemaakt, moet de informatie weer terug naar het BIM model. Met 'Import Techline' wordt de informatie uit AutoCAD terug ingelezen in Autodesk Revit.

**Werkwijze  voor het exporteren van prefab naar een BIM-model:**
- Activeer in AutoCAD het commando **[ Exporteer naar TheModus ]** op het tabblad: Algemeen > Support
_of_
tik in op de commandoregel: **TLEXPORTTL**
- Maak een keuze op de commandoregel; "Alleen techline objecten" of "Ook autocad blocks", kies:
  - **[ Alleen techline objecten ]** om 'Alleen techline objecten' te exporteren.
  - **[ Ook autocad blocks ]** om 'Techline objecten en 3D AutoCAD blocks' (3D solids in een AutoCAD block)
_3D solids die niet tot een block zijn verwerkt gaan niet mee over._
- Selecteer de Techline objecten en/of de AutoCAD 3D blocks die geëxporteerd moeten worden naar TheModus, met een window of een crossing.
- Bevestig de selectie met **<Enter>**
- Selecteer de gewenste locatie waar het tmex-bestand opgeslagen moet worden.
- Klik **[ Opslaan ]**
_Plaats het tmex-bestand op een voor u bekende plaats._

**Opmerking**
Indien u alleen één specifiek leidingstelsel wilt overzetten naar Revit TheModus, (bestaand uit twee of meerdere leidingsystemen (= lagen)), dan bestaat er de mogelijkheid om deze op verschillende manieren te selecteren in uw tekening. Het principe hierbij is om een selectieset te creëren die dan via de 'Previous' selectie mogelijkheid gebruikt kan worden bij de export functie. Dit dient dus te gebeuren voordat u de functie *'Exporteer naar TheModus'* activeert. Er zijn 3 methoden:
- Via tabblad 'Bewerk' -> 'Nordined Enkellijnig -> Techline' -> 'Route Controle'
Plaats het startpunt op het te selecteren leidingtracé
  - Toets **<Enter>**
  - Toets **<Esc>**
- Via tabblad 'Bewerk' -> 'Bewerk' -> 'Wijzig Leidingsysteem'
  - Kies 'Tracé' voor één leidingsysteem
_of_
  - Kies 'TMeerderelagen' als het leidingsysteem uit meerdere systemen (lagen) bestaat en is aangesloten
  - Selecteer een onderdeel van het tracé
  - Toets **<Enter>**
  - Klik **[ X ]** (Sluiten)
- Gebruikers met Techline Prefab-module: via tabblad 'Prefab' -> 'Controle Prefab' -> 'Route'
  - Selecteer een onderdeel van het tracé
  - Toets **<Esc>**
- Daarna kiest u voor 'Exporteer naar TheModus' maak de keuze voor 'Alleen Techline objecten' of 'Ook autocad blocks' en toets de **<P>** van 'Previous'. De selectie die u had gedaan op een van bovenstaande manieren wordt nu in de exportselectie gezet. Indien gekozen voor 'Ook autocad blocks' dan kan daarna alsnog, met een 'Window' of 'Crossing', AutoCAD 3D blocks aan de selectie toegevoegd worden.

**Werkwijze voor het importeren van prefab naar een BIM-model:**
- Open/activeer een floorplan of een 3D view.
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen ]**; > **[ ![themodus_prof_button_addin_productivity_tools_techline_import_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_techline_import_16x16.png) | Importeer Techline ]**; 
- Browse naar de locatie waar het tmex-bestand is opgeslagen, selecteer het bestand.
- Klik **[ Openen ]**
- Het 'Instellingen import uit Techline' dialoog verschijnt. Met hierin de velden:
  - 'Extremen model' met de minimale en maximale X,Y,Z coördinaten
  - 'Lokatie':
    - Level: Geef hier het Level aan waar de import moet komen. Het x-y vlak van de desbetreffende AutoCAD export (blocks en pipetypes) worden hier op het juiste level gelegd. Hiermee bepaalt u dus op welke bouwlaag de import moet komen te liggen.
    - Offset: x, y, z-waarden komen overeen met het nulpunt van de tekening x,y,z-nulpunt in AutoCAD. Als u deze op 0, 0, 0 waarden houdt, komen het nulpunt van de AutoCAD export en het Project basepoint met elkaar overeen.
      - Klik **[ ... ]** om een nieuw 0-punt op te geven.
  - 'Koppeling leidingsystemen':
    - TheModus leidingsysteem: De geselecteerde leidingsystemen. (vanuit Techline)
    - Revit Pipe/Ducttype: De (nieuwe) pipe/ducttype waarnaar de Techline objecten moeten worden omgezet, die _of_:
      - al in het project staan.
      - nog niet in het project staan; Revit Pipe/Ducttype geeft <nieuw aan te maken>.
  - Klik **[ OK ]**
_Er verschijnt een groene import status balk._
_Als de "Cadac Techline Import"-status balk klaar is, wordt weergegeven hoeveel objecten zijn geïmporteerd. Klik **[ OK ]**_
- Tik in per view > VV / VG > Tabblad 'Imported Categories' > Activeer **[] 'Imports in Families'**. 
_Alle imported AutoCAD objects worden zichtbaar._

**Opmerking**
Een 3D model o.b.v. AutoCAD, met daarin Techline objecten en/of AutoCAD 3D modellen die verwerkt zijn in blocks.