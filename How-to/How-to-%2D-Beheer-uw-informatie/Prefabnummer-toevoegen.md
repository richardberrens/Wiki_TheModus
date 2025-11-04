# **Prefabnummer toevoegen**

Ter voorbereiding van prefab werkzaamheden is het noodzakelijk om in het BIM-model de juiste objecten te voorzien van een prefab nummer.

TheModus 'Prefabnummer toevoegen' is een eenvoudig hulpmiddel welke een bestaand of nieuw prefabnummer toekent aan een selectie van objecten welke samen het prefab deel vormen.

TheModus 'Prefabnummer toevoegen' maakt gebruik van een filter op basis van categorieën. Bij het selecteren van de objecten worden alleen objecten toegevoegd aan de selectie die voldoen aan de filter. De eerste keer dat u TheModus 'Prefabnummer toevoegen'  gebruikt staan mogelijk niet alle gewenste categorieën geactiveerd in de filter.

**Werkwijze voor het instellen van de de filter:**
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![Indelen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_16x16.png) | Indelen ]**; > **[ ![Artikelnummer toevoegen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_numbers_prefab_16x16.png) | Prefabnummer toevoegen ]**; 
- Maak geen selectie, klik **[ Finish ]** of **[ Cancel ]**
- Klik **[ ![Indelen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_numbers_prefab_configure_16x16.png) | Indelen ]** om de lijst categorieën te openen
  - Activeer de gewenste categorieën
  - Klik **[ OK ]** om de filter op te slaan.
_Deze filter wordt de volgende keer automatisch toegepast._
- Klik **[ OK ]**
_De filter is ingesteld._
- Klik **[ OK ]** bij de melding: 'Geen Prefabnummer geselecteerd'

**Werkwijze voor het toekennen van prefabnummers aan objecten:**
- Selecteer de gewenste objecten welke tot een prefab set behoren;
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![Indelen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_16x16.png) | Indelen ]**; > **[ ![Prefabnummer toevoegen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_numbers_prefab_16x16.png) | Prefabnummer toevoegen ]**; 
- Geef een nieuw nummer op
_of_
- Selecteer en bestaand prefabnummer. 
- Klik **[ OK ]**
_Het prefab nummer is nu toegevoegd._

**Opmerking**
- Het nummer wordt toegevoegd aan de project parameter "prefabnummer". Bestaande informatie wordt overschreven.
- Het prefabnummer wordt ook toegevoegd aan alle 'Shared nested families';
- De instellingen worden opgeslagen in het bestand 'AECSettings.xml' in _%localappdata%\Cadac Group\TheModus Revit Addin\Config\Documentation_. 