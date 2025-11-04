# **Verlichtingsplannen ontwerpen samen met Dialux**
Het bepalen van de juiste lichtopbrengst in een ruimte is een vak apart. Autodesk Revit biedt hiervoor geen oplossingen. Maar gelukkig zijn er wel andere applicaties, die op een goede manier een lichtberekening kunnen maken. 

'TheModus Dialux' maakt het mogelijk om de informatie uit een BIM model te gebruiken voor het berekenen van de lichtopbrengst in Dialux'. Met een druk op de knop kan de juiste ruimte informatie geëxporteerd worden. Deze informatie wordt vervolgens gebruikt in Dialux, om daar de juiste lichtopbrengst te berekenen op basis van gekozen armaturen. 

Vervolgens moeten de resultaten van deze berekening terug naar het BIM model, waar de juiste aantallen armaturen op de juiste posities geplaatst worden. Ook hierin voorziet 'TheModus Dialux'.

**Werkwijze voor het exporteren van de BIM informatie naar Dialux:**

- **Voorwaarde: Het model moet voorzien zijn van 'Spaces'**
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen ]**; > **[ ![themodus_prof_button_addin_productivity_tools_dialux_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_dialux_16x16.png) | Dialux ]**; 
- Selecteer het gewenste output formaat:
  - Export GbXML (3D view only)
  - Export STF:
    - Export STF file for active view
    - Export STF file for model
- Klik **[ OK ]**
- Selecteer de gewenste locatie waar het bestand opgeslagen moet worden. Geef de bestandsnaam.
- Klik **[ Opslaan ]**
_Het export bestand is nu gegenereerd. Gebruik dit bestand in Dialux om de data te importeren._

**Werkwijze voor het importeren van de resultaten uit Dialux naar het BIM model:**
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen ]**; > **[ ![themodus_prof_button_addin_productivity_tools_dialux_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_dialux_16x16.png) | Dialux ]**; 
- Selecteer **[ Import ]**
- Klik **[ OK ]**
- Browse naar de locatie waar het stf-bestand is opgeslagen, selecteer het bestand.
- Klik **[ Openen ]**