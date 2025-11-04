# **Revisie beheer**
Revisiebeheer is één van de belangrijkste aspecten als we praten over 'Document Management'. In 'TheModus Documentatie' zijn enkele functies ingebouwd om te ondersteunen bij het onderhoud van documenten als er wijzigingen plaatsvinden in het BIM model.

Er zijn in het kader van revisiebeheer een aantal aspecten waar TheModus Documentatie' rekening mee kan houden, mits opgegeven door de gebruiker:
- Als 'TheModus Documentatie' de eerste keer wordt uitgevoerd, dan worden 'Views' gemaakt van het element;
- Als 'TheModus Documentatie' vervolgens nog eens wordt uitgevoerd, dan worden eerder aangemaakte 'Views' van elementen niet verwijderd. Eventuele tags en maatlijnen blijven daarmee behouden;
- 'TheModus Documentatie' controleert of een element is gewijzigd. Als een element wordt gewijzigd, dan is dat zichtbaar in de gemaakte'Views'. Echter kunnen de afmetingen van deze 'Views' te groot of te klein zijn na de wijziging. In 'TheModus Documentatie' kan bepaald worden of de 'Views' van een gewijzigd element moeten worden behouden, of dat nieuwe 'Views' gemaakt moeten worden. De bestaande 'Views' worden dan gewijzigd. Als een gebruiker kiest om de bestaande 'Views' te behouden, dan kan de gebruiker per 'Sheet' zien, in welke 'Sheet' gewijzigde elementen staan. Dit is het eenvoudigst met een 'Sheet schedule'. De gebruiker kan dan voor zichzelf markeren of hij de 'Views' handmatig heeft gecorrigeerd. De status wordt dan de volgende keer bijgewerkt. Als een gebruiker kiest om de bestaande 'Views' te vervangen, dan worden nieuwe 'Views' gegenereerd. Er moeten dan nieuwe tags en maatvoering worden toegevoegd indien van toepassing.
- Als een element is verwijderd kan de gebruiker ervoor kiezen dat ook de bladen van dit element worden verwijderd. Indien niet, dan worden de bladen gemarkeerd als "verwijderd".
- Voor het onderhouden van de bladen worden een aantal eigenschappen toegevoegd aan de 'Views' en de 'Sheets':
  - **'CDC_Document status'**, welke de status van het element op het document weergeeft.
De beschikbare statussen zijn:
    - "**Up to date**". De 'View' of 'Sheet' is up to date
    - "**Revise**". De gebruiker moet de 'View' of 'Sheet' controleren. Het element is namelijk gewijzigd.
    - "**Obsolete**". Het element is verwijderd. De gebruiker moet controleren of hij het blad wilt verwijderen.
  - **'CDC_Documentation updated by user'**. De gebruiker kan hier aanvinken als de 'Views' of 'Sheets' zijn bijgewerkt van een gewijzigd element;
  - **'CDC_Document Bounding Box'**, met daarin de gegevens van de 'Bounding Box' van het element. Op basis van deze gegevens controleert 'TheModus Documentatie' of er een wijziging heeft plaatsgevonden;
  - **'CDC_Document_ID'**, met daarin het ID nummer van het element; 
  -   **'CDC_Documentation code'**, uniek ID voor 'TheModus Documentatie'.
  - **'CDC_Documentation level'**, alleen bij de 'Sheets', waar het ID van de bijbehorende levels wordt gevuld.

**Werkwijze voor het instellen dat 'Views' en 'Sheets' moeten worden verwijderd als het element is verwijderd:**
- *Het formulier **'ONTWERP SHEETS'** is geopend;*
- Activeer '**Verwijder als gewist' [ ]**.
_Iedere keer als 'TheModus Documentatie' draait voor dezelfde collectie elementen, dan wordt gecontroleerd of het element nog bestaat. Als het element niet meer bestaat worden de 'Views' en 'Sheets' verwijderd._

**Werkwijze voor het instellen dat 'Views' en 'Sheets' moeten worden overschreven als het element is gewijzigd:**
- Het formulier **'ONTWERP SHEETS'** is geopend;
- Activeer '**Overschrijf als gewijzigd' [ ]**.
_Iedere keer als 'TheModus Documentatie' draait voor dezelfde collectie elementen, dan wordt gecontroleerd of het element is gewijzigd. Indien gewijzigd, dan worden de 'Views' en 'Sheets' verwijderd en worden nieuwe 'Views' en 'Sheets' gegenereerd._

Als u ervoor kiest dat 'Views' of 'Sheets' handmatig moeten worden bijgewerkt, activeer dan de 'View' of 'Sheet' parameter **'CDC_Documentation updated by user'** in de properties van de 'View' of 'Sheet'. Nadat alle 'Views' handmatig zijn bijgewerkt, klik **[ REVISEER ]** op de eerste pagina (**'SELECTEER ELEMENTEN'**) van 'TheModus Documentatie', en alle vinkjes worden hersteld en de status wordt bijgewerkt.