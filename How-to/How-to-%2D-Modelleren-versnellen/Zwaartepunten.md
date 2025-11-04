# **Zwaartepunten**
Weten waar een zwaartepunt van objecten ligt, is een belangrijk gegeven voor constructeurs en aannemers. Voor constructeurs is dit van belang, om te weten of elementen of zelfs gebouwdelen niet omvallen. Denk vaak ook aan kunstwerken. Voor aannemers is dit van belang om te weten hoe een element te hijsen met de bouwkraan.

Het berekenen van een zwaartepunt is redelijk complex. Het is bijna altijd een verzameling van berekeningen van meerdere zwaartepunten van verschillende materialen en vormen.

Met 'TheModus Center of Gravity' kan met redelijke nauwkeurigheid een zwaartepunt berekend worden van een object of collectie van objecten. De gebruiker zal wel enkele gegevens moeten opgeven van de materialen, aangezien die veelal ontbreken bij de materiaalspecificaties.

'TheModus Center of Gravity' maakt gebruik van de werkelijke volumes binnen een object. Het zwaartepunt wordt berekend op basis van deze volumes en de opgegeven volumieke massa, massa per oppervlakte, massa per lengte of massa per instantie. Indien er meerdere geometrieën gekoppeld zijn aan verschillende materialen, dan kan er feitelijk een afwijking optreden!

Voordat 'TheModus Center of Gravity' gebruikt kan worden moet de gebruiker eerst de volumieke eigenschappen toevoegen aan de juiste
parameters. De parameters zijn bepaald en kunnen door TheModus worden toegevoegd aan het model. Onderstaand een overzicht van de parameters welke door TheModus worden toegevoegd: 
- **CDC CenterPoint**, alleen lezen, op instantie niveau. Hier wordt de berekende coördinaten van het zwaartepunt geschreven.
- **CDC Mass Instance**, alleen lezen, op instantie niveau. Hier wordt de berekende massa van het object geschreven .
- **CDC Mass Part**, op type niveau. Hier kan de gebruiker de massa van het object opgeven. Deze wordt veelal gebruikt als zwaartepunten berekend moeten worden over grote collecties meubilair. Bijvoorbeeld in de offshore industrie.
- **CDC CenterPoint Custom**. Hier kan de gebruiker zelf een zwaartepunt opgeven als deze door bijvoorbeeld een fabrikant beschikbaar is gesteld. Deze kan dan weer gebruikt worden in berekeningen van hele collecties objecten.
- **CDC Mass Cubic Meter**. Hier kan de gebruiker de volumieke massa opgeven. Bijvoorbeeld bij betonwerk.
- **CDC Mass Meter**. Hier kan de gebruiker de massa per lengte opgeven. Bijvoorbeeld bij leidingwerk of staalconstructies.
- **CDC Mass Square Meter**. Hier kan de gebruiker de massa per oppervlakte opgeven. Bijvoorbeeld bij plaatmaterialen.

**Werkwijze voor het toevoegen van de noodzakelijke parameters aan het model:**
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_calculations_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_calculations_16x16.png) | Berekeningen ]**; > **[ ![themodus_prof_button_addin_productivity_calculations_cog_properties_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_calculations_cog_properties_16x16.png) | CoG parameters toevoegen ]**; 
_De parameters worden toegevoegd als project parameters._

**Voor de te berekenen type objecten moet nu minimaal één massa per eenheid worden opgegeven.**

**Werkwijze voor het berekenen van het zwaartepunt van één of meerdere objecten:**
- Selecteer een object of collectie van objecten. In geval van een collectie objecten, wordt het zwaartepunt berekend over het geheel van de objecten;
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_calculations_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_calculations_16x16.png) | Berekeningen ]**; > **[ ![themodus_prof_button_addin_productivity_calculations_cog_calculate_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_calculations_cog_calculate_16x16.png) | CoG berekenen ]**; 
- De volgende dialoog verschijnt: 
![themodus_nl_dialoog_cog.png))](https://download.cadac.com/themodus/manual/themodus_nl_dialoog_cog.png)
- Selecteer bij **'Te gebruiken familie'** de familie welke gebruikt moet worden als zwaartepunt symbool. Indien geen familie wordt opgegeven wordt het standaard symbool gebruikt.
- Selecteer bij **'Type naam'** het type van de geselecteerde familie welke gebruikt moet worden als zwaartepunt symbool. Indien geen type wordt opgegeven wordt het standaard symbool gebruikt.
- Geef bij **'Mark voorvoegsel'** een kenmerk of parameter aan welke wordt toegevoegd aan het symbool.
- Activeer **[ ] 'Marker voor elk element'** als ieder object in een selectie van objecten individueel berekend moet worden. Er wordt dan voor ieder object een zwaartepunt symbool geplaatst. Indien gedeactiveerd wordt het zwaartepunt berekend voor de hele selectie.
- Klik **[ OK ]**
_De berekening start._
- Er wordt een formulier geopend met een samenvatting van de berekende resultaten. Op het tabblad **'berekende'** staan alle objecten waarvan de resultaten berekend konden worden. Op het tabblad **\'overgeslagen\'** staan alle objecten waarvoor geen zwaartepunt berekend kon worden, met daarbij de reden waarom de berekening niet gemaakt kon worden. Aan de onderzijde zit de knop **[ EXPORT ]** waarbij de berekende resultaten geëxporteerd kunnen worden naar een csv bestand.
- Op de plek van het zwaartepunt wordt een zwaartepunt symbool geplaatst, met daarin de gegevens van het gevonden zwaartepunt.

**Opmerking**
Indien om bepaalde redenen andere parameters gebruikt moeten worden voor het ophalen van de massa, dan kunnen deze gemapt worden. Deze mapping vindt plaats in het bestand "*TheModus_COG_Mapping.xml"*. Deze staat in het pad _%localappdata%\Cadac Group\TheModus Revit
Addin\Config\CoG\_