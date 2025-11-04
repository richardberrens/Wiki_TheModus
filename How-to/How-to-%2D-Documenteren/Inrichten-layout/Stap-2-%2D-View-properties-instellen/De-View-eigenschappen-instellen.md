# **View eigenschappen instellen**
De tabel onder **'View eigenschappen'** toont alle geselecteerde projecties. Per projectie kan je diverse viewinstellingen instellen. 

**Werkwijze voor het inrichten van de 'View' eigenschappen:**
- Het formulier **[ VIEW PROPERTIES INSTELLEN ]** is geopend;
- Voor alle werkstromen zijn de volgende eigenschappen beschikbaar:
  - **Viewport**: Geef aan met welke viewport de 'View' geplaatst mag worden op een 'Sheet'. 
  - **Link template**: Geef aan of de viewtemplate gekoppeld moet worden aan de view.
  - **Toon Cropregion**: Geef aan of het viewkader voor  modelcategorieën getoond moet worden.
  - **Annotation Crop**: Geef aan of de 'View' afgebakend moet worden op basis van het annotatie kader.
- Voor de 'element' werkstromen zijn ook de volgende eigenschappen beschikbaar:
  - **Meervoudige secties**: Deze maakt het mogelijk om meerdere sneden te genereren op basis van een element. In dit geval wordt er gerekend met een marge. Lijnen binnen deze marge worden gezien als één geheel. Op basis van deze collectie lijnen wordt de 'Bounding Box' van het element verdeelt in meerdere delen, en voor ieder deel wordt een extra snede gegenereerd. Een typisch voorbeeld is een kozijn met meerdere vlakken, waarbij voor ieder vlak een snede gemaakt moet worden. De marge is 100 mm, en is beschikbaar in de definities onder "SectionWidth".
  - **Verberg elementen**: Deze activeert de 'Hide' functie van Revit en verbergt alle elementen in de 'View' behalve het geselecteerde element.
**Let op!**: Deze functie kan de performance van het hele model beïnvloeden!.
  - **Far Clip**: Hiermee kan de kijkdiepte van de 'View' ingesteld worden. Indien de waarde op 0 staat, wordt de kijkdiepte bepaald door de 'Bounding Box' van het element.
- Indien gebruik gemaakt wordt gemaakt van de projectie 'Placeholder voor wand' zijn extra eigenschappen beschikbaar:
  - **Sectie Offset**: deze vertegenwoordigd de afstand van de snede ten opzichte van de wand;
  - **Min. wand lengte**: deze vertegenwoordigd de minimale lengte van de wand (vanuit de ruimte gezien). Indien de lengte kleiner is dan de opgegeven waarde zal geen view worden aangemaakt.

**Opmerking**
- Indien je de viewport type van een rij wilt toepassen op alle rijen, klik dan met de rechter muis knop op de gewenste waarde en klik **'Op alle toepassen'.**
- Indien je een wijziging (vinkje aan/uit) van een rij wilt aanpassen:
  - Voor alle rijen. Klik dan met de rechter muis knop op de gewenste waarde en klik:
    - **'Alle aanvinken'**
_of_
    - **'Alle uitvinken'**
  - De instelling wilt converteren: Klik dan met de rechter muis knop op de gewenste waarde en klik **'Alle omkeren'**
- Als een "shared nested family" als input dient, dan is het **niet** mogelijk om "verberg elementen" toe te passen. Deze verbergt dan namelijk de hoofdfamily waardoor Revit ook alle geneste families ook verbergt.