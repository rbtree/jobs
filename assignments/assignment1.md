# Zadatak 1 - Praćenje vrednosti Crypto valuta

## Opis

Potrebno je napraviti aplikaciju za uporedni prikaz vrednosti Crypto valuta koristeći [Cryptocompare API](https://www.cryptocompare.com/api/)

## Zahtevi

* prvi ekran treba da sadrži listu svih crypto valuta koje API podržava
	* za svaku crypto valuta u listi treba prikazati
		* naziv
		* simbol
		* sliku
* odabirom crypto valute iz liste prikazati detalje za tu crypto valutu
	* prikaz treba da sadrži dva tab-a
		* opšti podaci
			* prikazati sve podatke za odabranu crypto valutu
			* prikazati trenutnu vrednost crypto valute u odnosu na: `BTC`, `ETH`, `EVN`, `DOGE`, `ZEC`, `USD`, `EUR`
		* grafički prikaz
			* prikazati istoriju vrednosti crypto valute po danu u poslednjih `X` dana u odnosu na `BTC` 
				* korisnik može da izabere period: jedan dan, jedna nedelja, dve nedelje, mesec dana
			* prikazati istoriju vrednosti crypto valute po satu u poslednjih `X` dana u odnosu na `BTC`
				* korisnik može da izabere period: jedan dan, tri dana, nedelju dana
			* prikazati istoriju vrednosti crypto valute po minutu u poslednjih X dana u odnosu na `BTC`
				* korisnik može da izabere period: jedan sat, tri sata, jedan dan
			* nije dozvoljeno koristiti third-party biblioteke za iscrtavanje grafikona
			* grafički prikaz uraditi po uzoru na diagram
			
			![diagram]({{ "/assets/img/assignment1_0.png" | absolute_url }})

## Bonus

* prikazati vrednost crypto valute u odnosu na više različitih crypto valuta na istom grafikonu
* koristiti lokalnu bazu podataka u slučaju kada korisnik nema internet pristup

## Napomena

Ukoliko budete imali dodatnih pitanja, slobodno pošaljite mail na <jobs@rbt.rs>.

Molimo vas napravite novi GitHub repo i korisite da tamo postavite rešenje zadatka zajedno sa uputstvom za pokretanje. Takođe vas molimo da nam link ka GitHub repu pošaljete uz prijavu za posao.

Kriterijumi za ocenu rešenja zadatka su:
- kvalitet primenjenog algoritma,
- čitljivost/urednost koda,
- brzina izvršavanja.