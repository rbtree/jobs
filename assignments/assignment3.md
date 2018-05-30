# Zadatak 3 - Igra memorije

## Opis

Potrebno je napraviti [Igru Memorije](https://en.wikipedia.org/wiki/Concentration_(game))

## Zahtevi

* igra treba da ima tri nivoa - (4x4), (6x6), (8x8)
* prilikom pokretanja igre korisnik će moći da odabere nivo (samostalno odlučiti kako će ovaj deo vizuelno izgledati)
* nakon što korisnik uđe u igru, na ekranu treba da mu se prikaže grid za odabrani nivo
* svaka kartica treba da se sastoji od dve stranice
	* `lica` na kojem se nalazi slika koju treba upariti
	* i `naličja` na kome se nalazi pozadinska slika (ista za sve kartice)
* na početku igre sve kartice su okrenute licem na dole
* prilikom pritiska na karticu, kartica se okreće
* maksimalno dve kartice mogu biti otvorene u istom trenutku
* ukoliko otvorene kartice nisu iste, treba ih zatvoriti (nakon 1s ako korisnik ne preduzme nikakvu akciju ili čim pokuša da otvori treću karticu)
* ukoliko su otvorene kartice iste, one ostaju na ekranu
* na glavnom ekranu igre, pored grida, treba da budu prikazane i sledeće informacije
	* proteklo vreme od početka igre
	* broj klikova, odnosno pritisaka na kartice
	* dugme za pauziranje igre
* pritiskom na dugme `pauza` korisnik dobija opcije da
	* nastavi započetu igru
	* resetuje započetu igru
	* prekine igru (vraća se na početni ekran)
* igra se završava kada korisnik upari sve kartice
* po završetku igre korisniku omogućiti da se taj rezultat share-uje (Facebook, Twitter…)
* nakon što korisnik završi sa akcijom share-ovanja, portrebno je da mu se na ekranu prikaže rang lista sa mogućnošću da upiše svoje ime ako je u prvih 10 rezultata (rezultate čuvati u file-u i pamtiti 10 najboljih rezultata)
	* rezultate čuvati po nivou težine igre
	* prvi kriterijum za sortiranje je broj klikova
	* drugi kriterijum za sortiranje je proteklo vreme
* sa ovog ekrana korisnik može da se vrati na početni odakle ponovo može da započne igru

## Bonus

* implementirati animaciju za okretanje kartica
* implementirati custom tranzicije između ekrana

## Napomena

Ukoliko budete imali dodatnih pitanja, slobodno pošaljite mail na <jobs@rbt.rs>.

Molimo vas napravite novi GitHub repo i korisite da tamo postavite rešenje zadatka zajedno sa uputstvom za pokretanje. Takođe vas molimo da nam link ka GitHub repu pošaljete uz prijavu za posao.

Kriterijumi za ocenu rešenja zadatka su:
- kvalitet primenjenog algoritma,
- čitljivost/urednost koda,
- brzina izvršavanja.