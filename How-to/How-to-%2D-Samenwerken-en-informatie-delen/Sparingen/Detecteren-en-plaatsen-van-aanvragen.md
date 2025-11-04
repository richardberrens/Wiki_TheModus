## **Detecteren en plaatsen van aanvragen**
Voordat sparingen gemaakt kunnen worden zal eerst bekend moeten zijn waar sparingen noodzakelijk zijn. Bestaande BIM modellen moeten met elkaar worden vergeleken. Daar waar clashes tussen de modellen ontstaan kan mogelijk sprake zijn van een sparingsaanvraag.

'TheModus Sparingen' ondersteunt bij het detecteren en lokaliseren van de sparingsaanvragen. Zowel objecten binnen één model, alsmede objecten van gelinkte modellen worden geanalyseerd. Alle resultaten worden weergegeven in een formulier op basis waarvan de gebruiker de volgende stappen kan maken.

Voordat u aan de slag gaat met het detecteren van de sparingen adviseren wij de paragraaf *'Voorbereiden sparingen proces'* goed door te nemen. Niet alleen is dit noodzakelijk om het proces te configureren. Er staat ook uitvoerig beschreven wat de mogelijkheden zijn. 

**Werkwijze voor het detecteren van sparingsaanvragen:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen  ]** > **[ ![themodus_prof_button_addin_productivity_tools_openings_cut_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_openings_cut_16x16.png) | Sparing aanvragen]**;
_Het formulier 'Sparing aanvragen' wordt geopend met het tabblad '1. AANVRAGEN DETECTEREN' actief;_
- Geef bij **'Algemeen'** op:
  - De **'Aanvraagdatum';** de datum wanneer de aanvraag voor de sparing start.
Klik op het datumicoon en selecteer de datum;
  - De **'Aanvrager'** de naam van de aanvrager;
- Selecteer bij **'Voorselectie' **hoe de welke objecten in het model geanalyseerd moeten worden. U kunt kiezen uit:
  - **'Project'** om alle objecten in het hele project te analyseren;
  - **'View'** om alleen de objecten in de actieve view te analyseren.
_Hiermee kunt u de werklast van het verwerken van sparingen eenvoudig reduceren._
  - **'Selectie'** om alleen de objecten die u selecteert te analyseren.
_Hiermee kunt u de werklast van het verwerken van sparingen eenvoudig reduceren._
  - **'Open worksets'** om alleen de objecten te analyseren die beschikbaar zijn in een open workset.
_Hiermee kunt u de werklast van het verwerken van sparingen eenvoudig reduceren en worden alleen objecten geanalyseerd die vanuit rechten toegankelijk zijn._
  - **'Actieve workset'** om alleen de objecten te analyseren die beschikbaar zijn in een actieve workset.
_Hiermee kunt u de werklast van het verwerken van sparingen eenvoudig reduceren en worden alleen objecten geanalyseerd waar u op dat moment mee bezig bent._
- Geef bij **'Automatisch staffel opnemen'** op:
  - Voor **'Staffel rond'** de gewenste staffel voor ronde sparingen. Voor sparingen die door een staffel aangebracht kunnen worden, wordt meteen de juiste staffelmaat opgenomen;
  - Voor **'Staffel rechthoekig'** de gewenste staffel voor rechthoekige sparingen. Voor sparingen die door een staffel aangebracht kunnen worden, wordt meteen de juiste staffelmaat opgenomen;
- Indien u met 'worksets' werkt, kunt u opgeven in welke 'workset' de aanvraagobjecten verwerkt moeten worden. Selecteer bij **'Sparing workset'** de gewenste 'workset'.
- Bij **'Clash categorieën 1'** vind u alle werktuigbouwkundige en elektrotechnische categorieën welke gebruikt worden in de analyse. Bij objecten van deze categorieën start de analyse. Deze worden vergeleken met de bouwkundige categorieën onder **'Clash categorieën 2'**. U kunt hier filteren welke categorieën vergeleken moeten worden. Op deze manier kunt u de werklast verdelen per discipline. Selecteer in beide kolommen de categorieën welke u wilt analyseren. Gebruik eventueel de rechter muisknop om alles te selecteren of de-selecteren;
- Klik **[ AANVRAGEN DETECTEREN | > ]**
_Het analyse proces start nu. Zodra gereed, worden de resultaten in een nieuw formulier getoond._

Het formulier met de geanalyseerde aanvragen werkt interactief met het model. U kunt dit formulier naar een tweede scherm slepen, en de sparingaanvragen in de tabel aanklikken. Het formulier bestaat uit een tabel met daarin alle gevonden aanvragen. De aangeklikte sparingen worden geactiveerd in de actieve view. Met **<CTRL>** kunt u meerdere
aanvragen selecteren. Met de knop **[ ![themodus_generic_search_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_search_16x16.png) | Inzoomen ]** kunt u ook inzoomen in de actieve view. Aan de rechterzijde de eigenschappen van iedere aanvraag onderverdeeld in BIM eigenschappen en typische sparing acties. Aan de bovenzijde zijn filteropties beschikbaar. De filtermogelijkheden zijn:
- Per vorm.
  - Activeer **[] Rond (#)** om de ronde sparingen te zien in de lijst.
  - Activeer **[] Recht (#)** om de rechthoekige sparingen te zien in de lijst.  
- Per type sparing.
  - Activeer **[] Wand (#)** om de wandsparingen te zien in de lijst.
  - Activeer **[] Vloer (#)** om de vloersparingen te zien in de lijst.
  - Activeer **[] Dak (#)** om de daksparingen te zien in de lijst.  
- Per aanvraag.
  - Activeer **[] Nieuw (#)** om alleen nieuwe aanvragen te zien in de lijst.
  - Activeer **[] Bestaand (#)** om alleen bestaande aanvragen te zien in de lijst.
  - Activeer **[] Gewijzigd (#)** om alleen gewijzigde aanvragen te zien in de lijst.
  - Activeer **[] Verwijderd (#)** om alleen verwijderde aanvragen te zien in de lijst. 

Afhankelijk van uw rol kunt u hier alle informatie verwerken per sparing. Het formulier ondersteunt het bewerken van meerdere aanvragen in één handeling. Voor meer informatie over het verwerken van de eigenschappen zie het artikel 'Verwerken aanvraag specificaties'.

Ervan uitgaande dat de aanvragen alleen gedetecteerd moeten worden, kunnen de aanvragen nu in het model worden opgeslagen. 

Onder **'Genereren'** in de tabel ziet u dat alle nieuwe sparingen zijn geactiveerd.

_Wijzigingen van aanvragen worden alleen verwerkt als **'Genereren'** is geactiveerd* ( **[✓]** )_

**Werkwijze voor het verwerken van sparingsaanvragen:**
- Controleer dat alle aanvragen welke verwerkt moeten worden zijn geactiveerd **[✓]** onder **'Genereren'**.
- Klik **[ AANVRAAG VERWERKEN | > ]**
_De aanvragen zijn verwerkt als de lijst leeg is_
- Klik **[ AFSLUITEN ]** om het formulier te sluiten.

Voor alle aanvragen wordt nu een aanvraag object geplaatst in het model met daarin alle noodzakelijke informatie.