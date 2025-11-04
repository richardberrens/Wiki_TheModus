# **Coördineren en verwerken aanvraag specificaties**
Als alle sparingaanvragen zijn gedetecteerd en vastgelegd kan het coördinatie proces starten. Dit bestaat uit het delen van de sparinginformatie, het voorbereiden van coördinatie overleggen en het verwerken van de resultaten uit deze overleggen.

'TheModus Sparingen' ondersteunt uiteraard niet in het beleggen van de coördinatie vergaderingen, maar ondersteunt wel in het treffen van de noodzakelijke voorbereidingen en het verwerken van de resultaten.

Ter voorbereiding van de coördinatie vergaderingen zijn er 2 mogelijkheden.

1. U deelt de BIM modellen met elkaar. Alle informatie van de sparingen is toegevoegd aan de aanvraagobjecten. Hierin ondersteunt 'TheModus Sparingen' niet, maar kan het best via Autodesk BIM360 gefaciliteerd worden;
2. U maakt een data extractie van alle aanvragen, en deelt deze per email met alle betrokkenen. Dit is zeker noodzakelijk voor alle partijen die geen beschikking hebben over alle BIM tools. Doch is dit ook voor de BIM partijen vaak gewenst, zodat ze een extra checklist bij de hand hebben. Met 'TheModus Sparingen' kunt u eenvoudig een Excel sheet genereren met daarin alle aanvraag informatie.

**Werkwijze voor het exporteren van alle aanvraag data naar Excel:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen  ]** > **[ ![themodus_prof_button_addin_productivity_tools_openings_request_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_openings_request_16x16.png) | Sparing aanvragen ]**;
_Het formulier 'Sparing aanvragen' wordt geopend met het tabblad '1. AANVRAGEN DETECTEREN' actief;_
- Klik **[ AANVRAGEN DETECTEREN | > ]**
_In dit geval gaan we ervan uit dat de aanvragen reeds zijn gedetecteerd en verwerkt. In het volgende formulier worden alle aanvragen als 'Bestaand' weergegeven._
- Klik **[ ![themodus_generic_share_14x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_share_14x16.png) | Gegevens delen  ]**
  - Geef de locatie en naam op waar u het bestand wilt opslaan.
  - Klik **[ Opslaan ]**
_Dit Excel bestand kunt u nu verdelen onder uw teamleden._
  - Klik **[ OK ]**
  - Klik **[ Annuleer ]** om het formulier af te sluiten.

Gedurende de coördinatie vergaderingen worden de aanvragen individueel of in bulk behandeld. De BIM coördinator gebruikt de beschikbare filters om de lijst met sparingen overzichtelijk te houden. In de lijst kunnen meerdere aanvragen geselecteerd worden, zodat deze in één handeling behandeld kunnen worden. Ook kan de informatie in de lijst gesorteerd worden door te klikken op de kolomkoppen.

