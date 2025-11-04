# **Kasten, voedingen, subrails en groepen bewerken o.b.v. sjablonen**
In een sjabloon staat de indeling van een kast die eerder is opgeslagen. Bij het toepassen van het sjabloon wordt gecontroleerd of de geïmporteerde groepen voorkomen in het sjabloon. Op deze geïmporteerde groepen wordt het volgende toegepast:
- de structuur van het sjabloon wordt overgenomen (voeding, evt. subrail).
- de families uit het sjabloon worden toegepast.
- de kastscheidingen uit het sjabloon worden overgenomen.

De eigenschappen van de groepen en voedingen blijven ongewijzigd, tenzij in de instellingen is aangegeven dat hiervoor eigenschappen uit het sjabloon moeten worden overgenomen. Voor de eigenschappen van voedingen die niet uit het sjabloon worden overgenomen geldt bovendien het volgende:
1. Als het sjabloon meer voedingen bevat voor een prefix dan het model, dan worden voor de extra voeding(en) de eigenschappen van de laatste voeding voor deze prefix overgenomen.
1. Als het sjabloon evenveel of minder voedingen bevat voor een prefix dan het model, dan worden voor de eerste (nieuwe) voeding de eigenschappen van de eerste voeding uit het model overgenomen, voor de tweede (nieuwe) voeding de eigenschappen van de tweede voeding uit het model, enz. Eerste en tweede slaat hierbij op de eerste en tweede voeding qua volgorde, dus niet qua code of omschrijving van de voeding!! 

De subrails komen inclusief families en eigenschappen geheel uit het sjabloon. Groepen die niet in het sjabloon voorkomen maar wel in het huidige schema staan worden, inclusief voeding en evt. subrail ongewijzigd overgenomen.

Bewerken kan door met de rechter muisknop te klikken op het item in het verkennerpaneel. U krijgt dan een dialoog met daarin alle beschikbare functies afhankelijk van het aangeklikte item. We zetten deze op een rijtje: 