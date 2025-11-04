# **Genereren Dyka Vacurain Fix Beugels**

Ophangen van leidingen aan een plafond of een wand is een tijdrovend proces. Er moet nauwkeurig bepaald worden wat de juiste beugelafstanden zijn, de lengte van de beugels, de diameters van de beugels en nog veel meer. BIM kan hierin ondersteunen door de beugels te modelleren, echter is dit ook een tijdrovende klus. 

Cadac heeft samen met Walraven een routine ontwikkeld voor het eenvoudig modelleren van de beugels. Een routine voor het Dyka Vacurain Fix Systeem. Deze routine is ook beschikbaar in TheModus.

De beugelfunctie voor Dyka Vacurain Fix ondersteunt in de volgende onderdelen:

1.  Koppelen van beugels, gebaseerd op vaste regels m.b.t. maximale onderlinge afstanden per diameter en afstanden tot aan hulpstukken;
2.  Het hangen van de beugels aan bevestigingsrails welke worden opgesplitst op maximale lengte;
3.  Het koppelen van ophang ankers aan de rails naar het eerst hogere level;
4.  Het bijwerken van de geplaatste beugels wanneer de leidingdiameter gewijzigd is;
5.  Inregelen van de beugelinstellingen.

De belangrijkste voordelen op een rijtje:
- Plaatsen beugels volgens de richtlijnen van de fabrikant;
- Leiding, beugels, rails en ankers zijn aan elkaar gekoppeld zodat bij verplaatsen leiding de beugels e.d. mee verplaatsen;
- Tijdsbesparing in het toekennen van beugels;

**Werkwijze voor het beugelen van Dyka Vacurain Fix leidingen:**
- Selecteer eventueel vooraf de te beugelen leidingen.

- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![Beugeling.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_bracketing_16x16.png) | Beugeling]** > **[ ![Genereer Vacurain beugels.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_bracketing_generate_16x16.png) | Genereer Vacurain beugels]**;
- Indien er geen voorselectie was wordt nu gevraagd een selectie in het model te maken.
  - Bevestig keuze met [ ![Finish.png))](https://download.cadac.com/themodus/manual/themodus_revit_finish_28x16.png) | Finish]
  - De beugels, rails en ankers worden toegevoegd aan het model. 

**Werkwijze voor het wijzigen van beugels:**
- Ga naar de knoppenbalk **[ Cadac Revit ]**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![Beugeling.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_bracketing_16x16.png) | Beugeling]** > **[ ![Instellingen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_bracketing_settings_16x16.png) | Instellingen]**;
_U krijgt een dialoog met de instellingen voor het beugelen:_
- Op het tabblad **'Beugel instellingen'** kunnen de onderstaande instellingen gedaan worden:
  - Per leidingdiameter:
    - De maximale beugelafstand;
    - De gewenste railafmeting;
    - De maximale vastpunt afstand;
    - De maximale afstand tussen ankers;
    - Het type beugel welke default moet worden toegepast;
    - Het type anker welke default moet worden toegepast.
  - Verder zijn er nog een 3 tal globale instellingen te maken;
    - De standaard afstand van een beugel tot een hulpstuk verbinding;
    - De minimale afstand tussen een anker en een beugel;
    - De maximale anker afstand tot een vastpunt beugel.
- Op het tabblad **'Onderdeel mapping'** kan per type onderdeel de gewenste family, type en eventueel bepalende parameters ingesteld worden.
  - Wanneer er van de default family instellingen wordt afgeweken dan dient de modelleur zelf zorg te dragen dat deze families en typen in het model geladen zijn voordat de beugelfunctie wordt gestart.
- Klik **[ OK ]** om de wijzigingen op te slaan en het formulier te verlaten.
