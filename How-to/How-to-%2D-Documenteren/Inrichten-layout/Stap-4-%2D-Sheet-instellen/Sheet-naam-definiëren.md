# **Sheet naam definiëren**
Je kan een 'Sheet' automatisch voorzien van een naam, gebaseerd op eigenschappen van de geselecteerde elementen en gebruikte viewtypen.

**Werkwijze voor het inrichten van de 'Sheet' naam:**
- _Het formulier **'ONTWERP SHEETS'** is geopend;_
- Klik op **[ ![themodus_generic_edit_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_edit_16x16.png) | Sheetnaam samenstellen ]**.
_Een nieuw formulier opent met daarin alle beschikbare eigenschappen voor de sheetnaam;_
- Selecteer een gewenst scheidingsteken en één of meerdere eigenschappen, in de volgorde zoals u deze in de naam wenst, gebruik de **<CTRL>** toets om meerdere componenten te selecteren. Tevens kan een vaste tekst toegevoegd worden:
  - Type de tekstwaarde achter '**Vrije tekst:**' 
  - Klik **[ ![themodus_generic_add_02_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_add_02_16x16.png) | Voeg vrije tekst toe ]**
_De waarde wordt toegevoegd onder "Vrije tekst" en kan worden geselecteerd._
- Klik **[ OK ]**
_Het scherm sluit en de syntax voor de 'Sheet naam' wordt nu weergegeven onder 'Sheet naam syntax'. In deze syntax balk kunnen volgende handelingen uitgevoerd worden:_
  - Schuiven met de eigenschappen; Klik een eigenschap aan en schuif deze naar de gewenste positie.
  - Het scheidingsteken wijzigen; Klik op het 'uitrolmenu' en kies het gewenste scheidingsteken.
  - Een eigenschap verwijderen; Klik op de eigenschap en klik **[ ![themodus_generic_remove_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_remove_01_16x16.png) | Eigenschap verwijderen ]**

**Opmerking**
- Je kan vrije tekst verwijderen. Klik de tekstwaarde aan en klik **[ ![themodus_generic_remove_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_remove_01_16x16.png) | Verwijderen geselecteerde vrije tekst ]**
- Er zijn diverse categorieën eigenschappen beschikbaar:
  - **Project informatie parameter**: dit zijn algemene project eigenschappen die je in Revit terug vind onder Project Information;
  - **Project parameter**: dit is informatie van het geselecteerde element afkomstig uit een project parameter;
  - **Sheet parameter**: 
    - Elementnaam: vertegenwoordigd de naam van het element, groepnaam of naam 'Scopebox' afhankelijk van de selectie van de workflow en het element;
    - Sheetnaam: dit is de naam van het (tab)blad welke je handmatig aanmaakt. Dit is erg handig als je het element of gebouw documenteert over meerdere bladen.
  - **Documentatieparameter**:
    - Elementnaam: vertegenwoordigd de naam van het element, groepnaam of naam 'Scopebox' afhankelijk van de selectie van de workflow en het element;
    - Projectienaam: vertegenwoordigd de projectie;
    - Viewtemplate naam: vertegenwoordigd de naam van de viewtemplate.
  - **Familie Parameter**: dit is informatie afkomstig uit het familietype, inclusief shared parameters.
  - U kunt '**View**' parameters gebruiken in de bladnaam. Echter als er meerdere 'Views' op de 'Sheet' worden geplaatst, dan wordt de eerste gevonden template gebruikt.