# **Gebouwen samenstellen op basis van opties**
Seriematige bouw is geen onbekend fenomeen. Met name in de woningbouw en in de unitbouw is er in hoge mate sprake van seriematigheid. 

Deze seriematigheid vereist een hoge repetitiefactor bij het maken van de bouwcomponenten. In een BIM model moet hiermee rekening worden gehouden. 

**'TheModus Opties'** ondersteunt de modelleur in het voorkomen van repeterende werkzaamheden. De techniek is gebaseerd op het gebruik van Revit groepen, welke samengesteld kunnen worden tot gebouwopties. Een gebouwoptie bestaat in deze uit één of meer Revit groepen. 

Deze Revit groepen worden beheerd in een apart model, ook wel een tasveld genoemd. In dit tasveld worden alle optiesets samengesteld. Hierbij kunnen meerdere optiesets gebruik maken van dezelfde Revit groepen.

Vervolgens kan een project worden uitgevoerd. In het projectmodel kunnen meerdere optiesets worden aangeroepen, welke uiteindelijk samen leiden tot een gebouw of gebouwdeel. De gebruiker maakt dus een selectie van optiesets. Vervolgens worden in één handeling op een vaste positie de groepen binnen deze optiesets geplaatst. Als voorbeeld selecteer je bijvoorbeeld de gevels van de begane grond, de gevels van een verdieping, de zolder, de inrichting van de begane grond en de inrichting van de verdieping. Het resultaat is een woning. Maak je een nieuwe selectie, dan wordt de hele woning opnieuw samengesteld.  

Op deze manier kan je heel snel een aspectmodel van een woning maken.

Voor het gebruik van **'TheModus Opties'** moet een tasveld beschikbaar zijn. Hierin moeten bouwdelen gebundeld zijn tot een Revit groep. Voor iedere groep is het belangrijk dat het nulpunt op de correcte plaats wordt gelegd. Dit nulpunt wordt namelijk gebruikt voor het automatisch plaatsen van de optiesets. Houdt hierbij rekening met de verdiepingen. 

Een tasveld in combinatie met 'Global Parameters' levert nog meer dynamiek. Je kan nu in bepaalde mate ook de beukmaten van de bouwdelen parametrisch beïnvloeden.

Voordat de optiesets gebruikt kunnen worden in een project, moeten eerst optiesets gemaakt worden in een tasveld. 

**Werkwijze voor het inrichten van een tasveld:**
- Maak een model, met daarin de gewenste bouwopties;
- Maak van iedere bouwoptie een groep;
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![Samenstellen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_compose_16x16.png) | Samenstellen ]** > **[ ![Optiesets samenstellen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_compose_set_16x16.png) | Optiesets samenstellen ]**;
_Een formulier opent._
- Onder **[ Beschikbare Revit groups ]** worden alle Revit groepen getoond zoals deze in het model zitten;
- Onder **[ Beschikbare optiesets ]** worden alle optiesets getoond. U kunt hier nieuwe optiesets aanmaken, namen wijzigen, optiesets importeren of een optieset verwijderen:
  - Voor het maken van een optieset:
    - Klik **[ ![themodus_generic_add_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_add_01_16x16.png) | Nieuw ]**
    - Geef de naam van de optieset op;
    - Klik **[ OK ]**
  - Voor het hernoemen van de optieset:
    - Selecteer de optieset;
    - Klik **[ ![themodus_generic_rename_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_rename_01_16x16.png) | Hernoemen ]**;
    - Geef de nieuwe naam van de optieset op;
    - Klik **[ OK ]**
  - Voor het importeren van de optieset:
    - Open een ander tasveld (bron);
    - Ga naar het doel tasveld;
    - Klik **[ ![themodus_generic_download_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_download_01_16x16.png) | Hernoemen ]**;
_Een nieuw formulier wordt geopend;_
    - Selecteer het bron tasveld;
      - Vink **[ ] 'Optiesets voor bestemming overschrijven'** "AAN" als u de bestaande optiesets wilt overschrijven;
      - Vink **[ ] 'Optiesets voor bestemming overschrijven'** "UIT" als u de (nieuwe) optiesets wilt toevoegen.
      - Klik **[ IMPORT ]**
    - Voor het verwijderen van de optieset:
    - Selecteer de optieset;
    - Klik **[ ![themodus_generic_remove_01_14x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_remove_01_14x16.png) | Verwijderen ]**;
        - Klik: **[ Ja ]** om de optieset te verwijderen;
        - Klik: **[ Nee ]** om de optieset te behouden.
- Aan iedere optieset moeten de juiste groepen worden verbonden.
  - Selecteer één of meerdere groepen.
  - Selecteer één of meerdere optiesets.
  - Klik **'Verbinden >>'**.
_De optieset wordt toegevoegd onder **'3. Samengestelde optiesets'**._
- Indien u een optieset wilt verwijderen:
  - Selecteer dan de optieset onder **'3. Samengestelde optiesets'**
  - Klik **[ ![themodus_generic_remove_01_14x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_remove_01_14x16.png) | Verwijderen ]**;
  - Herhaal bovenstaande stappen voor alle optiesets.
- Klik **[ Opslaan ]** zodra gereed.

De optiesets worden in de 'extensible storage' van het tasveld opgeslagen.

Volg onderstaande stappen voor het samenstellen van een gebouw met behulp van optiesets:
- Open de gewenste tasvelden. Dit mogen meerdere tasvelden zijn;
- Maak een nieuwe model;
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![Samenstellen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_compose_16x16.png) | Samenstellen ]** > **[ ![Optiesets samenstellen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_compose_building_16x16.png) | Gebouw samenstellen ]**;
_Een formulier opent._
- U gaat één aspectmodel maken van een woning:
  - Selecteer alle gewenste opties;
  - Klik **[ Samenstellen ]**
  - Het gebouw wordt samengesteld. Herhaal bovenstaande stappen om de samenstelling te wijzigen. De bestaande wordt dan verwijderd.

**Opmerking**
Omdat met Revit groepen wordt gewerkt, kan Revit vragen stellen met betrekking tot de typenamen van objecten. U kunt deze vragen onderdrukken door **[ ] 'Accepteer meldingen over bestaande types'** "AAN" te vinken.