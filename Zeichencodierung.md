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
der Unterschied liegt in wie viele verschiedene Ziffern zur Verfügung stehen

Dezimalsystem (DEC)
-10 Stellen/Ziffern zur Verfügung von 0-10
-nach der 9 sind alle Ziffern aufgebraucht also: 8 → 9 → 10 → 11 → 12 ...

Oktalsysten 




