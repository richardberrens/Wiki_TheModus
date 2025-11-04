# **Objecten bundelen en voorzien van informatie**

Objecten bundelen en voorzien van de juiste informatie gebeurt in 3 stappen. 

**Werkwijze voor het structureren van informatie:**
- Zorg dat het project is opgeslagen;
- Klik in 'Cadac Revit' > 'Productiviteit' > pijl onder **[ ![themodus_prof_button_addin_productivity_sort_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_16x16.png) | Indelen ]**; > **[ ![themodus_prof_button_addin_productivity_sort_information_transfer_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_sort_information_transfer_16x16.png) | Informatie overzetten en groeperen objecten ]**; 
- **STAP 1:** Verzamel de bronobjecten. Deze kunt u op een aantal methoden selecteren:
    - Optie 1: Kies **'Project'** om alle objecten in het project te gebruiken als bron. Alle model componenten die geplaatst zijn in het model worden geselecteerd.
    - Optie 2: Kies **'Actieve view'** om alle objecten in de actieve view te selecteren als bron object.
    - Optie 3: Kies **'Handmatige selectie'** om de bronobjecten handmatig te selecteren.
      - Klik **[ SELECTEREN ]** om het formulier te verlaten en objecten te selecteren.
      - Klik **[ ![themodus_generic_finish_28x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_finish_28x16.png) | Finish ]** om weer terug te keren naar het formulier.
N.B. Als u de functie start met al reeds geselecteerde objecten dan wordt automatisch deze optie ingeschakeld.
    - Optie 4: Kies **'Query'** kunt u TheModus laten zoeken naar alle bron objecten die voldoen aan het opgegeven zoekcriterium. Dit betreft alle objecten die actief zijn in de view. U kunt de view dus zelfs als extra filter inzetten. Geef vervolgens op:
      - De project parameter welke een bepaalde waarde bevat.
      - De operator hoe de waarde met het criterium vergeleken moet worden.
      - Het criterium.
      - Klik **[ UITVOEREN ]**
_De objecten die voldoen aan het criterium worden geselecteerd._
    - Het aantal bron objecten wordt weergegeven.
    - Open het tabblad **\'2. Informatie overdragen\'**
- **STAP 2:** U kunt nu kiezen hoe informatie moet worden overgedragen vanuit de bron objecten naar de aanverwante objecten. In dit geval worden eigenschappen van een bron object overgedragen naar gelijkwaardige parameters van de aanverwante objecten.
Deze stap is niet verplicht. U kunt deze stap overslaan om alleen groepen te genereren.  
Kies op welke manier de kenmerken moeten worden overgedragen. Selecteer:
   - Optie 1: **'Geen informatie overdragen'** als _alleen_ groepen gemaakt moeten worden.
   - Optie 2: **'Identificatienummer van primaire object overdragen naar hierin geneste objecten'** als u het unieke identificatienummer van het bron object wilt overdragen naar alle objecten die genest zijn in dit object.
      - Selecteer de 'instance project parameter' (type text) waaraan het kenmerk moet worden toegevoegd. 
_Deze parameter moet beschikbaar zijn voor alle categorieën._
      - U kunt dit nummer uitbreiden met een voorvoegsel en/of achtervoegsel.
_Voor deze procedure worden geen groepen gemaakt!_
   - Optie 2: **'Eigenschappen overdragen van een object naar alle objecten binnen haar volume'** als u één of meerdere eigenschappen van een bron object wilt overdragen naar alle aanverwante objecten die geheel of deels binnen het volume van dit bron object vallen.
      - Selecteer één of meerdere 'instance project parameters' van het bron object waarbij de waarde wordt overgedragen naar de gelijknamige parameters van de gevonden objecten binnen dit volume.
      - Kies nu hoe TheModus de elementen selecteert op basis van de bronobjecten:
        - Kies **'Objecten deels binnen het object overslaan'** als u wenst dat TheModus alleen doelobjecten selecteert waarvan de bounding box volledig binnen de bounding box van het bron object valt.
        - Kies **'Informatie alle objecten deels binnen het object ";" gescheiden toevoegen'** als doelobjecten mogelijk binnen meerdere bronobjecten vallen. De waarde van alle bronobjecten wordt dan overgedragen aan het doelobjecten, waarbij die waarden met ';' wordt gescheiden.
        - Kies **'Informatie toevoegen indien volumen overlappen > 50%'** als u wenst dat TheModus berekent of doelobjecten voor exact of meer dan de helft zich bevinden in de bounding box van het bronobject. Indien geldig, dan ontvangt het doelobject de waarde van het bronobject.
      - Activeer **[] 'Volume analyse op basis van Revit geometrie'** als u wenst dat TheModus de berekening maakt op basis van de exacte geometrie in plaats van de bounding box.
