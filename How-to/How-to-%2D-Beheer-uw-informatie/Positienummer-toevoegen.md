# **Positienummer toevoegen**

Ter invulling van prefab werkzaamheden is het noodzakelijk om de objecten in een prefab set te markeren. TheModus 'Positienummer toevoegen' is een eenvoudig hulpmiddel welke de objecten in een prefab set voorziet van een volgnummer, zodat alle objecten altijd uniek zijn gecodeerd. 

TheModus 'Positienummer toevoegen' maakt gebruik van een filter op basis van categorieën. Bij het selecteren van de objecten worden alleen objecten toegevoegd aan de selectie die voldoen aan de filter. De eerste keer dat u TheModus 'Positienummer toevoegen' gebruikt staan mogelijk niet alle gewenste categorieën geactiveerd in de filter.

**Werkwijze voor het instellen van de de filter:**
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![Indelen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_16x16.png) | Indelen ]**; > **[ ![Positienummer toevoegen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_numbers_position_16x16.png) | Positienummer toevoegen ]**; 
- Maak geen selectie, klik **[ Finish ]** of **[ Cancel ]**
- Klik **[ ![Indelen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_numbers_prefab_configure_16x16.png) | Indelen ]** om de lijst categorieën te openen
  - Activeer de gewenste categorieën
  - Klik **[ OK ]** om de filter op te slaan.
_Deze filter wordt de volgende keer automatisch toegepast._
- Klik **[ OK ]**
_De filter is ingesteld._
- Klik **[ OK ]** bij de melding: 'Geen Prefabnummer geselecteerd'

**Werkwijze voor het toekennen van positienummers aan objecten:**
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![Indelen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_16x16.png) | Indelen ]**; > **[ ![Positienummer toevoegen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_numbers_position_16x16.png) | Positienummer toevoegen ]**; 
- Maak geen selectie, klik **[ Finish ]** of **[ Cancel ]**
- Selecteer de prefab sets, waarin de objecten moeten worden gemarkeerd. 
- Klik **[ OK ]**
_Ieder object krijgt nu een uniek nummer per positienummer._

**Opmerking**
- Het nummer wordt toegevoegd aan de project parameter "positienummer". Bestaande informatie wordt overschreven.
- Het positie nummer wordt ook toegevoegd aan alle 'Shared nested families';
- De instellingen worden opgeslagen in het bestand 'AECSettings.xml' in _%localappdata%\Cadac Group\TheModus Revit
    Addin\Config\Documentation_.