**Werkwijze voor het verwerken van de resultaten van de aanvragen:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_tools_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_16x16.png) | Hulpmiddelen  ]** > **[ ![themodus_prof_button_addin_productivity_tools_openings_request_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_tools_openings_request_16x16.png) | Sparing aanvragen ]**;
_Het formulier 'Sparing aanvragen' wordt geopend met het tabblad '1. AANVRAGEN DETECTEREN' actief;_
- Klik **[ AANVRAGEN DETECTEREN | > ]**
_In dit geval gaan we ervan uit dat de aanvragen reeds zijn gedetecteerd en verwerkt. In het volgende formulier worden alle aanvragen als 'Bestaand' weergegeven._
- Activeer **[ ✓ ]  Aanvraag (#)** onder **'BIM STATUSSEN'**
- Selecteer één of meerdere aanvragen;
- Onder **'BIM INFORMATIE'** vindt u alle installatietechnische en bouwkundige informatie van de aanvraag. Hier zijn ook de coördinaten van de aanvraag en het Revit identificatienummer beschikbaar van het aanvraag object. U kunt hier geen wijzigingen aanbrengen. De informatie volgt allemaal uit het BIM model;
- Onder **'SPARING ACTIES'** kunt u alle specificaties opgeven en bepalen hoe de sparing gemaakt moet worden, te weten:
  - **Nummer**: Dit is het nummer van de aanvraag. Dit nummer wordt automatisch gegenereerd bij het detecteren van de aanvragen. U kunt dit nummer overschrijven. Dubbele nummers zijn toegestaan. Echter wordt er een waarschuwing getoond bij de aanvragen die een dubbel nummer hebben;
  - **BIM status**: In dit veld beheerd de BIM coördinator de status van de aanvraag. De inhoud van de lijst is configurabel. Voor iedere status kunnen de aanvraag objecten voorzien worden van een andere kleur;
De standaard statussen zijn:
    - Aanvraag
    - Gewijzigd
    - Afgekeurd
    - Goedgekeurd
    - Gerealiseerd
    - Vervallen
  - **Commentaar**: Hier kan de BIM coördinator commentaar toevoegen voor aanvragen, of aantekeningen maken welke nodig zijn als een sparing extra aandacht behoeft;
  - **Sparingverzoek door**:  Hier wordt de naam van de aanvrager getoond. Dit veld kan eventueel gewijzigd worden;
  - **Aanvraagdatum**:  Hier wordt de datum van de aanvraag getoond. Dit veld kan eventueel gewijzigd worden; 
  - **Afwerking**: Hier wordt de standaard afwerking van de sparing weergegeven. Deze is afkomstig uit de configuraties. De BIM coördinator kan deze waarde vervangen. Hier kan geselecteerd worden uit een lijst afwerkingen. Er kan ook een afwijkende waarde worden ingevuld.
  - **Clash afmeting**: Hier worden de exacte afmetingen van de clash getoond. Deze waarden komen uit het model en kunnen niet worden gewijzigd.
  - **Tolerantiewaarde**: Hier wordt de standaard tolerantie opgegeven zoals geconfigureerd. De BIM coördinator kan hier afwijkende waarden opgeven. 
_In geval van een ronde sparing wordt de sparingmaat de diameter van de buis vermeerderd met 2x deze waarde. 
In geval van een rechte sparing wordt de breedte/hoogte van de buis vermeerderd met 2x deze waarde;_
  - **Berekende afmeting**: Geeft de sparingmaat op, op basis van de clash afmetingen en de tolerantie, of indien een staffel van toepassing wordt hier de maat van de staffel opgegeven.
  - Activeer **Geboord ()** als de sparing geboord moet worden;
  - Activeer **Boorzone ()** als er geen sprake is van een sparing, maar van een boorzone, waar later eventueel een sparing gemaakt kan worden;
  - Activeer **Aanleveren ()** als er voor de sparing een mal aangeleverd wordt;
  - Activeer **Kisten ()** als er een bekisting gemaakt moet worden voor de sparing;
- Vervolgens moet de BIM coördinator een keuze maken:
  - Activeer **(●) 'Advies afmeting'** indien de berekende waarden gebruikt moeten worden.
  - Activeer **() 'Staffel afmeting'** en geef de gewenste staffel waarde indien de vooringestelde staffelwaarden gebruikt moeten worden. 
  - Activeer **() 'Specifieke afmeting'** en geef de gewenste afmetingen (diameter/breedte en hoogte) indien zelf gekozen afmetingen gebruikt moeten worden.
- Als alle informatie van de aanvraag is verwerkt klikt de BIM coördinator **[ Aanvraag voorbereiden | > ]**
_De informatie wordt dan in het geheugen opgeslagen. In de lijst aanvragen wordt het veld_ **[ ✓ ] Genereren** _geactiveerd, zodat de data verwerkt wordt in het model na klik_ **[ AANVRAAG VERWERKEN | > ]**
- Zodra alle kenmerken van de aanvragen zijn opgegeven, klikt de BIM coördinator **[ AANVRAAG VERWERKEN | > ]**
_Alle aanvragen waarbij_ **[ ✓ ] Genereren**  _geactiveerd is worden dan vervolgens in het BIM model verwerkt._
- Klik **[ Sluiten ]** om het venster te sluiten.

**Opmerking**
- Bij een detectie wordt geanalyseerd of er duplicaat nummers voorkomen. Deze worden meteen weergegeven in de waarschuwing.
- Bij een detectie worden gewijzigde diameters meteen weergegeven in de waarschuwingen. Selecteer de aanvraag (of aanvragen). Controleer de nieuwe specificaties. Klik **[ Aanvraag voorbereiden | > ]**.
De wijziging wordt vervolgens definitief verwerkt als aanvraag verwerkt wordt.
- Zodra u werkt met gelinkte modellen mogen na detectie deze modellen niet meer verplaatst worden. U kunt de positie van de gelinkte modellen vastpinnen op de locatie.