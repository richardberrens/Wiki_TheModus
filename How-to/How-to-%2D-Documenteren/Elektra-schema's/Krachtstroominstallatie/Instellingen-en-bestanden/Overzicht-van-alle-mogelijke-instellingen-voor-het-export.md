# **Overzicht van alle mogelijke instellingen voor het exporteren van het schema**
Verwerk onderstaande export instellingen:
- Export
  - _'Textnote breedte'_. Bepaal hier op basis waarvan de breedte van de tekstvelden berekend mogen worden. Kies:
    - _'Automatisch'_ als 'TheModus E-schema' deze moet berekenen.
    - _'# mm/kar'_ voor een vaste afstand per karakter. (bijv. 3).
- Export -> Installatieschema (Vink aan wat van toepassing is): 
  - Algemeen:
    - _Oriëntatie schema horizontaal_. Vink deze aan om het schema altijd in horizontale richting te genereren.
    - _Plaats aardsymbool tussen rails_. Vink deze optie aan als u de aardsymbolen altijd tussen de rails wilt plaatsen.
  - Voeding eigenschappen:
    - _Toon kabellengte_. Vink deze aan als de kabellengte getoond moet worden bij de voedingen.
    - _Toon Iz_. Vink deze aan als de Iz-waarde getoond moet worden bij de voedingen.
  - Groep eigenschappen:
    - _Faseletter bij groep_
    - _Geen waarde: toon '0'_. Vink deze aan als het getal 0 moet worden ingevuld als er geen waarde beschikbaar is.
    - _Plaats raster vermogens_
    - _Toon Iz_. Vink deze aan als de Iz-waarde getoond moet worden bij de groepen.
    - _Toon totaal gelijktijdig vermogen_
    - _Toon vermogen fase_
    - _Toon gelijktijdig vermogen fase)
  - Tussenruimte. Geef hier in 'mm' de waarde op tussen de verschillende items:
    - Groep
    - SubRail
    - Voeding
    - Buslijn
    - Renvooi
  - Tabellen. Geef hier de kolombreedte op van de tabellen voor de:
    - Groepenlijst [15] [30] [15] [15] [15]
    - Vermogensklasse [15] [15] [15] [15]
    - Fasen [7] [15] [15] [15]
    - Teksthoogte [1.8]. Geef hier de teksthoogte op voor de teksten in de tabellen.
  - Export -> Blokschema
      - Positionering
        - _Positie kasten_: Geef aan hoe de kasten worden geplaatst ten opzichte van de hoofdverdeelkast. Keuzen zijn:
          - _Links_: de kasten worden geplaatst aan de linkerkant van de hoofdverdeelkast, gesorteerd op naam;
          - _Rechts_: de kasten worden geplaatst aan de rechterkant van de hoofdverdeelkast, gesorteerd op naam;
          - _Verdeeld (L/R)_: de kasten worden zowel aan de linkerkant als aan de rechterkant van de hoofdverdeelkast geplaatst, gesorteerd op naam en zoveel mogelijk uitgebalanceerd qua aantal kasten links en rechts;
          - _Section view volgorde_: de volgorde van de kasten op de levels wordt bepaald door de positie van de kasten in een geselecteerde section view. Voor een goede schematische uitlijning kan de afronding van de positie worden opgegeven.
        - _Bomen gescheiden met tussenafstand [100]_. Vink deze _'aan'_ om bomen van het schema te scheiden als een blokschema wordt gegenereerd vanaf verschillende verdeelkasten en geef een tussenafstand op. Anders wordt alles samengevoegd tot één boom.
        - _Alle levels tonen_. Vink deze _'aan'_ om alle levels uit het model te tonen in het blokschema, of alleen de levels waarop kasten staan.
        - _Voedingsgegevens tonen_. Vink deze _'aan'_ om de voedingsinformatie wel of niet te tonen.
        - _Afstand tot kast_: Geef de afstanden binnen het schema op in 'mm' voor de:
          - Groep [5]
          - Voeding [10]
          - Kast [10]
          - Boom [20]
        - Minimale breedte van de kast [55]
        - Hoogte kast [15]
        - Minimale tussenafstand Levels [100]

Alle instellingen worden opgeslagen in *%localappdata%\Cadac Group\TheModus Revit Addin\Config\ESchema\ESchemaSettings.xml*. 

In E-Schema kunnen door de gebruiker twee soorten bestanden worden opgeslagen en geopend:
- E-Schema project bestanden (*.espx). Een E-Schema project bestand is het bestand waarin het complete E-Schema model is opgeslagen. Hierin staan alle gegevens van alle kasten uit het E-Schema dialoogvenster. E-Schema project bestanden kunnen worden opgeslagen via de knoppen **[ ![themodus_generic_save_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_save_16x16.png) | Opslaan ]** of **[ ![themodus_generic_save-as_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_save-as_16x16.png) | Opslaan als ]** en worden geopend met de knop **[ ![themodus_generic_open_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_open_16x16.png) | Openen ]**;
- E-Schema sjabloon bestanden (*.estx). Het E-Schema sjabloon bestand kan worden gebruikt om de structuur en de families die voor een bepaalde kast zijn ingesteld toe te passen op een andere kast. Het E-Schema sjabloon bestand kan worden gebruikt om de structuur en de families die voor een bepaalde kast zijn ingesteld toe te passen op een andere kast. Opslaan en toepassen van de sjabloonbestanden gebeurt via de opties van het rechtermuismenu van de kast in het verkennerpaneel.