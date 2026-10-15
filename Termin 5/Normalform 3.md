-ein Relationstyp befindet sich in 3NF, wenn er sich in 2NF befindet und kein Nichtschlüsselattribut transitiv von einem Kandidatenschlüssel abhängt
->jedes Attribut darf nur vom PK abhängen
-Beispiel: Wohnort ist abhängig vom PK und auch PLZ
![[Pasted image 20260930160340.png]]
-NF3 löst man auf, indem man die transitiv abhängigen Attribute in weitere Entitäten verlagert 
-PLZId wurde hinzugefügt, da einige PLZ mehrmals vorkommen für unterschiedliche Orte -> eignet sich nicht als PK
![[Pasted image 20260930211123.png]]
-nach der genannten Logik stellen auch die Hausnummer und die Strasse eine transitive Abhängigkeit dar -> mehrere Personen können an gleicher Adresse wohnen -> Daten sind redundant gespeichert


