-Datenbank muss Datenkonsistenz, also Widerspruchsfreiheit, gewährleistet werden -> z.B. keine Redundanzen zulassen
-Applikation, die Daten verwendet, muss sicherstellen, dass korrekten Daten in Spalten geschrieben werden -> Logik kann weder DBMS noch Datenmodell verhindern
-DBMS leistet einen Beitrag zur Konsistenz der Daten -> stellt sicher, dass keine FKs eingefügt werden, wenn kein PK dazu existiert -> Referenzielle Integrität
![[Pasted image 20260930211958.png|483]]
-hier soll ein Mitarbeiter für die Abteilung Sales (SA) hinzugefügt werden -> DBMS wird einen Fehler geben, da keine Abteilung mit Abkürzung SA existiert
