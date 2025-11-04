# **Documenteren project**
'Documenteren project' is specifiek bedoelt voor het documenteren van grote projectdelen of het hele project. 'Documenteren project' maakt gebruik van 'Sections' voor de aanzichten en doorsneden. Voor de plattegronden, bovenaanzichten, onderaanzichten en plafondaanzichten worden zogenaamde 'Planviews' gebruikt. Voor 'Documenteren project' is in beginsel de project oriëntatie leidend voor de berekening van de projecties. Doch kunnen met behulp van 'Scope Boxen' of 'TheModus Project Groepen' andere oriëntaties worden afgedwongen.

**Werkwijze voor het documenteren volgens deze toepassing:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_documentation_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_16x16.png) | Documentatie ]** > **[ ![themodus_prof_button_addin_productivity_documentation_projectdocumentation_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_projectdocumentation_16x16.png) | Project documentatie]**;
- Selecteer bij **[ 1. Select type ]** het gewenste type. Kies:
  - Revit Project voor het documenteren van het hele project op basis van een vast bepaald aantal verdiepingen, of kies de gewenste verdiepingen;
  - Revit Project Dependencies
  - Revit Scope Box (Opm. 1) voor het documenteren van een deel van het project op basis van een vast bepaald aantal verdiepingen, of kies de gewenste verdiepingen;
  - Revit Scope Box Dependencies
  - TheModus Projectgroep (Opm. 1) voor het documenteren van een deel van het project op basis van een vast bepaald aantal verdiepingen, of kies de gewenste verdiepingen;
  - TheModus Projectgroep Dependencies
- Selecteer bij **[ 2. Selecteer elementen ]** de gewenste objecten. Als je in de eerste stap hebt gekozen voor 'Revit Project' dan is er slechts één keuze, namelijk het project.
- Onder **[ 3. Selecteer levels/views ]**
  - Indien actief: Vink aan **[] 'Gebruik gespecificeerde levels van documentatie layout'** als de verdiepingen zijn vastgelegd in het sjabloon;
_of_
  - Indien actief: Vink uit **[] 'Gebruik gespecificeerde levels van documentatie layout'** als de verdiepingen niet zijn vastgelegd in het sjabloon;
  - Selecteer de gewenste verdiepingen;
_of_
  - (Opm. 2) Indien de lijst met Views actief is, selecteer de gewenste 'Views'
- Klik **[ VOLGENDE ]**
- Selecteer het gewenste sjabloon. Je moet een sjabloon hebben waarin alle instellingen zijn gedefinieerd. Voor meer informatie zie **Inrichten sjabloon**. 
Je kan met **<CTRL>** meerdere sjablonen kiezen. Per sjabloon wordt dan een set documenten gegenereerd!
- Klik **[ START ]**
_De documenten worden gegenereerd._

**Opmerking**
1. Voor de Revit Scopebox gelden een aantal beperkingen. Revit scope boxen hebben maar een beperkt aantal eigenschappen beschikbaar. Als gevolg is het niet mogelijk om bepaalde eigenschappen uit elementen te gebruiken voor het opbouwen van viewnamen, sheetnamen, het zetten van viewfilters en het zetten van schedule filters. Gebruik indien gewenst TheModus Projectgroep.
1. Bij **[ 1. Select type ]** heb je gekozen voor '...Dependencies'. Kies een sjabloon waarvan de 'Viewtype' van de geselecteerde 'View' overeenkomt met het sjabloon. 
