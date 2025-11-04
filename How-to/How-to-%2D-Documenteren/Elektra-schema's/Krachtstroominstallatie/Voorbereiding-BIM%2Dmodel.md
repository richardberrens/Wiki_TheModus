# **Voorbereiding BIM-model**
'TheModus E-schema' stelt enkele eisen aan het BIM-model. We zetten de voorwaarden op een rijtje:
- Alleen onderdelen die behoren tot een 'Electrical Circuit' en die zijn aangesloten op een 'Panel' worden meegenomen in de analyse.
- De vermogens van elementen uit het 'Electrical Circuit' kunnen alleen worden meegeteld bij de import, als deze elementen onderstaande parameters bevatten. Deze parameters bevinden zich in de Parameter Group "160-elektrotechniek" van de TheModus shared parameters:
  - Voor vermogensclassificatie:
    - shared parameter 'vermogensclassificatie' (type parameter) doorgekoppeld naar 'Load classification' connector parameter.
  - Voor schijnbaar vermogen: 
    - shared parameter 'aantal_polen' (type parameter) doorgekoppeld naar 'Number of Poles' connector parameter.
    - shared parameter 'schijnbaar_vermogen' (instance- of type parameter) indien niet aanwezig wordt de built-in parameter 'Apparent Load' uitgelezen;
      - OF: shared parameters (instance parameter):
        - schijnbaar_vermogen_L1
        - schijnbaar_vermogen_L2
        - schijnbaar_vermogen_L3
      - OF: built-in instance parameters: 
        - Apparent Load Phase A
        - Apparent Load Phase B
        - Apparent Load Phase C
  - (Balanced/Unbalanced niet nodig: als shared parameters "schijnbaar_vermogen_L1/2/3" ontbreken, dan wordt aangenomen, dat de family Balanced is, en wordt het vermogen over "number_of_poles" polen verdeeld).
- De Bestemming van de groep wordt ingelezen uit de 'Load Name' van het 'Electrical Circuit'. Deze kan in het model worden ingevuld via de properties van het 'Electrical Circuit' of via het 'Panel schedule'. 

**Let op:** 
De bovenstaande shared parameters worden in het model opgezocht op basis van GUID. Deze ligt voor onze shared parameters vast binnen de template en binnen de applicatie. De parameters die moeten worden toegevoegd aan een eigen family zullen dus moeten worden geselecteerd uit de shared parameter lijst van Cadac. Simpelweg zelf een shared parameter met de juiste naam aanmaken en opnemen in de family gaat dus niet werken, omdat de GUID niet overeen zal komen met onze shared parameter ! Maak hiervoor gebruik van de Cadac Shared Parameter file: CDC_shared_parameters.txt. Deze is terug te vinden in de map %localappdata\%Cadac Group\TheModus Revit Addin\Config\Main\