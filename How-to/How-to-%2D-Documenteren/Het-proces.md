# **Het proces**

Voordat u aan de slag gaat met TheModus Documentatie vragen wij u eerst even de tijd te nemen om onderstaande artikelen door te nemen.
TheModus Documentatie ondersteunt namelijk meerdere documentatie varianten. Deze varianten zijn afhankelijk van de keuze van de objecten welke u wenst te documenteren. 

Uw proces bestaat maximaal uit 6 stappen. Zie onderstaand proces:

::: mermaid
flowchart LR
A["Selecteer 
type object"]
B["Selecteer 
object"]
C{"Systeem
kiest 
variant"}
E{"Kies
verdiepingen:
vast/variabel"}
F["Selecteer 
verdiepingen"]
G["Selecteer 
views"]
H["Selecteer 
sjabloon"]
I["Start
Documenteren"]

A-->B
B-->C
C-->|"Objecttype:
'Element'"| H
C-->|"Objecttype:
'Project'
(other)"| E
C-->|"Objecttype:
'Project'
(dependent)"| G
C-->|"Objecttype:
'Ruimte'"| H
E-->|Vast|H
E-->|Variabel|F
F-->H
G-->H
H --> I
style A fill:#91004b,stroke:#91004b,color:#fff
style B fill:#91004b,stroke:#91004b,color:#fff
style C fill:#575757,stroke:#575757,color:#fff
style E fill:#91004b,stroke:#91004b,color:#fff
style F fill:#91004b,stroke:#91004b,color:#fff
style G fill: #91004b,stroke:#91004b,color:#fff
style H fill: #91004b,stroke:#91004b,color:#fff
style I fill: #91004b,stroke:#91004b,color:#fff
:::



We leggen de verschillende documentatie varianten uit:
1. **Documentatie van de elementen**
Deze variant produceert 'Detail views', '3D Views', Schedules' en 'Legends' en plaatst deze op één of meerdere 'Sheets'.
Met deze variant documenteert u specifieke elementen in uw project. U past deze variant  toe als u documentatie wilt maken ten behoeve van de werkvoorbereiding, inkoop of prefab productie van specifieke elementen in uw project. Denk aan kozijnuitslagen, prefab documentatie van wanden, prefab documentatie van leidingsystemen.

1. **Documentatie van het project**
Via deze variant documenteert u uw project of grote delen hiervan. 'Documentatie van het project' kent 3 subvarianten:
   1. **Op basis van een vast aantal verdiepingen**
Deze variant genereert 'Floorplans', 'Ceilingplans', 'Structural plans', 'Sections', '3D Views', 'Schedules' en 'Legends' en plaatst deze op één of meerdere 'Sheets'.
Deze variant is uitermate geschikt voor het documenteren van woningbouw projecten. Denk hierbij aan verkoopdocumentatie, bestektekeningen, woningboekjes etc. Kenmerkend aan deze variant is dat u het aantal verdiepingen heeft vastgelegd in uw definitie.
   1. **Op basis van een variabel aantal verdiepingen**
Deze variant genereert 'Floorplans', 'Ceilingplans', 'Structural plans', 'Schedules' en 'Legends' en plaatst deze op één of meerdere 'Sheets'.
Deze variant is uitermate geschikt voor het documenteren van plattegronden van utiliteitsprojecten of hoogbouw. Denk hierbij aan bestektekeningen en werktekeningen. Kenmerkend aan deze variant is dat u zelf het aantal verdiepingen kunt instellen zodra u gaat documenteren. Het aantal verdiepingen is dus niet hard ingesteld in uw definitie.
   1. **Op basis van bestaande 'Views'**
Deze variant genereert duplicaten ('Dependent Views') van 'Floorplans', 'Ceilingplans', 'Structural plans', 'Sections', 'Schedules' en 'Legends' en plaatst iedere 'View' op één 'Sheet'.
Deze variant kan zeer generiek toegepast worden. Kenmerkend in deze variant is dat u bestaande views gebruikt voor het genereren van uw documentatie. U maakt hierbij gebruik van de Revit techniek 'Dependent Views'. Het voordeel van deze variant is dat alle annotaties en maatvoering van uw bron 'Views' ook zichtbaar zijn op uw nieuwe 'Views'

1. **Documentatie van uw ruimten**
Deze variant genereert 'Detail views', '3D Views', Schedules' en 'Legends' en plaatst deze op één of meerdere 'Sheets'.
Met deze variant maakt u overzicjten van uw ruimten en/of wanduitslagen van uw ruimten. Deze variant is uitermate geschikt om uw schakelmateriaal of wandafwerkingen van de verschillende ruimten inzichtelijk te maken. Deze variant heeft veel raakvlakken met **Documentatie van de elementen**.

De varianten worden bepaald door de keuze van het object. U kunt verschillende objecten kiezen. 
In de volgende artikelen worden de specifieke objecten beschreven.