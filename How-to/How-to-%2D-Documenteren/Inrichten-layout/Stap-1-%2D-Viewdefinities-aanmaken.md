# **Viewdefinities aanmaken**
De weergave van de documentatie is gebaseerd op de viewinstellingen zoals je kent van Revit. Er worden 'Viewtypes' gebruikt waaraan Viewtemplates' zijn gekoppeld, met daarin alle gewenste viewinstellingen, zoals actieve categorieën, schaal etc. 

Het is ontzettend belangrijk om de 'Viewtypes' en de bijbehorende Viewtemplates' goed in te richten. Schakel alleen die modelcategorieën vrij, welke van belang zijn voor uw documentatie. Het proces waarvoor je de documentatie nodig hebt, bepaald dus hoe de 'Viewtemplate' moet worden ingericht.

Op basis van de beschikbare 'Viewtypes' begrijpt 'TheModus Documentatie' ook welke projecties gemaakt kunnen worden. 

Zo wordt voor het 'Documenteren van elementen' en voor het 'Documenteren van ruimten' de 'Detail sections' gebruikt voor alle aanzichten, sneden, en plattegronden. 
Voor 'Documenteren project' wordt de 'Section' gebruikt voor de aanzichten en sneden. Voor de plattegronden worden Planviews' gebruikt. Verder kunnen bij alle werkstromen '3D views', Schedules' en 'Legends' worden gemaakt.

De 'Detail sections' en 'Sections' worden altijd geplaatst ten opzicht van de 'Bounding Box'. Dit is de uiterste doos rondom de geometrie van een element of collectie elementen. In geval van aanzichten worden de sneden aan de buitenzijde van deze box geplaatst, kijkend naar de box. In geval van de sneden wordt de snede geplaatst in het midden van de box, kijkend naar buiten. We noemen dit de 'Projecties'.

Er zijn bijzondere projecties. Deze zijn:
- Documenteren van ruimten:
  - In de lijst '**2. Selecteer projecties**' kan je **Placeholder wand aanzicht** selecteren. Selecteer deze waarde als je een aanzicht wenst van alle wanden in een ruimte. Je kan in '**Stap 2 - View properties**' instellen hoe ver de snede gemaakt wordt vanaf de wand, alsmede instellen vanaf welke minimum lengte wand er een 'View' gegenereerd wordt.


In de layout wordt vastgelegd welke projecties gemaakt moeten worden en van welk 'Viewtype' deze moeten zijn. 

**Werkwijze voor het vastleggen van de juiste projecties in het layout:**
- Het formulier **[ VIEW DEFINITITES AANMAKEN ]** is geopend;
- Selecteer in kolom '**1. Selecteer viewtype**' één of meerdere weergaven (met **<CTRL>** + klik). De weergaven zijn gesorteerd op Discipline -> Sub discipline -> Viewtype.
_Documentatie kan gegenereerd worden over meerdere Disciplines of Sub-disciplines. Dit is vaak gewenst bij installatieplannen;_
- Selecteer in de kolom '**2. Selecteer projecties**' één of meerdere projecties (met **<CTRL>** + Klik.
- Klik **[ ![themodus_generic_add_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_add_01_16x16.png) | Maak nieuwe view definitie ]** om de selectie toe te voegen als weergave definitie. Deze worden vervolgens getoond onder '**3. Gemaakte view definities**'.
_Als er 'Viewtypen' van verschillende Disciplines of Sub-disciplines zijn geselecteerd, dan wordt er voor al deze een viewdefinitie gemaakt._
- Herhaal bovenstaande stappen totdat alle 'view definities' gemaakt zijn.
- Een 'view definitie' kan verwijderd worden:
  - Selecteer de te verwijderen 'view definitie(s)' onder **'3. Gemaakte view definities'**
  - Klik **[ ![themodus_generic_remove_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_remove_01_16x16.png) | Verwijder geselecteerde viewdefinitie(s) ]**
  - Klik:
      - **[ Ja ]** om de geselecteerde view definitie(s) te verwijderen.
      - **[ NEE ]** om de geselecteerde view definitie(s) te behouden.
- Klik **[ VOLGENDE ]**
- Ga verder op de volgende pagina met het instellen van de 'View' eigenschappen

**Opmerking**
- In de navigatiebomen kunt u met de rechtermuisknop alle informatie in of uit klappen. 
- In de navigatiebomen gebruikt u de **<CTRL>** toets om meerdere regels te selecteren. 