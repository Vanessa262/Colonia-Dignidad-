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

power
- definiert die Macht des Knotens in der Kolonie  
- 1 = Frauen die es geschafft haben aus der Kolonie zu fliehen
- 2 = Männer die es geschafft haben aus der Kolonie zu fliehen 
- 3 = Personen (Politiker, Justiz usw.) die von außerhalb Einfluss auf die Geschehnisse in der Kolonie hatten
- 4 = Personen die zum Unterdrückungsapparat gehörten
- 5 = Personen die in der Führungsebene der Kolonie waren
- 6 = Personen, die im Waffenhandel involviert waren
- 0 = keine Macht (z.B. normale Bewohner der Kolonie und Personen außerhalb der Kolonie, die keinen Einfluss auf die Geschehnisse in CD hatten) 

age
- 0 = Organisationen/Unternehmen/Verbände
- 1 = bis 30 Jahre
- 2 = 31 bis 40 Jahre
- 3 = 41 bis 50 Jahre
- 4 = 51 und älter
- 5 = verstorben

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
- 4 = Schweiz
- 5 Mexiko

subject (Beziehungsebene zu Paul Schäfer)
- 1 = Politik
- 2 = Wirtschaft
- 3 = Medizin 
- 4 = Justiz 
- 5 = Religion 
- 6 = Mitglied
- 7 = Familie
- 8 = Sonstiges
- 9 = ging gegen Paul Schäfer vor
- 10 = Waffenhandel

type 
- 0=Person
- 1=Organisation
 
# Edge-Attribute:

id (eindeutige Codierung der Knoten)
- codiert mit vollem Namen der Person oder Organisation
 
from 
- definiert den Sender 

to
- definiert den Empfänger
 
relation (Beziehungsart zwischen den Personen/Organisationen)
- 1 = work Geschäftliche Beziehung: Die Beziehung basiert rein auf geschäftlicher Ebene, arbeiten ohne spezielle Unterstützung wie durch beispielsweise Geld
- 2 = help Unterstützungsbeziehung: Die Beziehung basiert auf aktive Unterstützung/ Zustimmung gegenüber der Colonia Dignidad -> Unterstützung in Kombination mit einem bestimmten Vorteil (korruptiv)
- 3 = friendship freundschaftliche/private Beziehung zwischen Akteuren
- 4 = hostility Person ging gegen Paul Schäfer und seine Machenschaften vor
- 5 = abuse Person wurde von Paul Schäfer physisch oder psychisch misshandelt
- 6 = relatives Verwandschaft von Paul Schäfer
- 7 = support Leugnung von Paul Schäfers Menschenrechtsverletzungen und anderen negativen Taten die gegen ihn aussagten
- 8 = marriage
- 9 = Mitglied der "Herren"
- 10 = Waffenhandel

period (Zeitspanne, in der eine Verbindung zwischen den Personen/Organisationen bestand)
- 1 = vor der Gründung der Colonia Dignidad
- 2 = während die Colonia Dignidad in Deutschland bestand
- 3 = während die Colonia Dignidad in Chile bestand
- 4 = nach der Colonia Dignidad
 
