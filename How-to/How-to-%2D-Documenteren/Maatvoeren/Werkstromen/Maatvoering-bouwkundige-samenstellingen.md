# **Maatvoering bouwkundige samenstellingen**
De werkstroom 'Bouwkundige samenstellingen' is vooral voor de bouwkundigen en constructeurs. Deze werkstroom maakt het mogelijk om prefab elementen inclusief onderdelen in deze elementen te voorzien van maatvoering. De werkstroom wordt vooral bedoeld voor de productie van prefab) wanden en vloeren.

**Werkwijze voor het maatvoeren van prefab:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_documentation_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_16x16.png) | Documentatie ]** > **[ ![themodus_prof_button_addin_productivity_documentation_dimensioning_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_dimensioning_16x16.png) | Maatvoering  ]**;
- Selecteer een sjabloon welke behoort bij de werkstroom. De bouwer van de sjablonen zal de sjablonen doorgaans een naam geven welke verwijst naar het proces, en niet naar de specifieke werkstroom;
- Maak een selectie van de te maatvoeren elementen, kies:
  - **'Actieve view'** om alle elementen op te sporen welke voldoen aan de criteria zoals ingericht in het sjabloon. Alle elementen die voldoen worden voorzien van maatvoering;
  - **'Selectie'** als u zelf een selectie wilt maken in de actieve view van elementen. Zodra de procedure wordt gestart, wordt u gevraagd de elementen te selecteren.
    - Klik **[ ![themodus_generic_finish_28x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_finish_28x16.png) | Finish ]** als de selectie volledig is;
  - **'Lijst van views'** om alle elementen op te sporen welke voldoen aan de criteria zoals ingericht in het sjabloon in alle geselecteerde 'Views'.
    - Klik **[ ![themodus_generic_select_file_21x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_select_file_21x16.png) | Selecteer views om te maatvoeren ]** om de views te selecteren.
    - Selecteer alle views, klik **[ OK ]**
- U kunt ook de elementen in linked files voorzien van maatvoering. Activeer **[] 'Inclusief elementen in linked file'** om linked files mee te nemen.
**Let op!** De linked files worden apart geanalyseerd, en werkt als gevolg vertragend.
- Geef bij **'Bestaande maatvoering'** aan wat er moet gebeuren met eerder geplaatste maatvoering door 'TheModus Dimensions'. Kies:
  - **'<geen>'** als bestaande maatvoering niet moet worden geanalyseerd. Er worden dan nieuwe maatvoering bijgeplaatst.
  - **'Verwijder eerder geplaatste maatlijnen van element'** als bestaande maatvoering moet worden verwijderd voordat de nieuwe wordt aangebracht.
  - **'Element overslaan bij dimensioneringsactie'** als bestaande maatvoering moet worden behouden. Het element wordt dan overgeslagen. Er wordt alleen bij nieuwe elementen een maatlijn geplaatst.
- Geef bij **'Positie maatvoering'** aan op welke positie ('Boven', 'Onder', 'Links', 'Rechts') t.o.v. het gekozen object de maatvoering geplaatst moet worden. Alle combinaties zijn mogelijk.
- Geef bij **'Korte lijnen'** aan of lijnen die op zeer korte afstand ten opzichte van elkaar liggen een maatlijn moeten krijgen, of niet. Geef bij **'Minimale lengte'** de gewenste afstand op tussen de lijnen. Lijnen korter dan deze afstand op elkaar krijgen dan geen maatlijn.
- Klik **[ Starten ]**
_De maatvoering wordt aangebracht bij de gekozen elementen in de gekozen views._