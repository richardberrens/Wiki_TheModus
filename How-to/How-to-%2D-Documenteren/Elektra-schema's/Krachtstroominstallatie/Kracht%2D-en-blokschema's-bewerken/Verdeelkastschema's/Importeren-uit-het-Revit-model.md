# **Importeren van gegevens uit het Revit model**
'TheModus E-Schema' maakt gebruik van de BIM data. Derhalve is de eerste stap bij het genereren van schema's het ophalen van de BIM data
vanuit het Revit model. 

Het importeren van de BIM data werkt alleen als het BIM model voldoet aan de voorwaarden. Zie artikel *'Voorbereiding BIM-model'*. 

Het importeren start met enkele controles. 
- Als er ingelezen 'Electrical Circuits' zijn, waarbij de shared parameter 'vermogensclassificatie' bij elementen ontbreekt, dan wordt hier een melding van gegeven. De gebruiker kan de import dan nog afbreken. Als de import wordt doorgezet worden de bewuste elementen NIET meegeteld. 

Vervolgens gebeuren de volgende acties:  
- Kasten met dezelfde kastnaam worden bij het importeren in 'TheModus E-Schema' samengevoegd indien de optie **[ Gelijknamige kasten samenvoegen bij import ]** in de instellingen van 'TheModus E-Schema' is aangevinkt. Elk van deze kasten wordt op een aparte voeding geplaatst. Tijdens de import kan een melding worden weergegeven dat één of meer kasten niet konden worden samengevoegd. Dit treedt bijv. op als de samengevoegde kast meerdere groepen zou bevatten met dezelfde code. Er kan dan nog worden gekozen om de import af te breken. Als de import wordt doorgezet worden deze kasten afzonderlijk ingelezen. De instelling voor samenvoegen die is gebruikt bij de import wordt na het importeren als projectinstelling binnen het E-Schema project opgeslagen. Mocht het schema naderhand nog ge-update worden met recentere data uit het Revit model, dan gebruikt de 'Update' functie deze projectinstelling voor bij het opnieuw inlezen van de kasten (ongeacht wat er op dat moment in het instellingen-dialoogvenster is ingevuld).
- De eigenschappen 'voedende kast' en 'voedende groep' van de kast in het BIM model worden bij importeren doorgegeven aan de eigenschappen 'vanaf kast' en 'vanaf groep' van de voeding waar de groepen van de kast op worden geplaatst;
- De vermogens van de kast worden doorgerekend naar de voedende groep van de kast;
- Groepen die via het 'Panel Schedule' als 'Spare' zijn aangemerkt worden als 'Reserve' groep ingelezen;
- Na het importeren worden de standaard families voor voedingen en groepen toegepast zoals ingesteld in het 'Instellingen dialoogvenster';
- De 'load classification types' uit het BIM model worden ingedeeld in vermogensclassificatie categorieën die worden weergegeven op het schema. In de TheModus template staan 'load classification types' die standaard onder één van deze categorieën vallen. De vermogensclassificatie categorieën (met daarachter de standaard 'load classification types') zijn:
  - Noodverlichting: (load classification types "NV", "TP")
  - Verlichting: (load classification types "TL", "GL", "PL")
  - WCD: (load classification types "WCD", "WCD2")
  - WCD_Kracht: (load classification types "WCD4")
  - ASP: (load classification types "ASP")
  - ASP_Kracht: (load classification types "ASP4")

Eigen 'load classification types' kunnen op twee manieren aan een vermogensclassificatie categorie worden toegevoegd:
- Door deze op te nemen in het bestand ESchemaSettings.xml
- Door de naamgeving zodanig te kiezen, dat deze automatisch onder één van de vermogensclassificatie categorieën valt. Het format hiervoor is : - (bijv. "ASP_Kracht-wcds").

Als een 'load classification type' van een element niet op één van de bovenstaande manieren is onderverdeeld bij een vermogensclassificatie categorie, dan worden de vermogens hiervan alleen bij de totalen opgenomen. In de 'load classification' tabel op de sheet worden deze vermogens weergegeven bij 'Overige'.