# Colonia-Dignidad-
Codebuch
# Node-Attribute: 

id
- Identische ID wie aus der Edgelist zur Identifikation der Knoten 

name 
- Name oder Bezeichnung des Knotens

sex 
- Geschlecht des Knotens 
- male=1 
- female=2 
- divers (Organisationen)=3

power
- definiert die Macht des Knotens 
- 1=sehr gering -- 5=sehr hoch

age
- 0 = Organisationen/Unternehmen/Verbände
- 1 = bis 30 Jahre
- 2 = 31 bis 40 Jahre
- 3 = 41 bis 50 Jahre
- 4 = 51 und älter

nationality (aktueller Sitz)     
- 0 = international (bei Organisationen)
- 1 = Nordamerika
- 2 = Südamerika
- 3 = Asien 
- 4 = Europa
- 5 = Australien

country
- 1 = Chile
- 2 = Deutschland
- 3 = Argentinien 

subject (Tätigkeitsbereich)
- 1 = Politik
- 2 = Wirtschaft
- 3 = Finanzen 
- 4 = Justiz 
- 5 = Religion 
- 6 = divers
 
# Edge-Attribute:

id (eindeutige Codierung der Knoten)
- codiert von 1 bis XX, jede ID entspricht einem Unternehmen/Organisation/Verband bzw. einer Person
 
from 
- definiert den Sender 

to
- definiert den Empfänger
 
relation (Beziehungsart zwischen den Personen)
- 1 = work Geschäftliche Beziehung: Die Beziehung basiert rein auf geschäftlicher Ebene, arbeiten ohne spezielle Unterstützung wie durch beispielsweise Geld
- 2 = help Unterstützungsbeziehung: Die Beziehung basiert auf aktive Unterstützung/ Zustimmung gegenüber der Colonia Dignidad -> Unterstützung in Kombination mit einem bestimmten Vorteil (korruptiv)
- 3 = friendship freundschaftliche/private Beziehung zwischen Akteuren
 
