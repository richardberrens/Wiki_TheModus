# **Inrichten sparing objecten voor verschillende sparing typen en constructies**
Iedere sparing kent specifieke eigenschappen waardoor verschillende sparingsoplossingen noodzakelijk zijn in een gebouw. Sparingen zijn bijvoorbeeld afhankelijk van de constructie, of van brandwerende eigenschappen. 

'TheModus Sparingen' houdt bij de analyse naar sparingverzoeken rekening met diverse kenmerken welke van invloed zijn op de keuze van een sparing. Afhankelijk van de kenmerken van de clashes kan 'TheModus Sparingen' verschillende sparingobjecten plaatsen. De afhankelijke kenmerken zijn: 
- De vorm van de clash;
- De categorie van de installatie;
- Het systeem type;
- De categorie van de bouwkundige constructie;
- Het type bouwkundig object;
- Het materiaal van het bouwkundig object;
- De brandwerendheid van het bouwkundig object.

Afhankelijk van deze kenmerken kunnen voor ieder sparingobject de volgende zaken worden ingesteld:
- Het gewenste sparing object;
- Tolerantie rondom de sparing;
- Roteerbaarheid rondom de x-as en/of y-as;
- Gebruik van de peilmaat;
- Welke afwerking erbij geplaatst moet worden;
- Het nummer voorzien van een voorvoegsel.

Verder kunt u de toegestane afwijking van de rondheid in percentage aangeven. Deze bepaalt in welke mate bij schuin geplaatste ronde leidingen door een constructie er een rond of rechthoekig sparingobject geplaatst moet worden. 

Als eenmaal sparingobjecten zijn geplaatst en er vind een nieuwe analyse plaats, dan kunt u afdwingen dat de bestaande sparingdata wordt gehandhaafd.

**Werkwijze voor het inrichten van een definitie voor het plaatsen van een sparingobject:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen  ]** > **[ ![themodus_prof_button_addin_productivity_tools_openings_request_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_openings_request_16x16.png) | Sparing aanvragen ]**;
_Het formulier 'Sparing aanvragen' wordt geopend met het tabblad '1. AANVRAGEN DETECTEREN' actief;_
- Klik op **[ ![themodus_generic_configure_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_configure_16x16.png) | Instellingen ]**
_Het formulier 'Instellingen sparing' wordt geopend;_
- Activeer het tabblad **'Algemeen'**
- Bepaal de toegestane afwijking van de rondheid in procenten: Geef bij **'Toegestane afwijking rondheid in %'** het gewenste percentage op. 
_De standaard waarde is 17%. Deze waarde is tot stand gekomen in overleg met meerdere installateurs en constructeurs;_
- Bepaal of bestaande data gehandhaafd moet blijven bij nieuwe analyses:
Activeer **'Bij herberekenen bestaande afmeting handhaven' []** indien de oorspronkelijke data gehandhaafd moet blijven;
- Een nieuwe sparingdefinitie toevoegen:
  - Geef de voorkeurs eigenschappen van de sparing op:
    - Selecteer onder **'Type sparing'** de vorm van de verwachte sparing;
    - Type onder **'Sparing family'** de naam van het sparingcomponent welke gebruikt moet worden bij de opgegeven specificatie.
**Let op!** 
Bij zelf gemaakte objecten moet het pad worden opgegeven waar de objecten staan!
Zie artikel 'Overige instellingen' en tabblad 'Bestand'.
    - Geef de tolerantie op tussen de buis en de constructie. 
      - Geef onder **'Extra ruimte Diam/Breedte'** de extra marge op in mm. 
In geval van een ronde sparing wordt de sparingmaat de diameter van de buis vermeerderd met 2x deze waarde. 
In geval van een rechte sparing wordt de breedte van de buis vermeerderd met 2x deze waarde; 
      - Geef onder **'Extra ruimte hoogte'** de extra marge op in mm.
In geval van een rechte sparing wordt de hoogte van de buis vermeerderd met 2x deze waarde; 
    - Geef de roteerbaarheid van de sparing op. 
      - Activeer **'Om x-as draaibaar'** als het object om de x-as geroteerd mag worden;
      - Activeer **'Om y-as draaibaar'** als het object om de y-as geroteerd mag worden;
    - Geef aan of de peilmaat gebruikt moet worden.
Activeer **'Gebruik "Peilmaat" parameter'** als de peilmaat ten opzichte van de verdieping gebruikt moet worden. De maten worden dan bepaald op basis van het project waarin de aanvragen worden verwerkt.
    - Type onder **'Afwerking'** de gewenste afwerking bij deze sparingdefinitie.
Deze overschrijft een eventueel algemeen opgenomen afwerking bij het type sparing.
_Zie artikel 'Inrichten gewenste afwerking per type sparing' en tabblad **'Afwerking'**;_
    - Type onder **'NummerPrefix'** een kenmerk welke voor het sparingnummer wordt geplaatst.
  - Geef de analyse criteria op (de grijze velden). Deze velden mogen leeg blijven. De analyse vindt dan plaats over alle objecten. Een waarde invoeren in deze velden gebeurd op basis van een tabel. Klik in het veld met de rechter muis knop en vul de gewenste waarden in.
    - Type onder **'Installatie categorie'** de exacte naam van de categorie van de installatie welke de clash veroorzaakt;
    - Type onder **'Systeem type'** de exacte naam van het systeem type van de installatie welke de clash veroorzaakt;
    - Type onder **'Bouwkundige categorie'** de exacte naam van de categorie van de bouwkundige constructie waarmee wordt geclasht;
    - Type onder **'Bouwkundige type'** de exacte type naam van de bouwkundige constructie waarmee wordt geclasht;
    - Type onder **'Bouwkundig materiaal'** de exacte naam van het materiaal van de bouwkundige constructie waarmee wordt geclasht;
    - Type onder **'Brandwerendheid'** de exacte waarde van de brandwering van de bouwkundige constructie waarmee wordt geclasht. Deze wordt opgezocht in een parameter brandwering.
_Zie artikel 'Inrichten gebruik parameters voor brandwering' en tabblad **'Brandwerendheid'**;_
- Klik **[ Accepteren ]** om alle instellingen op te slaan en te accepteren.