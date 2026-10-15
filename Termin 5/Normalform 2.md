-ein Relationstyp (Tabelle) befindet sich in 2NF, wenn er sich in der 1NF befindet und jedes Nichtschlüsselattribut von jedem Schlüsselkandidaten voll funktional abhängig ist
-es gibt verschiedene Arten zum vorgehen (manche bauen auf, dass bereits Schlüssel vorhanden sind). z.B.:
	1. Entitäten identifizieren -> mögliche Objekt-Typen voneinander trennen, z.B. Kunden, Rechnungen, Artikel
	2. Primärschlüssel für jede Entität definieren
	3. Kardinalitäten zwischen Entitäten identifizieren
	4. Netzwerk-Beziehungen auflösen und FKs setzen
![[Pasted image 20260930154553.png]]

-im folgenden Schema wurden die Entitäten getrennt
-Währung wurde weggelassen, da diese anscheinend immer SFr ist und daher nicht in Datenbank gespeichert werden muss
-sobald man mehrere Währungen beim Kauf zulässt, kann man diese wieder einführen -> beim Artikel wurde dafür eine Beschreibung eingeführt -> Artikelbezeichnung gespeichert und Id hinzugefügt
![[Pasted image 20260930155129.png]]
-zu diesem Zeitpunkt ist die Information verloren, welche Rechnung zu welchem Kunden gehört und welche Artikel gekauft wurden
-mit Assoziationen weiss man wie man FKs einfügt -> Kardinalitäten zwischen Tabellen erkennen und FKs einfügen
![[Pasted image 20260930155405.png|483]]
-Resultat -> Tabellen mit Datenmodell
-gelb markiert -> hinzugefügte Spalten
-Tabelle _RechnungHatArtikel, damit ein Artikel, der mehrmals in einer Rechnung erscheint, nicht mehrere Datensätze benötigt
![[Pasted image 20260930155548.png]]