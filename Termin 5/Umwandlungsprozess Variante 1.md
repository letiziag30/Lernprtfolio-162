-öfters in Praxis
	1. Primärschlüssel hinzufügen -> jede Entität bekommt eine Primärschlüssel (oft ID)
	2. netzwerkförmige Beziehungen mit Transformationstabellen auflösen -> neue Entitäten
	3.  Fremdschlüssel hinzufügen -> können korrekt gesetzt werden, da keine netzwerkförmige Beziehungen mehr existieren
	4. Tabellen, die nun keinen PK haben (Transformationsentitäten) haben alle FKs in Kombination als PK
	5. restliche Attribute hinzufügen
![[Pasted image 20260929082426.png|391]]