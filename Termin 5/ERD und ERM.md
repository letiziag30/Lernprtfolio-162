ERD: "Entity-Relationship Diagram"
ERM: "Entity-Relationship Model" 
-die beiden Begriffe sind sehr ähnlich und werden manchmal als Synonym benutz

**ERD**
-immer ein einzelnes Diagramm
-werden nicht nur zur Modellierung von Datenbanken verwendet, sondern bringen allgemein Daten in einen semantischen Kontext

**ERM**
-kann ein Sammlung von Diagrammen sein
-wenn ein ERM aus einem Diagramm besteht, sind ERM und ERD fast gleich

**Beispiel**
![[Pasted image 20260917111410.png]]
-hier wäre es möglich ein einzelnes Diagramm zu erstellen 
-> man kann auf Wiederholungen verzichten (Schule) -> es kann bei vielen Entitäten unübersichtlich werden

-ein ERD besteht aus Entitäten und Beziehungen
![[Pasted image 20260917111740.png]]
-Entität:
	-ein Objekt das Daten enthält, werden im Detail spezifiziert
	-z.B. kann die Entität 'Lehrperson' die Attribute 'Vorname' und 'Nachname' haben
	-Eine Entität ohne Attribute ist einfach eine abstrakte Version, die noch konkretisiert werden muss
-Beziehung / Assoziation:
	-Beziehungen zwischen Entitäten werden mit einem Strich dargestellt
	-im Beispiel besitzen alle Entitäten eine Assoziation zueinander muss aber nicht immer so sein
