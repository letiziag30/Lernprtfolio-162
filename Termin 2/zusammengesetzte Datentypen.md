***Zeichenkette fester Länge***
-eine Folge von Zeichen mit einer vorher festgelegten Länge
-Bezeichnungen der Zeichenketten fester Länge: Array of CHAR, CHAR(n), CHAR[ n ]
-Wertebereich: Alle möglichen Zeichenketten -> alle Kombinationen der erlaubten Zeichen können gespeichert werden, solange die festgelegte Länge eingehalten wird
-Operationen: Stringfunktionen (Teilstring, Konkatenation (Zusammensetzung)), <, >, =  

***Zeichenkette variabler Länge***
-Text, dessen Länge sich verändern kann
-Computer muss wissen, wie lang ein Text ist bzw. wo er endet, es gibt verschiedene Möglichkeiten: ein spezielles Endezeichen (\0), eine gespeicherte Längenangabe oder eine Funktion -> oft String-Datentyp
-Bezeichnungen der Zeichenketten variabler Länge: String, Array of CHAR, VARCHAR, CLOB _(Character Large Object)_, Text
-Strings sind Zeichenketten von Char
-Wertebereich: Zeichenketten variabler Länge
-Operationen: Stringfunktionen (Teilstring, Länge, Konkatenation (Zusammensetzung)), <, >, =

***Datum & Zeit***
-speichern Datum, Uhrzeit oder beides zusammen
-Bezeichnungen: DATE, TIME, DATETIME, TIMESTAMP
-Wertebereich: verschiedene Definitionen, oft dient Anzahl Millisekunden als Grundlage
-Operationen: Manchmal sind Operatoren wie +, - möglich, normalerweise werden Methoden verwendet. Vergleich möglich mit = oder Methode
-Format: wird normalerweise mit einer Zeichenkette definiert, z.B. "dd.MM.yyyy - HH:mm:ss" oder "d.M.yy / H:m"

***binäre Datenobjekte variabler Länge***
-Daten, die der Computer als Folge von Bytes bzw. 0 und 1 speichert
-Länge kann durch eine Variable oder Standardfunktion ermittelt werden
-Bezeichnung: BLOB _(Binary Large OBject)_, Bild, Audo, Video, ...
-Wertebereich: binäre Datenobjekte variabler Länge
-Operationen: Länge, Konkatenation (Zusammensetzung), =

***Verbund, Satz, Struktur, Bereich***
-mehrere zusammengehörende Daten, auch mit unterschiedlichen Datentypen, werden zu einem neuen Datentyp zusammengefasst
-Bezeichnung: RECORD, STRUCT, CLASS (erweiterte Bedeutung)
-Wertebereich: Folge/ein Verbund verschiedener Komponenten, kann unterschiedliche Datentypen enthalten
-Operationen: Vergleich (nur Gleichheit oder Verschiedenheit), Zuweisung mit oder ohne Zuweisungskompatibilität (stark programmiersprachenabhängig)
-Beispiel: type Prüfung is RECORD (Fach: STRING, Schueler: STRING, Punkte: INTEGER, Lehrer: STRING, Termin: DATUM)

