![[Pasted image 20260829202857.png]]

***Ganze Zahlen***
-Bezeichnungen der ganzen Zahlen: BIGINT, BIN, BIN FIXED, BINARY, BYTE, COMP, INT, INTEGER, LONG, LONG INT, LONGINT, MEDIUMINT, SHORT, SHORTINT, SMALLINT
-Wertebereich (welche kleinste und grösste Zahl im Datentyp gespeichert werden kann) ganzen Zahlen: meist 32 Bit (-2^32...2^31-1), 16 Bit, 64 Bit
-Operationen: +, -, * , <, >, =, Division mit Rest, Modulo

***Natürliche Zahlen***
-ganze Zahlen ohne negative Zahlen
-Bezeichnungen der natürlichen Zahlen: BYTE, CARDINAL, NATURAL, UNSIGNED, UNSIGNED CHAR, UNSIGNED INT, UNSIGNED LONG, UNSIGNED SHORT, WORD
-Wertebereich: meist 32 Bit, (0...2^32-1), 8 Bit, 16 Bit, 64 Bit
-Operationen: +, -, * , <, >, =, Division mit Rest, Modulo

***Festkommazahlen (Dezimalzahlen)***
-Bezeichnungen der Festkommazahlen: COMP-3, CURRENCY, PACKED DECIMAL, DEC, DECIMAL, NUMERIC
-Wertebereich: ist direkt abhängig von der maximalen Stellenanzahl -> meist vorzugeben; CURRENCY (64 Bit)
-Operationen: +, -, * , <, >, =, Division mit Rest, Modulo

***Aufzählungstypen***
-Datentypen, bei denen vorher festgelegt wird, welche Werte erlaubt sind
-Bezeichnungen der Aufzählungstypen: ENUM, SET oder implizit
-Wertebereich: frei wählbar, der Programmierer bestimmt welche Werte erlaubt sind, beispielsweise (SCHWARZ, ROT, BLAU, GELB)
-Operationen: <, >, =

***Boolean (logische Werte)***
-kennt nur zwei logische Zustände
-oft für ja/nein-Fragen und Bedingungen verwendet
-Bezeichnungen von Boolean: BOOL, BOOLEAN, LOGICAL, oder (implizit ohne Bezeichner)
-Wertebereich: (TRUE, FALSE) oder (≠ 0, = 0 ) oder (= -1, = 0)
-Operationen: NOT, AND, XOR, NOR, NAND, OR, =, ≠, >>, << (Shift/Rotate)

***Zeichen (einzelnes Zeichen)***
-speichert genau ein einzelnes Zeichen
-Bezeichnungen der Zeichen: CHAR, CHARACTER
-Wertebereich: Alle Zeichen, die der verwendete Zeichensatz unterstützt (zum Beispiel Buchstaben)
-Operationen: <, >, =, Konvertierung in INTEGER, …

***Gleitkommazahlen***
-Zahlen mit Nachkommastellen, bei denen auch sehr grosse oder sehr kleine Zahlen dargestellt werden können
-das Komma ist nicht an einer festen Stelle
-Bezeichnungen der Gleitkommazahlen: DOUBLE, DOUBLE PRECISION, EXTENDED, FLOAT, HALF, LONGREAL, REAL, SINGLE, SHORTREAL
-Wertebereich: verschiedene Definitionen
-Operationen: +, -, * , /, <, >, =

***Zeiger***
-speichert nicht direkt einen Wert, sondern die Adresse, an der ein Wert im Speicher liegt
-Bezeichnungen: CCESS, POINTER, IntPtr oder auch nur kurz Stern ( * )
-Wertebereich: Adresse des Basistyps (oft anonym)
-Operationen: Referenz, Dereferenz, in einigen Sprachen: +, -, *, /

***Konstanter Nullzeiger***
-der Zeiger zeigt auf nichts
-Bezeichnung: NULL, VOID, None, NIL, Nothing
-Wertebereich: keiner
-Operationen: =
-Bedeutung: Dieser Zeiger ist verschieden von allen Zeigern auf Objekte.

