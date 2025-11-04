# **Automatisch nummeren**

Zodra modellen gebruikt gaan worden voor de productie, is het noodzakelijk dat elementen voorzien worden van nummers. Het is natuurlijk altijd mogelijk om de elementen één voor één te voorzien van een nummer, bijvoorbeeld met behulp van een schedule. Met TheModus Automatisch nummeren kan deze heftige klus in slechts enkele klikhandelingen.

Er bestaan 2 routines:
De eerste routine geeft zelf een volgnummer aan een selectie van elementen. De gebruiker geeft hier de structuur van het nummer op, de
analyse richting en maakt een selectie van alle elementen welke genummerd moeten worden.

Bij de tweede routine bepaalt de gebruiker zelf in welke volgorde de elementen genummerd worden. De gebruiker geeft ook hier de structuur van het nummer op en klikt dan vervolgens één voor één de elementen aan, in de volgorde zoals de gebruiker deze genummerd wil hebben. 

**Werkwijze voor het automatisch nummeren van elementen:**
- Maak een selectie van de elementen welke genummerd moeten worden;
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![Indelen.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_16x16.png) | Indelen ]**; > **[ ![themodus_prof_button_addin_productivity_sort_autonumbering_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_autonumbering_16x16.png) | Automatisch nummeren ]**; 
- Bij 'Nummering syntax':
  - Vink **[ Prefix ]** aan als u een prefix wilt toevoegen en geef de waarde op;
  - Vink **[ Categorie Code ]** aan als u een afkorting van de Revit categorie wilt toevoegen;
    - Klik **[ ... ]** om een selectie van categorieën te maken.
    - Klik **[ OK ]**
    - Vink **[ Level parameter ]** aan als u een parameterwaarde van een level wilt toevoegen en selecteer de parameter welke de waarde bevat;
    - Geef bij **'koppelteken'** een gewenst koppelteken op;
- Bij **'Filtering'**:
  - Activeer **'Selectie'** om de actieve selectie te gebruiken
_of_
  - Om een selectie te maken;
    - Activeer **'View'** om alle elementen in de actieve view te gebruiken;
    - Klik **[ ... ]** achter 'Filter categorieën' om een categorie als filter te gebruiken;
- Bij 'Volgorde':
  - Activeer 'Automatisch' als u volledig automatisch wilt laten nummeren. Bepaal de volgorde;
    - Activeer 'Level - Horizontaal - Vertikaal' om deze volgorde te gebruiken.
    - Activeer 'Level - Vertikaal - Horizontaal' om deze volgorde te gebruiken.
    - Activeer 'Handmatig' als u de elementen één voor één wilt selecteren. 
- Bij 'Te gebruiken levels':
  - Activeer **'Alle'** om alle levels te gebruiken
  - Activeer **'Specifiek'** om specifieke levels te gebruiken
  - Activeer **'Building story'** om alleen 'Building story levels' te gebruiken.
  - Activeer **'Structural'** om alleen 'Structural levels' te gebruiken.
- Bij 'In te vullen parameter':
  - Geef de parameter op waar het nummer moet worden weggeschreven;
  - Bepaal of bestaande waarden mogen worden overschreven;
  - Bepaal of de functie moet doorgaan met de bestaande nummers;
  - Geef bij **[ Startnummer ]** het startnummer op. Dit mag een numerieke waarde zijn (001), maar ook alfabetisch (aaa).
- Klik **[ OK ]** om te starten.
_Als u gekozen heeft om handmatig te nummeren, sluit dan de procedure af met <Esc>_