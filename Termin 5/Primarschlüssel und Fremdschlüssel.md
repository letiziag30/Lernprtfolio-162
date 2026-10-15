**Primarschlüssel**
-jede Entität benötigt ein Attribut oder eine Kombination von Attributen, die ein Tupel eindeutig identifiziert
-Attribut -> Primärschlüssel (PS) oder Primary Key (PK)
-im Beispiel, z.B. die _MitarbeiterId_ für die _Mitarbeiter_-Tabelle und die _AbteilungId_ für die Abteilung

**FremdschlüsselID**
-hierarchische und konditionelle Beziehungen benötigen einen Fremdschlüssel (FS) oder Foreign Key (FK) -> definiert Beziehung und zeigt auf PK oder andere Entität
-im Beispiel, z.B. Attribut Abteilungskürzel
-FK wird immer auf Seite der Beziehung eingeführt -> hat m oder mc  Beziehung

![[Pasted image 20260925161118.png]]

![[Pasted image 20260925161130.png]]

-allgemeine Vorgehen:
-PKs und FKs werden in Attributen bei einem ERD gekennzeichnet
-in einem physischen ERD müssen diese Beziehungen explizit modelliert werden 
![[Pasted image 20260925162036.png]]