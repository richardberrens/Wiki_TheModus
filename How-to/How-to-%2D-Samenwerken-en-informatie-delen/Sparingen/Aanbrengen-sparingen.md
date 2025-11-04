# **Aanbrengen sparingen**
Het detecteren en verwerken van de sparingaanvragen heeft uiteindelijk als doel het aanbrengen van de juiste sparingen op de juiste plaats. Als eerste moet dat in het BIM model gebeuren. Dit ter voorbereiding van het aanbrengen van de sparingen op de bouwplaats. Meestal betreft dit een groot aantal sparingen, welke aangebracht moeten worden in verschillende modellen. 

'TheModus Sparingen' ondersteunt het genereren van de feitelijke sparingen in de modellen. Zowel bij de kleinere projecten, waar coördinatie en model in één zijn, alsmede de grotere projecten waar gebruikt gemaakt wordt van aspectmodellen. Als alle aanvragen zijn verwerkt kunnen de aanvragen met een goedgekeurde status verwerkt worden tot sparing. 

In geval van één coördinatie model en verschillende aspectmodellen dupliceert 'TheModus Sparingen' alleen de van toepassing zijnde aanvragen, en gebruikt vervolgens de aanvragen om deze om te zetten tot sparing. 

'TheModus Sparingen' genereert alleen sparingen als deze van het type **"Aanleveren"** of **"Kisten"** zijn. De overige typen worden namelijk als nabewerking op de bouwplaats uitgevoerd. 

Tevens genereert 'TheModus Sparingen' alleen sparingen als deze de BIM status **"Goedgekeurd"** hebben. De BIM Status **"Goedgekeurd"** is gekoppeld aan de 'Status voor verwerken' **"Gereed voor verwerken"** in het Sparing aanvraag instellingen formulier.

Als een aanvraag eenmaal is verwerkt tot sparing, dan wordt bij de eerst volgende coördinatie de status **"Gereed voor verwerken"** gewijzigd naar **"Verwerkte sparing"**. De omschrijving van de BIM status kan daarbij afwijken. Dit is afhankelijk van de configuratie. Eenmaal verwerkte sparingen kunt u met behulp van de filters tonen of verbergen.

Voordat de feitelijke aanvraag wordt verwerkt tot sparing, wordt gecontroleerd of de bouwkundige kenmerken overeenkomen met de kenmerken van het actuele aspectmodel. Als deze afwijken worden geen sparingen gemaakt. De status veranderd niet. In deze situatie is het aannemelijk dat het coördinatie model niet correct is gelinkt in het aspectmodel.

**Werkwijze voor het verwerken van aanvragen tot sparing:**
- Indien er sprake is van een aspectmodel, link het coördinatiemodel aan het aspectmodel;
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen  ]** > **[ ![themodus_prof_button_addin_productivity_tools_openings_cut_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_openings_cut_16x16.png) | Genereer sparingen ]**;
_Het formulier 'Sparing aanvragen' wordt geopend met het tabblad '1. AANVRAGEN DETECTEREN' actief;_
_Er wordt een lijst getoond met alle mogelijk te verwerken aanvragen. Deze lijst werkt interactief met de actieve view._
_Controleer de te verwerken aanvragen._
- Selecteer de gewenste aanvragen (houdt de **<CTRL>** toets ingedrukt);
- Klik **[ OK ]**
_De procedure start._
_Als de procedure klaar is wordt de lijst met gegenereerde sparingen getoond._
- Klik **[ EXPORTEER ]** om de lijst op te slaan als Excelbestand;
  - Geef een bestandsnaam en opslaglocatie.
  - Klik **[ Opslaan ]**

  _of_
- Klik **[ OK ]** om af te sluiten.