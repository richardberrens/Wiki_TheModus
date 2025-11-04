# **Netwerk op afschot leggen**
Rioleringen moeten doorgaans op afschot liggen. De standaard oplossing van Autodesk Revit is daarin zeer beperkt. Vaak verliezen objecten de verbindingen onder elkaar. TheModus biedt hiervoor een meer uitgebreide functionaliteit. TheModus controleert ook of de verbindingen in stand blijven.

**Werkwijze voor het leggen van een leidingstelsel op afschot:**
- Zorg ervoor dat een leiding is getekend. 
- Selecteer het stelsel welke op afschot moet worden gelegd.
_De **'Modify'** knoppenbalk wordt geactiveerd;_
- Klik in 'Modify' > 'Cadac Revit bewerk' > **[ ![themodus_prof_button_addin_modify_routingsolutions_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_modify_routingsolutions_16x16.png) | Aansluit oplossingen ]** > **[ ![themodus_prof_button_addin_modify_slopesystems_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_modify_slopesystems_16x16.png) | Genereer afschot ]**;
- Klik een punt in het stelsel welke de vaste hoogte vertegenwoordigd.
_Dit punt wordt niet verplaatst;_
- Klik een punt in het stelsel welke verplaatst wordt; 
- Kies nu hoe de verplaatsing moet worden berekend:
  - Activeer **'Peilmaat te verplaatsen punt'** en geef de exacte peilmaat op waarnaar het te verplaatsen punt moet worden verplaatst;
_Het stelsel wordt onder afschot gelegd._
  - Activeer **'Peilmaat te verplaatsen punt verhogen met'** en geef de hoogte op waarmee het te verplaatsen punt wordt verhoogd ten opzichte van de actuele waarde;
_Het stelsel wordt onder afschot gelegd._
  - Activeer **'Peilmaat te verplaatsen punt verlagen met'** en geef de hoogte op waarmee het te verplaatsen punt wordt verlaagd ten opzichte van de actuele waarde;
_Het stelsel wordt onder afschot gelegd._
  - Activeer **'Afschot in mm/m vanaf rotatiepunt'** het afschot in mm/m op.
_Het hele stelsel wordt nu onder afschot gelegd vanaf het vaste punt. Als het stelsel al onder afschot ligt wordt hier de afschot waarde getoond._
  - Activeer **'Opschot in mm/m vanaf rotatiepunt'** het opschot in mm/m op.
_Het hele stelsel wordt nu onder opschot gelegd vanaf het vaste punt. Als het stelsel al onder opschot ligt wordt hier de opschot waarde getoond._
  - Activeer **'Geen afschot vanaf rotatiepunt\'** als u geen afschot wenst.
_Het stelsel wordt nu 'vlak' gelegd._
- Klik **[ OK ]** om de wijzigingen door te voeren.