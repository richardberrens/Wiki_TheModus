# **Onderhoud BIM-model**
'TheModus Dimension' maakt gebruik van de 'extensible storage'. Dit is opslagruimte voor data binnen het BIM-model. In deze 'extensible storage' wordt geregistreerd welke maatlijnen op welke views worden geplaatst. Dat maakt het mogelijk om de maatlijnen te onderhouden. 

Als een gebruiker maatlijnen, welke door 'TheModus Dimension' zijn gegenereerd, verwijderd, dan blijft de informatie achter in de extensible storage'. Als de procedure vervolgens opnieuw wordt uitgevoerd, dan herkent 'TheModus Dimension' in de 'extensible storage' en zal geen maatlijnen tekenen. U kunt daarom de data in de 'extensible storage' verwijderen.

**Werkwijze voor het verwijderen van de cache uit de extensible storage:**
- Klik in 'Cadac Revit' > 'Productiviteit' > **[ ![themodus_prof_button_addin_productivity_documentation_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_16x16.png) | Documentatie ]** > **[ ![themodus_prof_button_addin_productivity_documentation_dimensioning_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_button_addin_productivity_documentation_dimensioning_16x16.png) | Maatvoering  ]**;
- Maak een selectie van de views, kies:
  - **'Actieve view'** om de data alleen uit de actieve view te verwijderen;
  - **'Lijst van views'** om de data uit alle 'geselecteerde views' te verwijderen.
    - Klik **[ ![themodus_generic_select_file_21x16.png))](https://download.cadac.com/themodus/manual/themodus_generic_select_file_21x16.png) | Selecteer views om te maatvoeren ]** om de views te selecteren.
    - Selecteer alle views, klik **[ OK ]**
- Klik **[ ![themodus_prof_openings_remove_cache_16x16.png))](https://download.cadac.com/themodus/manual/themodus_prof_openings_remove_cache_16x16.png) | Verwijder TheModus dimensionering data voor de actieve view/view lijst ]**
- Klik:
  - **[ Ja ]** om de data te verwijderen
  - **[ Nee ]** om de data te behouden.
- Sluit de procedure af door te klikken op **[ X ]** of **[ ANNULEER ]**
_De 'extensible storage' voor de geselecteerde view is opgeschoond._