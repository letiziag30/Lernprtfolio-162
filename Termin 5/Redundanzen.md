-kann man nicht eine einzige Entität und auch eine einzige Tabelle verwenden anstatt Daten in Entitäten zu verpacken und zu strukturieren?

-z.B.:
![[Pasted image 20260924102441.png|441]]
-viele Daten werden mehrfach abgespeichert -> Redundanz
-redundante Daten sind fehleranfällig bei Änderungen oder Löschung der Einträge -> Anomalien (werden grundsätzlich in drei unterteilt)

**einfüge-Anomalie**
-Primärschlüssel wird so gewählt, dass man keine neuen Daten einfügen kann -> sonst würde Primärschlüssel verletzt werden
-z.B. könnte beim Beispiel oben der Name als Primärschlüssel dienen -> eine Person mit dem gleichen Namen könnte nur einmal eingetragen werden und aber auch nur einmal einen Kauf auslösen

**Änderung-Anomalie**
-passiert wenn man einen Eintrag ändern möchte, aber der gleiche Eintrag mehrmals vorkommen kann
-beim Beispiel oben, z.B. möchte Gustav Meier-Senn nach seiner letzten Bestellung anrufen und eine Änderung seiner Adresse durchgeben -> Support trägt die Adresse nach, aber nur nach der genannten Bestellung -> Gustav Meier-Senn existiert dann mit zwei Adressen

**Lösch-Anomalie**
-passiert, wenn man Werte löschen möchte, aber dadurch zu viele Daten löschen muss 
-beim Beispiel oben, z.B. möchte Beat Merz seine Bestellung stornieren -> wenn der Datensatz gelöscht wird, wird auch der Name und die Adresse gelöscht, sollten aber zukünftige Bestellungen erhalten bleiben