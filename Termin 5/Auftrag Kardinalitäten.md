Aufgabe 1

![[Pasted image 20261029100631.png]]
**Adresse - Person**                 1:m 
**Buch - Autor**                        mc:m  
**Mutter - Kind**                       1:m  
**Mann - Frau**                         mc:mc  
**Mitarbeiter - Vorgesetzte**    m:1  
**Eltern - Kind**                         1:m 
**Klasse - Lehrperson**             mc:m 
**Zeitung - Inserat**                 1:m  
**Fahrzeug - Lenkrad**             c:1  
**Geschäft - Kunde**                 mc:mc  
**Person - Geburtsort**             mc:1

Aufgabe 2
![[Pasted image 20261029101820.png]]
**rechte Schuhe - linke Schuhe**          1:1 (Paare)  
**Abteilung - Personal**                        1:1 (Abteilungsleiter)  
**Person - Abteilungen**                       m:1 (Abteilungszugehörigkeit)  
**Kinder - Ehepaare**                             mc:1 (Familienzugehörigkeit)  
**Personen - Parteien**                          m:1 (Parteizugehörigkeit)  
**Projekte - Projekte**                            mc:1 (ist Unterprojekt)  
**Vorlesungen - Studenten**                 m:n (Einschreibung)  
**Personen - Personen**                        mc:mc (Freundschaften)

Aufgabe 3
![[Pasted image 20261029102244.png]]
**Auto - Person**                 1:m (ist im Auto)  
**Auto - Person**                 mc:1 (gehört)  
**Auto - Person**                 1:m (wird zugeteilt)  
**Auto - Person**                  mc:mc (darf fahren)