# Zadatak 1 - Konvertor Crypto valuta

## Api
- preporuka je da se koristi [Cryptocompare api](https://www.cryptocompare.com/), ali dozvoljeno je koristiti i neki drugi po izboru
- [Dokumentacija Cryptocompare](https://www.cryptocompare.com/api/)
//ne bih slao koje endpointe trebaju da koriste, mislim da je korisno da kandidati sami istraze dokumentaciju ili mozda za Juniore da dodamo???
- [Lista coin-a](https://www.cryptocompare.com/api/data/coinlist/)
- [Trenutna vrednost](https://min-api.cryptocompare.com/data/price?fsym=BTC&tsyms=BTC,USD)
- [Istorija po minutu](https://min-api.cryptocompare.com/data/histominute?fsym=BTC&tsym=USD&limit=60&aggregate=3&e=CCCAGG)
- [Istorija po satu](https://min-api.cryptocompare.com/data/histohour?fsym=BTC&tsym=USD&limit=60&aggregate=3&e=CCCAGG)
- [Istorija po danu](https://min-api.cryptocompare.com/data/histoday?fsym=BTC&tsym=USD&limit=60&aggregate=3&e=CCCAGG)

## Lista svih coin-a
- prikazati listu svih coin-a koje nudi Api
- svaki element u listi treba da sadrzi
  - naziv
  - simbol
  - sliku
  - algoritam, *ako api podrzava*
  - ukupnu kolicinu coin-a (Total Coin Supply), *ako api podrzava*
- klikom na element u listi otvara se ekran sa detaljima

## Detalji coin-a

### Tab 1 opšti detalji
  - prikazati sve podatke iz liste
  - prikazati trenutnu vrednost valute u odnosu na: `BTC`, `ETH`, `EVN`, `DOGE`, `ZEC`, `USD`, `EUR`

### Tab 2 grafikoni
- prikazati grafikon 1 koji je slican slici ispod, prikazuje istoriju vrednosti coin-a po danu u poslednjih *X* dana u odnosu na `BTC`. Korisnik moze da izabere period kao što je prikazano na slici ispod, samo sa sledecim vrednostima: jedan dan, jedna nedelja, dve nedelje, mesec dana
- prikazati grafikon 2 koji je slican slici ispod, prikazuje istoriju vrednosti coin-a po satu u poslednjih *X* dana u odnosu na `BTC`. Korisnik moze da izabere period kao sto je prikazano na slici ispod, samo sa sledecim vrednostima: jedan dan, tri dana, nedelju dana
- prikazati grafikon 2 koji je slican slici ispod, prikazuje istoriju vrednosti coin-a po minutu u poslednjih *X* dana u odnosu na `BTC`. Korisnik moze da izabere period kao sto je prikazano na slici ispod, samo sa sledecim vrednostima: jedan sat, tri sata, jedan dan
<img alt="Crypto currency info-88966d4e.png" src="Crypto currency info.assets/Crypto currency info-88966d4e.png" width="" height="" >

## Napomene
- dozvoljeno je koristiti thirdy party biblioteke za komunikaciju sa API-em i parsiranje
- čuvanje i prikazivanje liste svih coin-a iz lokalne baze podataka kad nema interneta je plus
- za generisanje grafika nije dozvoljeno koriśćenje thirdy party biblioteka
- horizontalni scroll i prošireni period (da *X* bude znatno veci od navedenog, recimo godinu ili vise dana) prikaza istorije vrednosti coin-a je plus
- prikazivanje vrednosti coina u odnosu na vise različitih coina na istom grafiku je plus

## Napomena

Ukoliko budete imali dodatnih pitanja, slobodno pošaljite mail na <jobs@rbt.rs>.

Molimo vas napravite novi GitHub repo i korisite da tamo postavite rešenje zadatka zajedno sa uputstvom za pokretanje. Takođe vas molimo da nam link ka GitHub repu pošaljete uz prijavu za posao.

Kriterijumi za ocenu rešenja zadatka su:
- kvalitet primenjenog algoritma,
- čitljivost/urednost koda,
- brzina izvršavanja.