-JSON = JavaScript Object Notation (ABKÜRZUNG) -> Data representation format
-JSON ist eine Beschreibungssprache -> man kann mit JSON Informationen speichern und von Computer zu Computer senden
-JSON ist ein Standardformat, um Daten strukturiert dazustellen und zwischen Programmen auszutauschen
-JSON ist keine Programmiersprache, sondern ein Datenformat
-text format um Daten zu speichern
-es besteht hauptsächlich aus Key-Value-Paaren -> z.B "name": "Anna"
-ein JSON Objekt beginnt mit { und endet mit }:
{
  "name": "Anna",
  "alter": 25
}
-> alles zwischen { } gehört zum Objekt
-für Texte werden doppelte Anführungszeichen benutzt ("Anna") 
-für Zahlen braucht es keine Anführungszeichen (25)
-JSON erkennt auch Booleans, keine Anführungszeichen (true, false)
-ein Array ist eine Liste von mehreren Werten, man benutzt [ ] Klammern:
{
  "hobbys": ["Fussball", "Lesen", "Gaming"]
}
-es gibt 6 Datentypen von JSON:
		-String, "Hallo"
		-Zahl, 42
		-Boolean, true/false
		-Null, null
		-Object, {"name": "Anna"}
		-Array, [1, 2, 3]
-Eigenschaften von einem Objekt werden mit Kommas getrennt
-Syntax ist ähnlich zu JavaScript object syntax aber hat unterschiede
-einfach zum lesen/schreiben
-die Syntax von JSON text und JavaScript objects sieht sehr ähnlich aus

***JSON Applications***
-extenseion: .json
-JSON.parse() -> konventiert strings in JavaScript Objects
-wird benutzt um Daten zu senden, empfangen und speichern
-JSON.parse() method wird benutzt um JSON text in JavaScript werten umzuwandeln
-JSON.stringify() method wird benutzt um einen JavaScript Wert in JSON text umzuwandeln
-JSON Files kann man mit einem Text Editor erstellen und dann mit .json speichern
-JSON Internet-Media type ist application/json

***Anwendung***
-oft für APIs und Configs, Text editors benutzt -> Webserver und APIs benutzen JSON um öffentliche Daten bereit zu stellen
-JSON wird benutzt um Daten zwischen Server und Client zu übertragen
-wird benutzt während man JavaScript Applikationen schreibt -> kann Browser Extensions und Webseiten beinhalten
-kann mit modernen Programmiersprachen verwendet werden

***JSON Types***
-Strings
-Numbers
-Booleans
-null
-Arrays
-Objects

***Beispiel***
-JSON text der eine Person beschreibt 
-beschreibt ein object mit 3 propterties
{  
  "name": "John",  
  "age": 30,  
  "city": "New York"  
}

-jeder property hat einen Namen -> "name", "age", "city"
-jeder property hat einen Value -> "John", 30, "New York"

***Weshalb man JSON benutzt***
-Computer und Applikationen müssen oft Daten austauschen
-JSON hat einen einfachen text format, der viele Computer verstehen
-oft benutzt für: 
		-Daten von einer web page zu einem server zu schicken
		-Daten von einem web server zu einer web page zu schicken
		-strukturierte Daten in Files zu speichern
		-Daten zwischen Apllikationen auszutauschen

***Beispiel JSON zu JavaScript umwandeln***
// JSON text  
const text = '{"name":"John", "age":30, "city":"New York"}';  
  
// Parse the JSON text  
const person = JSON.parse(text);

***Beispiel JavaScript zu JSON umwandeln***
const person = {  
  name: "John",  
  age: 30,  
  city: "New York"  
};  
  
const text = JSON.stringify(person);  
  
document.getElementById("demo").innerHTML = text;

***Daten speichern***
-JSON ermöglicht es JavaScript als text zu speichern
-JSON Daten kann man auch in einem File speichern -> .json extension

-[[Auftrag JSON Adressdaten interpretieren]]
-[[Auftrag JSON Steckbrief]]











