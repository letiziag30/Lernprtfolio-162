S 1     -      SQL, 1 ERD und ERM, 2 Assoziation (Beziehung) und Kardinalität
S 2     -      2 Assoziation (Beziehung) und Kardinalität, 3 Redundanzen
S 3     -      3 Redundanzen, 4 Konzeptionelles, logisches & physisches Datenmodell
S 4     -      4 Konzeptionelles, logisches & physisches Datenmodell
S 5     -      4 Konzeptionelles, logisches & physisches Datenmodell
S 6     -      4 Konzeptionelles, logisches & physisches Datenmodell, 5 Normalisierung
S 7     -      5 Normalisierung, 6 Datenkonsistenz und - Integrität, 7 Krähenfussnotation



S 1     -      SQL, 1 ERD und ERM, 2 Assoziation (Beziehung) und Kardinalität

![[IMG_2613.jpg|700]]

S 2     -      2 Assoziation (Beziehung) und Kardinalität, 3 Redundanzen

![[IMG_2614.jpg]]

S 3     -      3 Redundanzen, 4 Konzeptionelles, logisches & physisches Datenmodell

![[IMG_2615 2.jpg]]

![[Pasted image 20261020202417.png|700]]

S 4     -      4 Konzeptionelles, logisches & physisches Datenmodell

![[IMG_2616 1.jpg]]

S 5     -      4 Konzeptionelles, logisches & physisches Datenmodell

![[IMG_2617.jpg]]

**Umwandlungsprozess Variante 1**
1. Primärschlüssel hinzufügen. Jede bestehende Entität kriegt einen Primärschlüssel, oft eine ID (Laufnummer).
2. Netzwerkförmige Beziehungen mit Transformationstabellen auflösen. Es werden also neue Entitäten geschaffen.
3. Fremdschlüssel hinzufügen. Die Fremdschlüssel können nun korrekt gesetzt werden, da keine netzwerkförmigen Beziehungen mehr existieren.
4. Tabellen, die nun keinen PK haben (Transformationsentitäten) haben alle FKs in Kombination als PK.
5. Restliche Attribute hinzufügen.
![[Pasted image 20261021074128.png]]

**Umwandlungsprozess Variante 2**
![[Pasted image 20261021074212.png]]

S 6     -      4 Konzeptionelles, logisches & physisches Datenmodell, 5 Normalisierung

![[IMG_2618.jpg]]

**Vom logischen zum physischen Modell**
-Datentypen spezifisch für DBMS hinzufügen
![[Pasted image 20261021074701.png]]
-neue Begriffe
![[Pasted image 20261021074741.png]]

S 7     -      5 Normalisierung, 6 Datenkonsistenz und - Integrität, 7 Krähenfussnotation

![[IMG_2619.jpg]]

