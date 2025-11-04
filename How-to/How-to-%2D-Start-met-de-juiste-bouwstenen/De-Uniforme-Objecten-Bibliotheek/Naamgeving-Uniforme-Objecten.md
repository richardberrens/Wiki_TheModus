---
tags:themodus
--- 
# **Naamgeving Uniforme Objecten**

Het is van belang dat familienamen en typenamen van families conform een bepaalde structuur zijn.

Standaard biedt de Uniforme Objecten Bibliotheek de objecten voor Autodesk Revit aan op basis van de NLRS (Nederlandse Revit Standaard). Dit betreft in ieder geval de familienamen van de Autodesk Revit
families. Op dit moment zijn er nog geen andere standaarden beschikbaar.

De typenamen van de uiteindelijke producten kunt u zelf instellen. Na de installatie van TheModus wordt er een standaard definitie meegeleverd, volgens de NLRS. Doch u kunt deze aanpassen naar wens.

De naam kan ingesteld worden voor 3 typen elementen:
- Instantie voor alle elementen die met behulp van look-up tables worden aangestuurd (fittingen e.d.).
- Type voor alle normale Revit families.
- Systeem voor alle leidingsystemen.

Daarnaast kan er op basis van een UOB veld een specifieke syntax worden opgebouwd.

Standaard is er altijd een basis syntax aanwezig. Deze kan niet worden verwijderd, maar wel worden gewijzigd. Deze is van toepassing als er niet aan de filter criteria wordt voldaan van de voorgaande syntaxen.

Volg onderstaande stappen om de syntax van de familienamen te wijzigen:
- Klik in 'Cadac Revit' > 'Algemeen' > **[ Algemeen ▼ ]** > **[ ![themodus_generic_configure_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_configure_16x16.png) | Instellingen ]**; > **[ Typenaam samenstellen ]**
_Het venster 'Applicatie instellingen > Typenaam samenstellen' opent._
- Aan de linkerzijde kunt u verschillende syntax definities instellen voor de namen. Voor iedere definitie kunt u een aparte filter instellen met uitzondering van de 'Base'. Voor ieder definitie kunt u de syntax van de naam opgeven. U kunt nu definities aanmaken:
  - Klik **[ ![themodus_generic_add_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_add_01_16x16.png) | Nieuw ]** om een nieuwe definitie toe te voegen.*Het venster 'Applicatie instellingen > Typenaam criteria samenstellen' verschijnt.*
    - Geef de waarde voor Merk
    - Geef de waarde voor Serie
    - Geef de waarde voor Type
    - Klik **[ OK ]**
  - Selecteer de definitie en **[ ![themodus_generic_rename_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_rename_01_16x16.png) | Wijzig typenaam criteria ]**  om de naam van de definitie te wijzigen.
  - Selecteer de definitie en klik **[ ![themodus_generic_remove_01_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_remove_01_16x16.png) | Verwijder ]** om de definitie te verwijderen.
  - Selecteer de definitie en klik:
    - **[ ![themodus_generic_arrow_up_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_arrow_up_16x16.png) | Naar boven verplaatsen ]**
    - **[ ![themodus_generic_arrow_down_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_arrow_down_16x16.png) | Naar beneden verplaatsen ]** 
om de filter volgorde in te stellen.
  - U kunt de syntax per definitie instellen
    -   Selecteer de definitie. 
*Indien nieuw aangemaakt, is deze nog leeg, anders wordt in het rechterscherm de syntax getoond;*
    -   Nieuwe syntax instellen voor nieuw aangemaakte definitie: Klik **[ VELD TOEVOEGEN  ]**
    -   Selecteer onder **[ Veld ]** het veld welke de waarde bevat voor deze veldpositie.                *U kunt hier ook voor 'Vaste tekst' kiezen. Er verschijnt dan een veld waarin u zelf een waarde kunt opgeven;* 
    -   Selecteer onder **[ Scheidingsteken ]** het gewenste scheidingsteken;
    -   Klik **[ VELD TOEVOEGEN  ]** als u een extra veldpositie wilt toevoegen;
    -   Klik **[ ![themodus_generic_remove_02_16x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_remove_02_16x16.png) | Verwijderen ]** achter de veldpositie als u een veldpositie wilt verwijderen;
    -   Klik **[ OPSLAAN ]** om de instellingen op te slaan.
  -   Klik **[ OK ]** om de instellingen op te slaan.

*Alle objecten worden vanaf nu geladen met familienamen conform de geselecteerde standaard.*