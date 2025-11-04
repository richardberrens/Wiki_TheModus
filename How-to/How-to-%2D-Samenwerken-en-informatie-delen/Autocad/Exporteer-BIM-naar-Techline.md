# **Exporteer BIM naar Techline**
Vele bedrijven maken voor hun prefab oplossingen gebruik van Techline Prefab. Als bron wordt dan het BIM model gebruikt.
Met 'Exporteer Techline' kunnen BIM modellen geëxporteerd worden naar Techline.

**Werkwijze voor het exporteren van een BIM-model:**
- Open/activeer een floorplan of een 3D view.
- Selecteer de objecten die u wenst te exporteren naar AutoCAD/Cadac Techline;
  - Zweef met de muis over een leidingdeel zodat deze blauw wordt;
_Met 3 keren klikken op de **<TAB>**-knop kunt u een geheel leidingsysteem selecteren._
  - Klik met linkermuisknop als alles blauw is.
  - U kunt ook eerst de functie activeren en daarna een 'Window' of 'Crossing' doen
_of_
  - eerst selecteren en daarna de functie activeren,
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen ]**; > **[ ![themodus_prof_button_addin_productivity_tools_techline_export_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_techline_export_16x16.png) | Exporteer Techline ]**; 
_Er wordt nu een koppeling gelegd met de Techline database en er volgt een dialoogvenster: 'Mapping project/template gegevens met TheModus database' met daarin 3 tabbladen waarin eventueel nog veranderingen kunnen worden aangebracht:_
  - Leidingsystemen: in het pulldownmenu "TheModus leidingsysteem" kunt u kiezen voor een ander leidingsysteem.
  - Leiding typen: in het pulldownmenu "TheModus leidingtype" kunt u kiezen voor een ander leidingtype.
  - Materialen: in het pulldownmenu "Database leidingmateriaal" kunt u kiezen voor een ander materiaal.
- Klik **[ OK ]**
- Selecteer de gewenste locatie waar het mmex-bestand opgeslagen moet worden.
- Klik **[ Opslaan ]**

In AutoCAD/Cadac Techline volgt u nu onderstaande stappen voor het importeren van het BIM model:
- Activeer het commando **[ Importeer TheModus model ]** op het tabblad: Algemeen > Support
_of_
 tik in op de commandoregel: **TLIMPORT**
- Browse naar de locatie waar het mmex-bestand is opgeslagen, selecteer het bestand.
- Klik **[ Openen ]**
_Vervolgens worden de pipetypes ingeladen en omgezet naar Techline leidingsysteem._
- Het project basepoint komt overeen met het nulpunt van de tekening.
- De hoogtes van de leidingen worden overgenomen.
- Als de import niet alle aansluitingen heeft kunnen maken, dan wordt hiervan melding gemaakt. Klik:
  - **[ Ja ]** om een rapportage te tonen. 
_Een lijst wordt getoond met de locaties (x,y,z- coördinaat) waar de aansluitingen niet via de importprocedure gemaakt konden worden. De gebruiker kan dan zelf de betreffende locatie bekijken en eventueel met Techline functies de gewenste aansluitingen alsnog maken._
  - **[ Nee ]** om de rapportage niet te tonen.
- Controleer altijd of het leidingsysteem/de onderdelen, op de juiste positie zijn ingeladen.
- Verplaatst eventueel de objecten, met het correcte insertiepunt/nulpunt naar juiste positie/bouwlaag in AutoCAD.

**Opmerking**
Een 3D model o.b.v. Revit TheModus. Overige standaard Revit-objecten worden 1 op 1 overgenomen zonder verdere route intelligentie.