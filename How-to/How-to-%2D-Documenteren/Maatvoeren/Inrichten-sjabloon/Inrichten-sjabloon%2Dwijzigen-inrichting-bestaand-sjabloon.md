# **Inrichten sjabloon/wijzigen inrichting bestaand sjabloon**

**Werkwijze voor het inrichten van sjablonen:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_documentation_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_16x16.png) | Documentatie ]** > **[ ![themodus_prof_button_addin_productivity_documentation_dimensioning_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_dimensioning_16x16.png) | Maatvoering  ]**;
- Maak een nieuw sjabloon en selecteer deze om in te stellen 
_of_
- Selecteer een bestaand sjabloon om deze te wijzigen.
- Klik **[ ![themodus_generic_configure_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_configure_16x16.png) | Configureren ]**
- Selecteer bij **'Type maatvoering'** de gewenste werkstroom.:
  - **Maatvoering element lineair** voor het voorzien van lineaire maatvoering op alle elementen;
  - **Maatvoering element ordinaat** voor het voorzien van ordinaat maatvoering op alle elementen;
  - **Maatvoering element t.o.v. stramien** voor het voorzien van maatvoering van elementen ten opzichte van een stramien;
  - **Maatvoering bouwkundige samenstellingen** voor het voorzien van lineaire maatvoering voor wanden en vloeren;
  - **Maatvoering leidingsystemen]** voor het voorzien van leidingwerk van maatvoering.
_De volgende artikelen geven meer informatie over deze type maatvoeringen!_
- Selecteer bij **'Maatstijl'** het gewenste type maatlijn. De lijst toont alle beschikbare 'Lineair Dimension Types' in het actieve BIM-model. Bij sommige werkstromen wordt deze lijst nog eens
    gefilterd op de waarde 'Ordinate' of 'Continuous' bij de eigenschap 'Dimension String Type'.
Dimensions worden ingesteld onder 'Annotate' -- 'Dimension' -- 'Lineair Dimension Types'.
- Bij sommige werkstromen kunt u kiezen uit een (primaire) **'Maatstijl'** en een **'Secundaire maatstijl'** om onderscheid te maken tussen hoofdmaten en overige maten. Selecteer bij **'Secundaire maatstijl'** het gewenste type maatlijn.
- Geef bij **'Afstand tot element'** de afstand (in millimeters) op tussen het element (de 'bounding box' van het element) en de dichtstbijzijnde maatlijn.
- U kunt in het sjabloon een filter vastleggen van de categorieën van elementen. Indien geen categorieën geselecteerd, dan worden alle elementen voorzien van maatvoering. Indien categorieën zijn vastgelegd, dan worden alleen de elementen van de geselecteerde categorieën voorzien van maatvoering.
  - Klik **[ ![themodus_generic_select_file_21x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_select_file_21x16.png) | Selecteer te filteren categorieën ]** om de lijst met categorieën te openen.
  - Vink de gewenste categorieën aan
  - Klik **[ OK ]**
- In sommige gevallen is het gewenst om ook 'shared nested families' te voorzien van maatvoering. Activeer **'Geneste families toestaan' []** om ook deze families te voorzien van maatvoering;
- Objecten welke deels zichtbaar zijn in de view kunnen overgeslagen worden. Geef de minimale zichtbaarheid van de objecten op in %. Objecten minder dan ...% zichtbaar worden niet gemaatvoerd.
- Voor het maatvoeren van onder andere standleidingen is een speciale functie toegevoegd, zodat ook deze van maten kunnen worden voorzien. Activeer **'Alleen verticale connectoren' [ ]** om standleidingen te voorzien van maatvoering. Deze functie is beschikbaar bij voor werkstromen:
  - **Maatvoering element lineair**;
  - **Maatvoering element ordinaat**;
- Bij **'Referentie 1'** t/m **'Referentie 5'** kunt u de referenties opgeven waaraan de maatlijnen worden gekoppeld. 'TheModus Maatvoering' maakt gebruik van de referentievlakken in een familie. Deze referentievlakken moeten voorzien zijn van een naam, en mogen **niet** van het type "Not a reference" zijn. Bij alle werkstromen kunnen referenties opgeven worden bij 'Referentie 1'. Bij de werkstroom 'Maatvoering element lineair' kunnen ook **'Referentie 2'** t/m **'Referentie 5'** opgeven worden. Deze werkstroom ondersteund het om maatlijnen van meerdere niveaus in een gewenste volgorde te genereren. Het invoeren van referenties is eenvoudig:
- Klik **[ ![themodus_generic_match_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_match_01_16x16.png) | Selecteer een family om referentievlakken uit te lezen ]**
- Selecteer een object in het BIM-model welke representatief is.
- Klik **[ ![themodus_generic_finish_28x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_finish_28x16.png) | Finish ]**
_Er wordt nu een lijst met beschikbare referentie vlakken in de familie geopend._
- Selecteer de gewenste referenties
- Klik **[ OK ]** 
_De referenties worden overgenomen._
_U kunt referenties ook opgeven in het tekstvak. Meerdere referenties worden middels een ';' gescheiden. Met_ '( * )' _kunt u meerdere referenties opgeven die voldoen aan een bepaald kenmerk. Bijvoorbeeld Center (*)._
- Indien gewenst kan het gerefereerde element of categorie weergegeven worden bij de maatlijn. De maatlijn kan dan alleen dit element of categorie vertegenwoordigen. Voor de werkstroom 'Maatvoering bouwkundige samenstellingen' en de functie 'Groepeer maatlijnen op' ontwikkeld welke de maatlijn specifiek per 'Family', 'FamilyType' of 'Category' kan groeperen en tevens daarbij de naam plaatst.
  - Geef bij 'Groepeer maatlijnen op' de gewenste instelling op:
    - Geen
    - Categorie
    - Family
    - Family type
    - Type commentaar
    - Type omschrijving
- Voor de werkstroom 'Maatvoering element tot nulpunt' is een nulpunt noodzakelijk. Dit nulpunt moet bepaald worden door de gebruiker. 'TheModus Dimension' maakt in deze gebruik van een component, welke in de bibliotheek beschikbaar is.
- Klik **[ ![themodus_generic_match_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_match_01_16x16.png) | Selecteer nulpunt family (Detail item, generic model)  ]** en selecteer het element welke als nulpunt fungeert. U kunt ook meerdere nulpunten gebruiken. De elementen die bij een bepaald nulpunt horen, moeten dan een gelijke waarde hebben. Dit kan met behulp van een project parameter van het type 'text'. Selecteer bij 'Gelijke parameter waarde' de parameter welke de gelijke waarde heeft.
- Klik **[ Opslaan ]**