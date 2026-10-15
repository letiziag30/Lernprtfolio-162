-netzwerkförmige Beziehungen können mit Hilfe einer Zwischentabelle (Transformations-Entität oder assoziative Entität) auf gelöst werden
-> notwendig, da dies in relationale DBMS nicht implementiert werden können
-eine zusätzliche Tabelle wird zwischen die netzwerkförmige Beziehung gestellt mit folgenden Regeln:
	1. Beziehung der ursprünglichen Entität fällt weg
	2. eine neue Entität wird hinzugefügt
	3. neue Beziehungen zwischen ursprünglichen Entität und neu erstellten Transformationsentität wird hinzugefügt
	4. Kardinalitäten werden verschoben in der Position
![[Pasted image 20260929080958.png|463]]