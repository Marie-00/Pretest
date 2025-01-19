# Pretest
Codebuch						
			
Edgeliste:		
from:	definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort	

to: 	definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 

weight:	Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen.

relationship:	definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten	

time:	definiert einen Zeitraum, in dem die Beziehung zwischen zwei Knoten stattgefunden hat oder beobachtet wurde.		
			
Nodeliste:			
id:	Eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird	

name:	Name oder Bezeichnung des Knotens. 		

type:	Was ist es, Kunstwerk, Museum oder Person? Person=1, Museum=2, Kunstwerk=3, relevant bei two-mode Netzwerken, um die Unterscheidung zwischen z.B. Akteur und Event zu berechnen.

object_type:	Gemälde=1, Skulptur=2, Gegenstand=3	

role:	Wer ist er? Kunsthändler/Privatperson ... -> noch zu klären wie codierbar und sinnvoll		

year:       	Welches Jahr im Besitz -> noch zu klären wie codierbar und sinnvoll		

location:	Wo im Besitz -> noch zu klären wie codierbar und sinnvoll		

status:	 Keine Rückgabe an Erben/Besitzer=1, Rückgabe an Erbe/ursprünglichen Besitzer=2		
			
			
NA:	definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..		
