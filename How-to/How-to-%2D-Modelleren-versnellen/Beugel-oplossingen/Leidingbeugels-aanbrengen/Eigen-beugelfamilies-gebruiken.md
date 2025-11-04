# **Eigen beugelfamilies gebruiken**

TheModus levert standaard een representatieve beugelfamilie voor het ophangen van beugels.
Deze familie kan door eindgebruikers worden aangepast naar wens.
U kunt bijvoorbeeld extra componenten toevoegen voor het uitrekenen van bepaalde aantallen.

De standaard beugel bestaat uit Revit families:
- de beugel
- een draadeinde

Bij de beugel wordt rekening gehouden met:
- de beugel bestaat uit 2 beugeldelen;
- de beugeldelen staan standaard tegen elkaar, maar kunnen een afstand van elkaar hebben;
- de beugel kan als geheel een verplaatsing hebben ten opzichte van het werkvlak. Dit kan handig zijn als de beugel handmatig wordt geplaatst;
- de beugel heeft een diameter ter grote van de buis;
- de diameter van de beugel kan verhoogd worden voor als er extra vulling of isolatie tussen de buis en de diameter zit. Dit heet de inlage;
- de afmetingen van de beugelplaat zijn aanpasbaar in lengte, breedte en dikte;
- op de beugel zit een moer;
- de moer kan in lengte, sleutelwaarde en diameter aangepast worden;

Aan de beugel is een draadeinde bevestigd. Dit is een geneste familie en kan daardoor als apart item worden gecalculeerd. De eigenschappen van dit draadeinde zijn:
- de diameter is aanpasbaar;
- de lengte wordt aangepast op basis van:
  - de afstand tussen de constructie en de beugel;
  - rekening houdend met de dikte en diameter van de beugel;
  - een instelbare maat hoe ver het draadeinde in de moer zit;
  - een instelbare maat of het uiteinde van het draadeinde eindigt in de constructie of onder de constructie.

De applicatie TheModus Beugels plaatst de family en vult onderstaande parameters:
- offset, welke de hoogte vertegenwoordigd tussen het hart van de leiding (= hart van de beugel) en de constructie
- diameter leiding, welke de diameter van de buis vertegenwoordigd;
Alle overige parameters kunt u zelf naar eigen gelieven aanpassen.
Indien u gebruik maakt van eigen families, dan moeten bovengenoemde parameters aanwezig zijn!

Bij de moer is onderstaande tabel toegevoegd om eenvoudig de juiste insteekmaat te kunnen kiezen bij een gekozen diameter van de moer.
M2 - 4 mm
M3 - 5,5 mm
M4 - 7 mm
M5 - 8 mm
M6 - 10 mm
M7 - 11 mm
M8 - 13 mm
M10 - 17 mm
M12 - 19 mm
M14 - 22 mm
M16 - 24 mm
M18 - 27 mm
M20 - 30 mm
M22 - 32 mm
M24 - 36 mm
M27 - 41 mm
M30 - 46 mm
M33 - 50 mm
M36 - 55 mm