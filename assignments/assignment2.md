# Zadatak 2 - Music player

## Opis

Potrebno je napraviti aplikaciju za pregled i stream-ovanje muzike koristeći [Free Music Archive API](https://freemusicarchive.org/api) (API key -> `CFEFES9JPKBN4T7H`)

## Zahtevi

* prvi ekran treba da sadrži listu žanrova 
    * implementirati paginaciju
    * za svaki žanr u listi treba prikazati
        * naziv
        * boju
* odabirom žanra iz liste prikazati sledeći ekran sa listom pesama
    * implementirati paginaciju
    * za svaku pesmu u listi prikazati
        * naziv pesme
        * naziv autora
        * play, pause, stop i download opcije
    * klikom na `play` dugme stream-uje se odabrana pesma i prikazuje Player Bar na dnu ekrana
    * klikom na `stop` dugme (iz Player Bar-a ili u listi) zaustaviti stream i sakriti Player Bar
    * animirati prikazivanje i skrivanje Player Bar-a
    * inicijalno Player Bar nije vidljiv
        * Player Bar treba da sadrži
            * naziv pesme
            * dužinu pesme
            * seek bar
            * stop, play/pause opcije (koje se menja u zavisnosti da li pesma puštena). 
    * omogućiti premotavanje uz pomoć seek bar-a
    * `stop` dugme treba da bude disable-ovano ukoliko se pesma ne stream-uje
    * klikom na `download` dugme treba skinuti pesmu i sačuvati je na telefonu
    * stream-ovanje pesma se ne prekida ako korisnik scroll-uje kroz listu
* odabirom pesme iz liste prikazati ekran sa detaljima
    * ukoliko sa neka pesma stream-uje, stream se ne prekida i Player Bar je i dalje vidljiv
    * ekran sa detaljima pesme mora da sadrži dugme `Show All Artist Albums`
* klikom na `Show All Artist Albums` prikazati ekran sa listom svih albuma tog izvođača
    * ukoliko sa neka pesma stream-uje, stream se ne prekida i Player Bar je i dalje vidljiv
* odabirom albuma iz liste prikazati web stranicu albuma unutar aplikacije
    * ukoliko sa neka pesma stream-uje, stream se ne prekida i Player Bar je i dalje vidljiv
* ukoliko korisnik zatvori ili minimize-uje aplikaciju, pauzirati stream
* ukoliko korisnik primi ili pokuša da ostvari telefonski poziv, pauzirati stream

## Bonus

* napraviti API manager po uzoru na diagram

![diagram](/assets/img/assignment2_0.png "Diagram")

## Napomena

Ukoliko budete imali dodatnih pitanja, slobodno pošaljite mail na <jobs@rbt.rs>.

Molimo vas napravite novi GitHub repo i korisite da tamo postavite rešenje zadatka zajedno sa uputstvom za pokretanje. Takođe vas molimo da nam link ka GitHub repu pošaljete uz prijavu za posao.

Kriterijumi za ocenu rešenja zadatka su:
- kvalitet primenjenog algoritma,
- čitljivost/urednost koda,
- brzina izvršavanja.