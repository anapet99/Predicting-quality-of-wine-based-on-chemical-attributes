# Predvidjanje kvaliteta vina na osnovu hemijskih atributa (engl. Predicting quality of wine based on chemical attributes)
Projekat predmeta Masinsko ucenje na smeru Industrija 4.0  
Autor: Aleksandra Petrovic  

###  Opis skupa
Posmatraju se dva skupa podataka koji se odnose na crvene i bele varijante portugalskog vina "Vinho Verde". Za više detalja, posetite: http://www.vinhoverde.pt/en/. Zbog problema privatnosti i logistike, dostupni su samo fizičko-hemijski (ulazni) i senzorni (izlazni) podaci (npr. nema podataka o vrsti grožđa, marki vina, ceni prodaje vina, itd.). Skup podataka je preuzet sa sajta https://archive.ics.uci.edu/dataset/186/wine+quality .   
Ima 11 atributa i 4898 instanci. Analiza se vrsila za skupu belog vina.

  Svi atributi su neprekidnog tipa. Nema nedostajucih podataka.

Ulazne promenljive (bazirane na fizičko-hemijskim testovima):  
1 - fiksna kiselost (fixed acidity)  
2 - fluktuirajuća kiselost (volatile acidity)  
3 - limunska kiselina (citric acid)  
4 - ostatak šećera (residual sugar)  
5 - hloridi (chlorides)  
6 - slobodan sumpor-dioksid (free sulfur dioxide)  
7 - ukupan sumpor-dioksid (total sulfur dioxide)  
8 - gustina (density)  
9 - pH  
10 - sulfati (sulphates)  
11 - alkohol (alcohol)  
  
Izlazna promenljiva (bazirana na senzornim podacima):  
12 - kvalitet - ocena između 0 i 10 (quality)  
  
Neizbalansirana podela po ocenama kvaliteta na osnovu histograma.

### Modeli 
  Podeljen je skup na test i trening. Izvrsena je standardizacija standardnim Scaler-om.  
Modeli korisceni u projektu su:  
 1.KNN (K najblizih suseda)  
 2.Linearna regresija sa tezinama    
3.AdaBoost  
4.Multinomijalna logisticka regresija  
5.Potpuno povezana neuronska mreza    

### Listing neophodnih paketa
Numpy  
Matplotlib  
Pandas  
Sklearn  
Tensorflow  
Keras  
Pygam



