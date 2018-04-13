# Zadatak 2 - Music player

## Opis
Potrebno je napraviti aplikaciju za pregled i streaming muzike koristeći [Free Music Archive API](https://freemusicarchive.org/api)

## Zahtevi

* prvi ekran treba da sadrži listu žanrova 
	* implementirati paginaciju
	* za svaki žanr u listi treba prikazati
		* naziv žanra
		* boju vezanu za žanr
* odabirom žanra iz liste prikazati sledeći ekran sa listom pesama za taj žanr
	* implementirati paginaciju
	* za svaku pesmu u listi prikazati
		* naziv pesme
		* naziv autora
		* play, pause, stop i download opcije
	* klikom na `play` dugme započeti stream za odabranu pesmu i prikazati Player Bar na dnu ekrana
	* klikom na `stop` dugme (iz Player Bar-a ili u listi) zaustaviti stream i sakriti Player Bar
	* animirati prikazivanje i skrivanje Player Bar-a
	* inicijalno Player Bar nije vidljiv
		* Player Bar treba da sadrži
			* naziv pesme
			* dužinu pesme
			* seek bar
			* stop, play/pause opcije 
	* omogućiti premotavanje uz pomoć seek bar-a
	* `stop` dugme treba da bude disable-ovano ukoliko se pesma ne stream-uje
	* klikom na `download` dugme treba skinuti pesmu i sačuvati je na telefonu
	* streaming pesma se ne prekida ako korisnik scroll-uje kroz listu
* odabirom pesme iz liste prikazati ekran sa detaljima za tu pesmu
	* ukoliko sa neka pesma stream-uje, stream se ne prekida i Player Bar je i dalje vidljiv
	* ekran sa detaljima pesme mora da sadrži dugme `Show All Artist Albums` 
* klikom na `Show All Artist Albums` prikazati ekran sa listom svih albuma tog izvođača
	* implementirati paginaciju
	* ukoliko sa neka pesma stream-uje, stream se ne prekida i Player Bar je i dalje vidljiv
* odabirom albuma iz liste prikazati web stranicu za taj albuma (unutar aplikacije)
	* ukoliko sa neka pesma stream-uje, stream se ne prekida i Player Bar je i dalje vidljiv
* ukoliko korisnik zatvori ili minimize-uje aplikaciju, pauzirati stream
* ukoliko korisnik primi ili pokuša da ostvari telefonski poziv, pauzirati stream

## Bonus

* implementirati search
* napraviti API manager po uzoru na diagram

![diagram]({{ "/assets/img/assignment2_0.png" | absolute_url }})

## Napomena

Ukoliko budete imali dodatnih pitanja, slobodno pošaljite mail na <jobs@rbt.rs>.

Molimo vas napravite novi GitHub repo i korisite da tamo postavite rešenje zadatka zajedno sa uputstvom za pokretanje. Takođe vas molimo da nam link ka GitHub repu pošaljete uz prijavu za posao.

Kriterijumi za ocenu rešenja zadatka su:
- kvalitet primenjenog algoritma,
- čitljivost/urednost koda,
- brzina izvršavanja.