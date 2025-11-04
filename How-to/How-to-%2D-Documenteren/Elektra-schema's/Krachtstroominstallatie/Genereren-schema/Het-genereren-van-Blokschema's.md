# **Het genereren van Blokschema's**
Volg onderstaande stappen voor het genereren van een verdeelkastschema:
- Zorg ervoor dat 'TheModus E-schema' is geopend.
- Zorg ervoor dat het project is geopend en/of ingericht.
- Selecteer welke blokschema's te genereren. Er zijn een aantal mogelijkheden:
  - Blokschema genereren voor gebouw. Er is nog geen blokschema gegenereerd:
    - Klik **[ ![themodus_prof_escheme_create_blockscheme_18x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_escheme_create_blockscheme_18x16.png) | Blokschema genereren ]**
_Er volgt een melding" Het blokschema is gegenereerd op drafting view 6-_DV_Blokschema - <kast1> + <kast2> enz."._
    - Klik **[ OK ]**
  - Bestaand blokschema updaten voor gebouw. Er is reeds eerder een schema gegenereerd. U wilt het bestaande schema updaten. 
    - Klik **[ ![themodus_prof_escheme_create_blockscheme_18x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_escheme_create_blockscheme_18x16.png) | Blokschema genereren ]**
_Er volgt een melding: "View '6-_DV_blokschema - <kast1> + <kast2>' bestaat al. Schema op 6-_DV_blokschema - <kast1> + <kast2> vervangen?"._
Klik:
      - **[ Ja ]**
_Er volgt een melding: "Het blokschema is gegenereerd op drafting view 6-_DV_Blokschema - <kast1> + <kast2>"._
        - Klik **[ OK ]**
_Het bestaande schema wordt vervangen. Eventueel handmatig toegevoegde annotaties blijven staan op het schema. Controleer de positie van deze aanvullingen!_
      - **[ Nee ]**
_Er volgt een melding: "Een nieuwe Drafting View wordt aangemaakt. Doorgaan?"._
Klik:
        - **[ Ja ]** om het nieuwe blokschema aan te maken. 
_Er volgt een melding: "Het blokschema is gegenereerd op drafting view 6-_DV_Blokschema - <kast1>+<kast2>_<volgnummer>"._
          - Klik **[ OK ]**
        - **[ Nee ]** om geen nieuw blokschema aan te maken.
_Er volgt een melding: "Het blokschema is niet gegenereerd"._
          - Klik **[ OK ]**
      - **[ Annuleren ]**
_Er volgt een melding: "Het blokschema is niet gegenereerd"._
        - Klik **[ OK ]**

  - Nieuw Blokschema genereren voor actieve kast. Er is reeds eerder een schema gegenereerd. U wilt het bestaande schema behouden:
    - Klik **[ ![themodus_prof_escheme_create_blockscheme_18x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_escheme_create_blockscheme_18x16.png) | Blokschema genereren ]**
_Er volgt een melding: "View '6-_DV_blokschema - <kast1> + <kast2>' bestaat al. Schema op 6-_DV_blokschema - <kast1> + <kast2> vervangen?"._
Klik:
      - **[ Nee ]**
_Er volgt een melding: "Een nieuwe Drafting View wordt aangemaakt. Doorgaan?"._
        - Klik: **[ Ja ]**
_Er volgt een melding: "Het blokschema is gegenereerd op drafting view 6-_DV_Blokschema - <kast1>+<kast2>_<volgnummer>"._
        - Klik **[ OK ]**
_Het bestaande schema wordt vervangen. Eventueel handmatig toegevoegde annotaties blijven staan op het schema. Controleer de positie van deze aanvullingen!_


  - Blokschema's genereren van een specifieke kast:
    - Klik **[ ![themodus_prof_escheme_create_blockscheme_specific_15x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_escheme_create_blockscheme_specific_15x16.png) | Blokschema genereren vanaf kast ]**
    - Selecteer de gewenste kast.
    - Klik **[ OK ]**
_Er volgt een melding: "Het blokschema is gegenereerd op drafting view 6-_DV_Blokschema - <kastnaam>". _
    - Klik **[ OK ]**

**Let op!**
De schema's worden gegenereerd met de naamopbouw met als syntax _"6-_DV_Installatieschema - <kastnaam>"_ of _"6-_DV_Blokschema - <kastnaam>+<kastnaam>"_.
Deze komen te staan onder _'Electrical -> Installatieschema -> Drafting Views'_ en _'Electrical -> Blokschema -> Drafting Views'_ in de projectbrowser van Revit. Deze structuur is afhankelijk van de instellingen in het Revit project.
- Indien bestaande schema's niet worden vervangen, dan wordt de naam van 'drafting view' aangevuld met een volgnummer. De 'drafting view' met het hoogste volgnummer is het meest recent gegenereerde schema.
- Het schema wordt volgens de instellingen uit het instellingen-dialoogvenster gegenereerd voor wat betreft:
  - Horizontale of verticale oriëntatie van het schema.
  - Tussenafstanden van groepen, subrails, voedingen en renvooi. Hierbij rekening houden dat de tussenafstanden van voedingen, subrails en groepen zijn gedefinieerd in de instellingen. In het eigenschappenpaneel van groepen bevindt zich echter ook nog de eigenschap 'Afstand tot volgende (mm)'. Als hier een waarde wordt ingevuld, dan zal dit de afstand op het schema worden tussen deze en de volgende groep, ongeacht wat er bij de instellingen staat. Als deze waarde op "Standaard" staat, dan wordt voor deze afstand gewoon de tussenafstand gehanteerd zoals opgegeven bij de instellingen.
  - Te plaatsen faseletter bij het begin van de groepsinformatie.
  - Te plaatsen tabellen bij het schema op de 'drafting view'.