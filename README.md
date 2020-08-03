# Codebuch
Kohlekommission Netzwerk    
Datensatz der Mitglieder der Kohlekommission   

Codebuch Stand 2020-07-15 erstellt von Brigitte Buck (bb095@hdm-stuttgart.de) 

## Inhalt 

Edges.csv (Edgelist)  
Nodes.csv (Nodelist)  
Codebuch.rm (Codierung der Datensätze)  

## Ursprung und Datenerhebung 
Ich habe den Datensatz der Mitglieder der Kohlekommission aus folgenden Artikeln zusammegestellt: 

- Mitlgieder der Kohlekomission: https://www.klimareporter.de/deutschland/das-sind-die-mitglieder-der-kohlekommission
- Ergänzung der personenbezogenen Daten durch das Munzinger Archiv: https://www.munzinger.de/search/start.jsp
- Faktencheck durch die Pressemeldung des BMWI: https://www.bmwi.de/Redaktion/DE/Pressemitteilungen/2018/20180606-bundeskabinett-setzt-kommission-wachstum-strukturwandel-und-beschaeftigung-ein.html

Das Netzwerk ist ein *ungerichtetes two-mode Netzwerk (Akteur-Organisationen)*.   

# EDGE-Attribute  

**from** (id Mitglied der Kommision) 

**to** (alle Mitgliedschaften der Person, soweit recherchierbar, dazu gehört z.B. politische Partei, Unternehmen, Verbände, Vereine und weitere Organisationen)  

# NODE-Attribute  

**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten.   

**type**  
Identifizierung Person oder Organisation: 
0 = person   
1 = organization  

**sex**   
Geschlecht der Person:   
1 = weiblich  
2 = männlich  
3 = divers  

**age**         
Geburtsjahr der Person:             
1 = 1930 bis 1940     
2 = 1941 bis 1950       
3 = 1951 bis 1960     
4 = 1961 bis 1970     
5 = 1971 bis 1980         
6 = 1981 bis 1990       
7 = 1991 bis 2000     
8 = später als 2000     

**party**       
Persönlicher Mitgliedschaft in politischer Partei:       
1 = CDU   
2 = SPD   
3 = AFD   
4 = FDP   
5 = DIE LINKE     
6 = GRÜNE   
7 = CSU   

**representation**    
Funktion der Person innerhalb der Kommission:   
1 = Politik   
2 = Wirtschaft    
3 = Gewerkschaft   
4 = Umwelt    
5 = Regionen  
6 = Wissenschaft  

**position**     
Position der Person:    
1 = Vorsitz   
2 = Mitglied   
3 = kein Stimmrecht   

**state**   
Bundesland des Geburtsortes:    
1 = Baden-Württemberg    
2 = Bayern   
3 = Berlin   
4 = Brandenburg     
5 = Bremen   
6 = Hamburg   
7 = Hessen  
8 = Mecklenburg-Vorpommern  
9 = Niedersachsen  
10 = Nordrhein-Westfalen  
11 = Rheinland-Pfalz  
12 = Saarland 
13 = Sachsen    
14 = Sachsen-Anhalt  
15 = Schleswig-Holstein   
16 = Thüringen   
17 = anderes Land

**children**    
Hat die Person Kinder?    
1 = ja    
2 = nein    

##  

