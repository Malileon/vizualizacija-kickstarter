Kako bi se projekt pokrenio, potrebno je imati VS Code sa ekstenzijom Live Server, 
te klonirati projekt iz git-a / extractat zipani file sa merlin-a. Nakon toga je potrebno 
otvoriti VS Code u tom folderu, te u donjem desnom kutu kliknuti na „Go Live“. Nakon toga 
se defaultni web browser otvara sam i vizualizacija podataka je spremna za korištenje.

Nakon što se otvori browser, user vidi naslov projekta i prikaz mape sa obojanih 20 država 
koje se mogu prikazati na vizualizaciji zbog dataset-a. Države su obojane u nijansama zelene 
boje ovisno o njihovoj populaciji (tamnija boja oznaćava veću populaciju).

Hoverom na neku od država se vide podaci o istoj, tj. vidi se naziv države i njena 
populacija u tooltip-u. Klikom na neku od obojanih država se nakon kratkog delay-a zbog 
količine podataka prikazuju 2 grafa i ime kliknute države.

Pie chart prikazuje raspodijelu Kickstarter projekata po kategorijama u kliknutoj državi. 
Svaka kategorija je oznaćena svojom bojom koja je jednaka kao i na Barchartu. Hoverom na 
segment pie charta se prikazuje tooltip imena kategorije i točnog broja projekata u toj 
kategoriji. Na dnu pie charta je prikazan ukupan broj Kickstarter projekata u toj državi.
Bar chart prikazuje zbroj ljudi koji su podržali projekt iz pojedinih kategorija. Hoverom 
na pojedini bar se vidi točan broj podržavatelja.
