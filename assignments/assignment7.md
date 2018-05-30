# Zadatak 7 - last.fm  top 10 Rock izvođača

## Zahtevi

Korišćenjem **Angular 5**, **Bootstrap 4** i **[last.fm API-a](https://www.last.fm/api/intro)** potrebno je napraviti aplikaciju koja će prikazivati top 10 Rock izvođača, njihove albume i pesme.

Aplikacija se sastoji od 2 stranice:

1. Na početnoj strani treba prikazati *top 10 Rock izvođača* u vidu kartica (320x320px).

    * Na prednjoj strani kartice prikazati sliku izvođača, poziciju na rang listi i naziv izvođača.
    * Prelaskom kursora preko kartice, kartica se okreće oko vertikalne ose i prikazuje se poleđina kartice.
    * Na poleđini kartice prikazati: 
        - kratak opis izvođača (summary) i ograničiti broj prikazanih karaktera na 300,
		- dugme "Albums" koje vodi na stranicu sa albumima odabranog izvođača

2. Na stranici sa Albumima treba prikazati maksimalno 10 albuma, takođe u vidu kartica (istih dimenzija kao i na početnoj strani)

	* Na prednjoj strani kartice prikazati sliku albuma i naziv albuma.
	* Prelaskom kursora preko kartice dešava se ista animacija kao i na početnoj strani.
	* Na poleđini kartice prikazati listu pesama sa albuma (redni broj pesme, naziv pesme), klik na pesmu vodi na last.fm stranicu pesme.
	* Implementirati "infinite scroll", svaki put kad se odskrola na dno stranice treba učitati jos 10 albuma i njihovih pesama.
	* Implementirati pretragu po imenu albuma.

## Napomena

Ukoliko budete imali dodatnih pitanja, slobodno pošaljite mail na <jobs@rbt.rs>.

Molimo vas napravite novi GitHub repo i korisite da tamo postavite rešenje zadatka zajedno sa uputstvom za pokretanje. Takođe vas molimo da nam link ka GitHub repu pošaljete uz prijavu za posao.

Kriterijumi za ocenu rešenja zadatka su:
- kvalitet primenjenog algoritma,
- čitljivost/urednost koda,
- brzina izvršavanja.