-wie man in Informatik Texte abspeichert
-verschiedene Codierung
-wie Zeichen gemacht sind oder abspeichern
-Hexadezimalsystem: Basis 16 -> 0 bis F
-Octalsystem: 0 bis 7 (8 Stellen)
-> wie wandle ich ins Hexadezimalsysten, ins Octalsystem um etc.

!!**wichtig: Ich weis wie ich den ASCII Code lese**!!   

***ASCII (American Standard Code for Information)***
-ASCII bezeichnet ein Set von Zeichen und weist diesen feste Zahlen zu
-ASCII ist eine Tabelle, die Zeichen in Zahlen übersetzt, damit ein Computer sie speichern und verarbeiten kann -> weist Zeichen, z.B. A, eine feste Zahl zu
-jedes Zeichen werden auf der Festplatte oder im Speicher binär gespeichert (binär speichern: nur mit 0 oder 1 gespeichert, z.B. A ist im Binärsystem 01000001 und 65 als ASCII-Zahl)
-Zahl 65 kann durch A repräsentiert werden und umgekehrt
-z.B. char c = 'A'; int i = c; -> c soll das Zeichen A enthalten, dann speichere den Wert von c in i -> Die Variable i hat den Wert 65
-z.B. char c = '1'; int i = c; -> c soll das Zeichen 1 enthalten, dann speichere den Zahlenwert von c in i -> die Variable i hat den Wert 49, da1 die ASCII-Zahl 49 hat
-ABER ACHTUNG: wenn man 65 als Zeichenkette codiert, dann wird 65 mit 54 (binär 00110110) und 53 (binär: 00110101) codiert

![[Pasted image 20260903112701.png]]

***Unterschied Dezimalsystem, Oktalsystem, Hexadezimalsyystem***
-unterschiedliche Codierung für denselben Wert
der Unterschied liegt in wie viele verschiedene Ziffern zur Verfügung stehen

Dezimalsystem (DEC)
-10 Stellen/Ziffern zur Verfügung von 0-10
-nach der 9 sind alle Ziffern aufgebraucht also: 8 → 9 → 10 → 11 → 12 ...

Oktalsystem (OCT)
-8 Stellen/Ziffern zur Verfügung von 0-7
-nach der 7 kommt bereits 10: 6 -> 7 -> 10 -> 11 -> 12
-10 Oktal = 8 Dezimal

Hexadezimal (HEX)
-16 Ziffern von 0-9 und A-F -> 0 1 2 3 4 5 6 7 8 9 A B C D E F
-nach F kommt 10: 8 -> A -> B -> C -> D -> E -> F -> 10
-A HEX = 10 DEC

***8-Bit Zeichensätze***
-ASCII-Tabelle arbeitet mit 7-bit Speicherplatz (7 Stellen mit 0 oder 1)
-dies reicht aber nicht, um alle Zeichen in anderen Sprachen abzubilden, daher hat man ein 8tes Bit für weitere 128 Werte definiert
-ANSI ist die Erweiterung von ASCII (7 Bit) -> weitere 128 Zeichen
-ANSI = American National Standards Institute 
-diese 128 Werte wurden für verschiedene Länder unterschiedlich codiert -> Computer muss wissen welchen Codepage /(Tabelle, die sagt welche Zahl für welches Zeichen) für einen Text verwendet wird
-ISO/IEC 8889-1 (Latin-1) ist eine bestimmte 8-Bit-Zeichentabelle für westeuropäische Sprachen
-8 Bit = 1 Byte

***Unicode***
-wurde Ende 80er Jahre entwickelt mit der Idee für eine grosse Zeichentabelle
-anfangs mit 16-Bit codiert, dann auf 32-Bit in 2001 umgestellt -> enthält ca. 100000 verschiedene Zeichen aus unterschiedlichen Sprachen, auch von sehr alten Sprachen
-jedes Zeichen wird mit 4 Byte abgespeichert (= UTF-32) -> sehr viel Speicherplatz
-für weniger Speicher gibt es 2 Codierungen: 2 Byte (UTF-16), 1 Byte (UTF-8)

***UTF*** -8
-UTF-8 ist die häufigste verwendete Kodierung für Unicode-Zeichen (legt fest welche Nummer ein Zeichen bekommt)
-Speicherplatz für ein Zeichen kann zwischen 1-4 Bytes betragen
-Abkürzung UTF-8: UCS Transformation Format 8-Bit
-wurde als Standard durchgesetzt
-Empfehlung UTF-8 zu verwenden aber kein muss -> andere Codierung z.B. UTF-16
-die Bitfolge im ersten Byte eines Zeichens bestimmt die Länge des UTF-8-Zeichens: beginnt es mit 0XX... braucht es 1 Byte, beginnt es mit 110XX braucht es 2 Byte, beginnt es mit 1110XXX.. braucht es 3 Byte, beginnt es mit 11110XX... braucht es 4 Byte -> z.B. 'A' braucht 1 Byte 01000001



