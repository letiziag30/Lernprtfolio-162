-Datentypen werden auch zum logischen Datenmodell hinzugefügt -> spezifisch für gewählte DBMS
-DBMS eigene Tools werden für Modellierung verwendet
-normalerweise kann man das Modell per Knopfdruck in Tabellen umwandeln oder Tabellen werden automatisch mit Modell angelegt
![[Pasted image 20260929171915.png|383]]

-mit der Einführung von physischen Tabellen werden neue Begriffe notwendig: 
![[Pasted image 20260929172041.png|438]]
-Tabelle: nicht mehr Entität, sondern Tabelle (Bezeichnung Entität wird auch oft verwendet)
-Tabellenname: eindeutige Bezeichnung der Tabelle
-Attribut, Spalte, Column: jede Spalte innerhalb der Tabelle muss eindeutig sein -> jede Spalte hat einen Datentyp und dadurch einen Wertebereich
-Datensatz, Record, Row, Zeile, Tuple: Datensatz, der ein Objekt dieser Tabelle enthält, z.B. Mitarbeiter mit all seinen Attributen
-Feld, Field, Value, Wert: spezifischer Wert eines Objekts -> Wert muss der Definition der Spalte genügen (mit Datentyp), Wert kann NULL sein 

-Definition der Tabellen Mitarbeiter und Abteilung:
![[Pasted image 20260930151411.png|494]]
-Datatype: Datentyp -> kann bei jedem DBMS unterschiedlich sein
-PK: Primary Key
-NN: Not Null -> hier definiert man ob die Spalte einen Eintrag benötigt, leerer Wert ist ungültig -> macht Unterschied zwischen den Kardinalitäten c und 1 -> daher redet man im physischen Modell nur von 1:m Beziehungen -> ob 1:m oder c:m wird über dieses Feld gesteuert
-UQ: Unique -> wird definiert ob ein Wert in dieser Spalte nur einmal vorkommen darf, PK automatisch auch Unique
-FK: Foreign Key -> Datentyp muss übereinstimmen mit Datentyp des PKs der referenzierten Tabelle

[[Bedeutung von 1, c und m im physischen Datenmodell]]