**Let op!: Deze procedure duurt langer!**
      - Activeer **[] 'Elementen gehost op selectie ook meenemen'** als er 'Host-based' componenten op de gevonden elementen zitten die ook tot de groep horen. Als u wapening wilt voorzien van kenmerken dan moet u deze optie ook kiezen.
      - Activeer **[] 'Gebruik actieve view voor bepaling intersectie'** als u alleen de componenten in de actieve view wilt gebruiken voor de analyse.
_Voor iedere type analyse zijn vervolgens 3 opties beschikbaar. Zie onderstaande tabel voor meer informatie over de berekening._
      - Klik **[ GENEREREN ]** als u alleen informatie wilt overdragen of ga naar stap 3
- **STAP 3:** U kunt ook groepen maken. In de laatste stap wordt ingesteld hoe groepen te genereren, en welke type groepen. 
U kunt het genereren van groepen combineren. Het is mogelijk om samen met een TheModus groep ook een Revit selection set te genereren en een Revit Groep of Revit Assembly te maken. 
U kunt geen Revit Groep en Revit Assembly samen maken. Het is in Revit niet toegestaan om een object in zowel een Groep alsook in een Assembly te plaatsen. 
Het is niet mogelijk om groepen aan te maken in combinatie met **'Identificatienummer van primaire object overdragen naar hierin geneste objecten' **(tabblad '2. Informatie overdragen')
    - Bepaal bij **'Groepeer per kenmerk'** welke parameter waarde bepalend is voor het bundelen van de informatie per groep.
_Deze functie is uitgeschakeld in combinatie met **'Eigenschappen overdragen ...'** (tabblad 2. Informatie overdragen') omdat het bundelen dan reeds bepaald is door de keuze van de hoofdobjecten._
    - Kies **[] 'TheModus groep'** maken, als u onder meer de groep gaat gebruiken voor documentatie doeleinden. Kies daarbij:
      - **'Elementen groep'** als u wenst dat TheModus Documentation uw groep behandeld gelijkwaardig als een element. 'Views' worden nu gegenereerd op basis van 'Detail views'. 
_of_
      - **'Project groep'** als u wenst dat TheModus Documentation uw groep behandeld als een project. Views worden nu gegenereerd als  'Planviews'.
      - Kies het primair object op basis van de 'Categorie' of de 'Familie'. Dit object is bepalend voor de oriëntatie van de groep objecten en de naam van de groep.
      - Geef aan of dit object alleen horizontaal mag zijn.
_Deze functie wordt uitgeschakeld in combinatie met **'Eigenschappen overdragen ...'**. Het primair object is reeds bepaald door het bronobject._
    - **[] 'Revit selection set maken'** als u ook een selection set wilt maken.
    - **[] 'Revit groep maken'** als u ook een group wilt maken.
    - **[] 'Revit assembly maken'** als u ook een assembly wilt maken.
      - **[] 'Orientatie assembly oorsprong gelijk maken aan primair object'** als u de oorsprong van de assembly automatisch wilt roteren naar de voorzijde van het element.
  - Klik **[ GENEREREN ]** om de procedure te starten.

**Opmerking**
Onderstaande figuur toont de verschillende use cases hoe TheModus uw informatie kan structureren.
![themodus_nl_afbeelding_informatie_overdragen.png))](https://download.cadac.com/themodus/manual/themodus_nl_afbeelding_informatie_overdragen.png)