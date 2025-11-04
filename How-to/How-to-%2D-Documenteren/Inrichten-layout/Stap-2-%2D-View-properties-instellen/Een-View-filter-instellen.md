# **Een 'View' filter instellen**
Je kan een viewfilter instellen waarmee je bepaalde informatie kunt weglaten uit de view.

De viewfilter werkt gelijkwaardig als dat een viewfilter in Revit wordt ingesteld. De viewfilter maakt gebruik van project parameters.

**Werkwijze voor het instellen van de 'View' filter:**
- Het formulier '**VIEW PROPERTIES INSTELLEN**' is geopend;
- Selecteer bij '**Filter parameter**' de gewenste parameter. Deze parameter wordt gebruikt om de filter op toe te passen én het criterium uit te lezen. Het criterium wordt uitgelezen bij het element waarvan de documentatie wordt gegenereerd;
- Selecteer bij '**Filter Criteria**' de operator hoe de filter moet worden toegepast. Onderstaande operatoren worden ondersteund:
  - Begint met
  - Begint niet met
  - Bevat
  - Bevat niet
  - Eindigt met
  - Eindigt niet met
  - Gelijk =
  - Groter dan >
  - Groter of gelijk >
  - Heeft parameter
  - Kleiner dan <
  - Kleiner of gelijk <=
  - Ongelijk <>
- Selecteer bij '**Filter positie**':
  - Eerste; als dit filter als eerste filter mag worden toegepast in de view.
  - Laatste; als dit filter als laatste filter mag worden toegepast in de view.
  - Vervang; als dit filter alle andere filters mag verwijderen.

**Opmerking**
- De filter wordt aangemaakt met het kenmerk *"visibility"* uitgeschakeld!
- Een filter kan alleen worden ingesteld, als dit toegestaan is in de viewtemplate. Het vinkje **'Include'** in het instellingen scherm van de Revit 'View' Template moet dan zijn **uitgevinkt**!
![themodus_nl_documentatie_viewtemplate_filter.png))](https://download.cadac.com/themodus/manual/themodus_nl_documentatie_viewtemplate_filter.png)