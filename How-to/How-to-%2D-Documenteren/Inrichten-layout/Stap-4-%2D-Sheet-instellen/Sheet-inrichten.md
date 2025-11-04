# **Sheet inrichten**
Ieder tabblad heeft een matrix van 4 kolommen en 4 rijen. In iedere cel kan een 'View' worden toegevoegd.

Een 'View' kan één keer worden toegevoegd. Uitgezonderd zijn Schedules' en 'Legends'. Die kunnen meerdere malen worden
toegevoegd.

De exacte positie van de 'View' wordt berekend door TheModus. Deze berekening gebeurt op basis van de 'Bounding Box' van de elementen, en de opgegeven marges. Dit geld voor alle 'Views', met uitzondering van een '3D view', een 'Schedule' of een 'Legend'. Voor deze 'Views' moeten exacte coördinaten worden opgegeven waar de 'View' komt te staan op het blad. Voor de overige 'Views' is het ook mogelijk om coördinaten op te geven. De coördinaten worden berekend vanaf de linker bovenhoek van de 'View' ten opzichte van de linker bovenhoek van het blad.

Het is ook mogelijk om een 'View' te roteren. Een 'View' kan 90° naar links worden gekanteld, of 90° naar rechts.

De berekening van de positionering van de 'Views' is afhankelijk van de afmetingen van de views, de ingestelde marges en de eventuele centreeropties.

**Werkwijze voor het toevoegen van een 'View' in een matrix cel:**
- *Het formulier **'ONTWERP SHEETS'** is geopend;*
- Klik op de gewenste cel.
_de lijst met beschikbare views wordt geopend_
- Selecteer de gewenste 'View', 'Schedule' of 'Legend' uit de lijst; 
- Klik **[ OK ]**
- Stel de view in:
  - Geef eventueel een rotatie op.
  - Geef indien gewenst coördinaten op (verplicht voor de '3D view', 'Schedule' of 'Legend').
- Herhaal deze voor alle views.

**Opmerking**
- Je kan een geplaatste 'View' verslepen naar een andere cel.
- Je kan een geplaatste 'View' verwijderen door te klikken op het kruisje rechtsboven in de matrix cel.*
- Het uitrekenen van de coördinaten voor de '3D views', 'Schedules' en 'Legends' is altijd complex. Gebruik daarom eerst een aantal representatieve elementen bij het inrichten van een layout.
- Indien er gebruik wordt gemaakt van de 'Placeholder voor wand' moet er rekening mee gehouden worden dat 'TheModus Documentatie' automatisch de views van de wanden áchter' elkaar blijft plaatsen totdat het einde van de bladkader is bereikt of het einde van het titelkader. Rekening houdend met de instellingen 'Titelblok breedte' en 'Titelblok hoogte'. Zodra dit einde is bereikt worden views automatisch op een volgende regel geplaatst. Indien het blad 'vol' is wordt er automatisch een nieuw blad aangemaakt.