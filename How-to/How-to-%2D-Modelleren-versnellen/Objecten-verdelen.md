# **Objecten verdelen**
In bijna alle projecten is er sprake dat objecten verdeelt moeten worden in een ruimte of gebied. Denk bijvoorbeeld aan inrichtingen of verlichtingsplannen. Autodesk Revit biedt enkele basisfunctie om objecten te verdelen, echter zijn deze bewerkelijk en bieden niet voldoende ondersteuning. Het plaatsen en verdelen van objecten is als gevolg ook een behoorlijk tijdrovende klus, welke vaak fout gaat.

Met **'TheModus Verdelen'** wordt het verdelen van objecten in ruimten veel eenvoudiger. **'TheModus Verdelen'** maakt gebruik van patronen. Deze patronen zijn 'Revit families' en kunnen zelfs door klanten uitgebreid worden. De patronen bieden een preview van het resultaat waardoor de modelleur meteen een goed beeld krijgt van het resultaat. Daarnaast passen de patronen zich aan, aan de geselecteerde ruimten. Er kunnen dan ook meerdere ruimten in één handeling voorzien worden van de objecten.

Voor **'TheModus Verdelen'** zijn geen voorbereidende werkzaamheden nodig. De functie kan meteen toegepast worden in alle Revit modellen.

**Werkwijze voor het verdelen van objecten in één of meerdere ruimten:**
- De functie starten en de elementen selecteren:
  - Plaats op een willekeurige plek, maar wel op de correcte hoogte, het te verdelen object;
  - Selecteer het te verdelen object en de ruimtes waarin het object verdeelt moet worden;
  - Klik in 'Modify' > 'Cadac Revit bewerk' > **[ ![themodus_prof_button_addin_modify_divide_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_modify_divide_16x16.png) | Verdelen ]**;
_of_
  - Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![Indelen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_16x16.png) | Indelen ]**; > **[ ![themodus_prof_button_addin_modify_divide_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_modify_divide_16x16.png) | Verdelen ]**; 
  - Selecteer de gewenste ruimten;
  - **[ ![themodus_generic_finish_28x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_finish_28x16.png) | Finish ]** 
_Het formulier voor het verdelen wordt geopend._
- Selecteer bij **'1. Element'** het object wat verdeelt moet worden.
_Dit object hoeft niet op de correcte plaats te staan. Het enige wat van belang is, is dat het element op de juiste hoogte is gepositioneerd._
- Selecteer bij **'2. Room/Space'** de ruimten waar de verdeling moet plaatsvinden. U kunt meerdere ruimten selecteren.
  - **[ ![themodus_generic_edit_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_edit_16x16.png) | Selecteer Room / Space ]** om de ruimten te selecteren. U kunt met een rechthoek alles selecteren. Er worden alleen 'Rooms' of 'Spaces' opgenomen in de selectie.
  - **[ ![themodus_generic_finish_28x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_finish_28x16.png) | Finish ]** als de selectie compleet is. U kunt met de **[ < ]** en **[ > ]** knoppen door de ruimten bladeren. De ruimten worden dan opgelicht in de actieve view.
_De verdeling gaat plaatsvinden op de ruimten die actief zijn._
  - Selecteer **'Alle'** in de lijst om de objecten in alle ruimten te verdelen. 
- Selecteer bij **'3. Patronen'** het gewenste verdeelpatroon. U kunt dit verdeel patroon instellen per ruimte! De lijst toont alle
    beschikbare patronen.
    Met **[ ![themodus_generic_refresh_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_refresh_16x16.png) | Standaard TheModus patronen opnieuw downloaden ]** kunt u eventueel aangepaste of nieuwe patronen downloaden van TheModus.
  - Klik 2 keer op het patroon om het patroon te activeren in de geselecteerde ruimte(n)
_of_
  - Selecteer het patroon
  - Klik **[ ![themodus_generic_grid_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_grid_16x16.png) | Genereer patronen ]**
- Vul bij **'4. Eigenschappen'** de gevraagde gegevens in. Dit kunnen afmetingen, aantallen of hoekverdraaiingen zijn. Indien u
    patronen instelt per ruimte, dan moeten ook de eigenschappen per ruimte worden ingesteld.
- Voordat u gaat verdelen, kunt u de patronen nog handmatig aanpassen.
  - Klik **[ SLUIT ]**
_Het formulier wordt gesloten. Pas de patronen indien gewenst aan. U kunt deze verschuiven, vergoten, verkleinen._
  - Open vervolgens opnieuw het formulier.
- Klik **[ VERDEEL ]** en het geselecteerde object wordt verdeelt over alle ruimten.

U kunt ook objecten verdelen op basis van een AutoCAD onderlegger. Ter ondersteuning van het gebruik van AutoCAD onderleggers heeft TheModus een functie welke op basis van de onderlegger 'Rooms' of 'Spaces' voor u aanmaakt. Op basis van deze ruimten kan vervolgende 'TheModus Verdelen' worden toegepast. Ga voor meer informatie naar het artikel 'Genereer rooms of spaces uit DWG'.


**Opmerking**
U kunt zelf patronen maken. Voor het patroon is nodig een Revit Family, een mapping bestand en een afbeelding van het patroon. De standaard patronen staan in *%localappdata%Cadac GroupTheModus Revit AddinConfigPatterns20xx*.

Gebruik de bestaande patronen als voorbeeld voor het maken van een nieuw patroon. U kunt ook een Cadac Revit consultant raadplegen.