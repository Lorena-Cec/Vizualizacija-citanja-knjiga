# Vizualizacija čitanja knjiga

## Opis projektnog zadatka
Cilj ovog projekta je kreirati interaktivnu web aplikaciju koja omogućuje vizualizaciju podataka o pročitanim knjigama putem različitih grafičkih prikaza. Aplikacija omogućava korisnicima pregled broja pročitanih knjiga po godinama, žanrovima i mjesecima te pruža alate za interakciju i detaljniju analizu podataka.


## Hijerarhija projekta.
•	Index.html – glavni kod projekta
•	Style.css – glavni stilovi 
•	Books.csv – datoteka s podacima
•	/images – slike koje se koriste za prikaz ocjene knjige
o	Stars1.png
o	Stars2.png
o	Stars3.png
o	Stars4.png
o	Stars5.png
•	goodreads_library_export.csv – originalna datoteka s podacima

## Popis korištenih tehnologija

•	D3.js
•	HTML5
•	CSS3
•	CSV
•	Visual Studio Code     

## Upute za postavljanje.

1.	Klonirajte repozitorij: https://github.com/Lorena-Cec/Vizualizacija-citanja-knjiga
2.	Otvorite folder repozitorija u Visual Studio Code
3.	Pokrenite Live Server (ukoliko nemate Live Server instalirajte ga unutar Visual Studio Code)

## Upute za korištenje.

1.	Nakon pokretanja Live Servera pokrenit će se projekt u pregledniku
2.	Prikaz podataka:
•	Moguće je odabrati jednu ili više godina za koje želimo dobiti podatke
•	Klikom na jednu godinu prikazuju se različiti podaci o navikama čitanja te godine
•	Klikom na više godina uspoređuju se podaci između tih godina
3.	Interakcija s grafikonima za jednu godinu:
•	Omogućen je klik na stupce u stupčastom grafu nakon čega se prikazuje lista knjiga pročitanih u kliknutom mjesecu
•	Omogućen je klik na žanrove gdje se prikazuje lista knjiga pročitanih u kliknutom žanru 
•	U listi knjiga omogućen je klik na naziv knjige nakon čega se prikazuje naslovnica knjige I vlastita ocjena knjige
4.	Interakcija s grafikonima za odabir više godina:
•	Prelaskom miša na točku u linijskom grafu prikazuje se mjesec I godina koji su odabrani te broj knjiga pročitanih u odabranom razdoblju
•	Prelaskom miša na pie chartu prikazuje se godina koja predstavlja odabrani dio pie charta – u usporedbi dvije godine nije nužno koristiti ovu funkcionalnost jer sa strane postoji legenda, ali prilikom usporedbe više godina lakše je doći do podatka o odabranoj godini 
