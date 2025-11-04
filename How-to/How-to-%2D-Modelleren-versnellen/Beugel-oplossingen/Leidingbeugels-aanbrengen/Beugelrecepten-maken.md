# **Beugelrecepten maken**

U kunt zelf beugelrecepten maken zodat u per leidingtype of systeem kunt bepalen welke beugels u wenst. Dankzij deze recepten kunt afhankelijk van afmetingen of gewicht afdwingen dat een zwaardere beugel gebruikt wordt bij bijvoorbeeld dikkere leidingen.

U kunt meerdere beugelrecepten maken, bijvoorbeeld specifiek voor ieder leidingsysteem;
U kunt per recept meerdere configuraties toevoegen. gebruik bijvoorbeeld een andere Revit familie bij dikkere leidingen.

De volgende instellingen zijn van toepassing:
- **[ Fabrikant ]**  filtert op basis van de 'Manufacturer'. Op deze manier kunt u beugelrecepten maken die alleen toegepast worden op leidingen van deze fabrikant. Gebruik eventueel wildcards (*) om meerdere fabrikanten te ondersteunen;
- **[ Oriëntatie ]**  bepaalt de richting waar de beugel wordt opgehangen. Vooralsnog zijn nu alleen 'Ophangbeugels' mogelijk;
- **[ Vorm ]**  filtert op basis van de vorm van de leiding. Deze is overeenkomend de Revit Categorieën. Vooralsnog worden alleen 'Pipe Types' ondersteund;
- **[ Systeem Type ]**  filtert op basis van het systeem van de leiding. Geef hier de naam van het Revit Systeem Type op; 
- **[ Pipe Segment ]** filtert op basis van het 'Pipe Segment' van de leiding. Op deze manier wordt tevens op het materiaal van de leiding gefilterd. Geef hier de waarden van het Pipe Segment op. Gebruik eventueel wildcards (*) om meerdere segmenten te ondersteunen;
- **[ Diameter kleiner of gelijk aan ]** filtert op basis van de diameter van de leiding. Alle leidingen onder of gelijk de opgegeven waarde komen in aanmerking voor deze configuratie van dit recept;
- **[ Familynaam ]** bepaalt welke Revit familie gebruikt wordt als beugel. Geef hier de volledige naam van de Revit familie op;
- **[ Familie type naam ]** bepaalt welke type van de bepaalde familie gebruikt wordt. Geef hier de volledige naam van het type op;
- **[ Pad ]** bepaalt de locatie waar de familie is opgeslagen. Gebruik deze indien u eigen families toepast. geef hier het volledige pad op.

**Werkwijze voor het instellen van de afstanden van leidingbeugels:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![Beugeling.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_bracketing_16x16.png) | Beugeling]** > **[ ![Genereer beugels.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_bracketing_16x16.png) | Genereer beugels]**;
- Klik **[ ![Instellingen.png))](https://download.cadac.com/themodus/manual/themodus_prof_brackets_configure_recipe_16x16.png) | Instellingen]** 
_Het volgende formulier toont de recepten die u kunt gebruiken voor het plaatsen van beugels._
- U kunt nu recepten en configuraties bewerken. Daar zijn 4 functies voor beschikbaar;
  - Klik **[ ![Toevoegen.png))](https://download.cadac.com/themodus/manual/themodus_prof_brackets_configure_dimensions_add_16x16.png) | Toevoegen]** voor het toevoegen van een nieuw recept;
  - Klik **[ ![Kopieren.png))](https://download.cadac.com/themodus/manual/themodus_prof_brackets_configure_dimensions_copy_16x16.png) | Kopiëren]** voor het kopiëren van een bestaand recept zodat u een nieuwe variant kan inrichten;
  - Klik **[ ![Hernoemen.png))](https://download.cadac.com/themodus/manual/themodus_prof_brackets_configure_dimensions_rename_16x16.png) | Hernoemen]** voor het hernoemen van een bestaand recept;
  - Klik **[ ![Verwijder.png))](https://download.cadac.com/themodus/manual/themodus_prof_brackets_configure_dimensions_remove_16x16.png) | Verwijder]** voor het verwijderen van een recept.
- U wilt een nieuw recept toevoegen:
  - Klik op de bovenste node 'Recepten'
  - Klik **[ ![Toevoegen.png))](https://download.cadac.com/themodus/manual/themodus_prof_brackets_configure_dimensions_add_16x16.png) | Toevoegen]**;
  - Geef de naam van het recept op;
  - Geef indien gewenst de naam van de fabrikant op;
  - Klik **[ OK ]**.
- U wilt een configuratie toevoegen:
   - Klik op de naam van het recept
   - Klik **[ ![Toevoegen.png))](https://download.cadac.com/themodus/manual/themodus_prof_brackets_configure_dimensions_add_16x16.png) | Toevoegen]**;
_Er wordt een nieuwe configuratie toegevoegd_
- U kunt nu de configuratie inrichten:
  - Klik op de configuratie;
  - Vul alle filtervelden in;
  - Klik **[ Opslaan ]**
_De configuratie is ingesteld. Herhaal dit voor alle configuraties zodat u een volledig recept maakt._