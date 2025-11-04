# **Maatvoering element ordinaat**
De werkstroom 'Maatvoering element ordinaat' voorziet ieder afzonderlijk element van maatvoering. Echter ligt de focus niet op de afmetingen van de elementen, maar de positie van de elementen, en wel ten opzichte van een nulpunt. Volgens deze werkstroom worden overzichtstekeningen van elementen voorzien van maatvoering. Een typisch voorbeeld is een installatietekening voor schakelmateriaal.

**Werkwijze voor het maatvoeren van een element:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_documentation_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_16x16.png) | Documentatie ]** > **[ ![themodus_prof_button_addin_productivity_documentation_dimensioning_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_dimensioning_16x16.png) | Maatvoering  ]**;
- Selecteer een sjabloon welke behoort bij de werkstroom.
De bouwer van de sjablonen zal de sjablonen doorgaans een naam geven welke verwijst naar het proces, en niet naar de specifieke werkstroom;
- Maak een selectie van de te maatvoeren elementen, kies:
  - **'Actieve view'** om alle elementen op te sporen welke voldoen aan de criteria zoals ingericht in het sjabloon. Alle elementen die voldoen worden voorzien van maatvoering;
  - **'Selectie'** als u zelf een selectie wilt maken in de actieve view van elementen. Zodra de procedure wordt gestart, wordt u gevraagd de elementen te selecteren.
    - Klik **[ ![themodus_generic_finish_28x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_finish_28x16.png) | Finish ]** als de selectie volledig is;
  - **'Lijst van views'** om alle elementen op te sporen welke voldoen aan de criteria zoals ingericht in het sjabloon in alle geselecteerde 'Views'.
    - Klik **[ ![themodus_generic_select_file_21x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_select_file_21x16.png) | Selecteer views om te maatvoeren ]** om de views te selecteren.
    - Selecteer alle views, klik **[ OK ]**
- U kunt ook de elementen in linked files voorzien van maatvoering. Activeer **[] 'Inclusief elementen in linked file (vertragend!)'** om linked files mee te nemen.
**Let op!** De linked files worden apart geanalyseerd, en werkt als gevolg vertragend.
- Geef bij **'Bestaande maatvoering'** aan wat er moet gebeuren met eerder geplaatste maatvoering door 'TheModus Dimensions'. Kies:
  - **'<geen>'** als bestaande maatvoering niet moet worden geanalyseerd. Er worden dan nieuwe maatvoering bijgeplaatst.
  - **'Verwijder eerder geplaatste maatlijnen van element'** als bestaande maatvoering moet worden verwijderd voordat de nieuwe wordt aangebracht.
  - **'Element overslaan bij dimensioneringsactie'** als bestaande maatvoering moet worden behouden. Het element wordt dan overgeslagen. Er wordt alleen bij nieuwe elementen een maatlijn geplaatst.
- Geef bij **'Positie maatvoering'** aan op welke positie ('Boven', 'Onder', 'Links', 'Rechts') t.o.v. het gekozen object de maatvoering geplaatst moet worden. Alle combinaties zijn mogelijk.
- Geef bij **'Gelijke Maten'** aan of gelijke maten binnen een bepaalde afstand ten opzichte van elkaar dubbel geplaatst mogen worden of niet. Geef daarbij de afstand op. (in meters)
- Klik **[ STARTEN ]**
_De maatvoering wordt aangebracht bij de gekozen elementen in de gekozen views._

**Tip:**
- Er zijn meerdere methoden om te maatvoeren ten opzichte van meerdere nulpunten:
- Maak gebruik van scope boxen en maak voor iedere scope box een aparte view. De procedure zoekt in iedere view naar een nulpunt voor de maatvoering. 
- Geef aan de hand van een parameter op welke elementen bij welk nulpunt horen. Deze parameter moet in het sjabloon zijn gemarkeerd!