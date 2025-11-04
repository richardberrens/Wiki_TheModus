# **Genereer rooms of spaces uit DWG**
U kunt ruimten uit een Autocad onderlegger direct overnemen naar uw Revit model. Er worden dan **'Rooms'** of **'Spaces'** getekend met behulp van **'Room separation Lines'**.
Deze functie wordt vaak gebruikt in combinatie met **'Verdelen objecten'** 

Voorafgaand aan het genereren van de ruimten adviseren we de AutoCAD onderlegger zoveel mogelijk op te schonen. Laat alleen die lagen 'aan' staan in de view die relevant zijn voor de afbakening van de ruimten. In het algemeen zijn dit alleen lijnen die wanden en/of deuren vertegenwoordigen!

**Werkwijze voor het genereren van ruimten:**
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen ]**; > **[ ![themodus_prof_button_addin_productivity_tools_createroomfromdwg_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_createroomfromdwg_16x16.png) | Genereer rooms of spaces voor geimporteerde DWG's ]**; 
- Maak een selectie van de te maatvoeren elementen:
  - Selecteer:
    - **'Actieve view'** om alle elementen op te sporen welke voldoen aan de criteria zoals ingericht in het sjabloon. Alle elementen die voldoen worden voorzien van maatvoering;
    - **'Lijst van views'** om alle elementen op te sporen welke voldoen aan de criteria zoals ingericht in het sjabloon in alle geselecteerde 'Views'.
        -   Klik **[ ![themodus_generic_select_file_21x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_select_file_21x16.png) | [...] ]** om de views te selecteren.
          - Selecteer alle views
          - Klik **[ OK ]**
- Selecteer **'Rooms'** of **'Spaces'** afhankelijk van het type ruimte dat u wilt genereren.
- Activeer **[] 'Alleen gesloten polylijnen'** als u zeker weet dat er gesloten polylijnen beschikbaar zijn in het model die de ruimten reeds vertegenwoordigen in de AutoCAD onderlegger.
- Geef de minimale grootte van het oppervlakte van een ruimte op bij **'Minimaal aan te maken oppervlak'**
- Geef indien gewenst een voorvoegsel en nummer op.
- Klik **[ Starten ]**
_De ruimten worden gegenereerd._
- U kunt nu de verdeel routine starten op basis van de gegenereerde ruimten.
