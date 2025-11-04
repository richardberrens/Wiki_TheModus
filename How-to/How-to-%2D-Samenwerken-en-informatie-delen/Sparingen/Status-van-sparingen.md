# **De status van sparingen**
In dit artikel wordt iets dieper ingegaan op het gedrag van de status van sparingen bij bepaalde toepassingen.

**[Bij het detecteren wordt een nieuwe clash geconstateerd. Er heeft nog geen eerdere detectie plaatsgevonden voor deze clash**
In het overzicht wordt deze als 'Nieuw' gemarkeerd. 'TheModus Sparingen' zal hier voorstellen een aanvraag object te plaatsen. 

**[Bij het detecteren wordt een clash geconstateerd. Deze is reeds eerder geconstateerd, echter heeft de gebruiker de aanvraag niet verwerkt**
In het overzicht wordt deze als 'Nieuw' gemarkeerd. 'TheModus Sparingen' zal hier voorstellen een aanvraag object te plaatsen. 

**[Bij het detecteren wordt een clash geconstateerd. Deze is reeds eerder geconstateerd. Er is reeds een aanvraag object geplaatst**
In het overzicht wordt deze als 'Bestaand' gemarkeerd. 'TheModus Sparingen' zal slechts de bestaande gegevens ophalen.

**[Bij het detecteren wordt een clash geconstateerd. Deze is reeds eerder geconstateerd. Er is reeds een aanvraag object geplaatst. Er hebben echter wijzigingen in het model plaatsgevonden**
In het overzicht wordt deze als 'Gewijzigd' gemarkeerd. 'TheModus Sparingen' zal de nieuwe gegevens ophalen. U moet bepalen of de wijziging verwerkt moet worden.

**[Bij het detecteren wordt geen clash geconstateerd, waar eerder een aanvraag voor was. Er is een wijziging gedaan in het model. Er was goedkeuring van de aanvraag om de aanvraag als sparing te verwerken. In het aspectmodel staat een duplicaat aanvraag**
Bij het detecteren zal 'TheModus Sparingen' dit object markeren met een BIM status gekoppeld aan 'Verwerkt'. 

**[Bij het detecteren wordt geen clash geconstateerd, waar eerder een aanvraag voor was. Er is een wijziging gedaan in het model. Er was geen goedkeuring van de aanvraag om de aanvraag als sparing te verwerken**
Bij het detecteren zal 'TheModus Sparingen' dit object markeren met een BIM status gekoppeld aan 'Vervallen'. U kunt als coordinator ervoor kiezen het object fysiek te verwijderen. U moet dan de aanvraag ook uit het geheugen van het Revit project verwijderen. Zie ook **[ Herstel opslag ]** in het artikel *'overige instellingen'*. U kunt de sparing ook laten staan. Met de filter *'Vervallen'* kan de aanvraag verborgen blijven uit de lijst.

**[Bij het detecteren wordt een clash geconstateerd. Deze is reeds eerder geconstateerd. Er was reeds een aanvraag object geplaatst. Dit aanvraag object is echter verwijderd**
In het overzicht wordt deze als 'Verwijderd' gemarkeerd. 'TheModus Sparingen' zal de laatst bekende gegevens ophalen. U moet bepalen of de aanvraag opnieuw verwerkt moet worden.