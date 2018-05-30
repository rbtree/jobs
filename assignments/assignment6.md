# Zadatak 6 - Najkraći put na mapi

## Opis

Potrebno je pronaći najkraći put između dve tačke na mapi (primer mape se nalazi na slici ispod).

![map]({{ "/assets/img/assignment6_0.png" | absolute_url }})

## Zahtevi

Potrebno je napraviti konzolnu aplikaciju u programskom jeziku po izboru. Potrebno je da program:
- prihvata putanju do dokumenta kojim je opisana mapa (koordinate mape, početna i krajnja tačka puta; primer u nastavku) kao ulazni parametar (obavezan parametar),

```xml
<?xml version="1.0" encoding="UTF-8"?>
<map>
	<cells>
		<cell row="1" col= "A" />
		<cell row="1" col= "B" />
		<cell row="1" col= "C" />
		<cell row="1" col= "D" />
		<cell row="2" col= "B" />
		<cell row="3" col= "A" />
		<cell row="3" col= "B" />
		<cell row="3" col= "C" />
		<cell row="3" col= "D" />		
		<cell row="4" col= "A" />
		<cell row="4" col= "C" />
		<cell row="4" col= "D" />		
	</cells>	
	<start-point row="1" col= "C" />
	<end-point row="4" col= "C" />
</map>
```

- prihvata putanju do dokumenta u kome će biti sačuvano rešenje zadatka kao ulazni parametar (nije obavezan parametar),
- prikazuje poruku o grešci ukoliko obavezni parametri nisu specificirani ili su specificirani u pogrešnom formatu,
- prikazuje poruku o grešci ukoliko sadržaj dokumenta kojim je opisana mapa nije u odgovarajućem formatu,
- kao rezultat generiše dokument (primer u nastavku) čiji sadržaj bi trebalo da bude lista najkraćih putanja za zadate tačke, kao i vreme izvršenja,

```json
{
	"execution_time_in_ms": 10,	
	"paths": [
		{
			"points":[
				{
					"row": 1,
					"col": "C"
				},
				{
					"row": 1,
					"col": "B"
				},
				{
					"row": 2,
					"col": "B"
				},			
				{
					"row": 3,
					"col": "B"
				},
				{
					"row": 3,
					"col": "C"
				},
				{
					"row": 4,
					"col": "C"
				}
			]
		}
	]
}
```

- prikazuje putanju do dokumenta u kome se nalazi rešenje zadatka

## Bonus

Za bonus poene, potrebno je sav kod pokriti Unit testovim i/ili izložiti prethodno implemetiranu funkcionalnost kroz REST API.

## Napomena

Ukoliko budete imali dodatnih pitanja, slobodno pošaljite mail na <jobs@rbt.rs>.

Molimo vas napravite novi GitHub repo i korisite da tamo postavite rešenje zadatka zajedno sa uputstvom za pokretanje. Takođe vas molimo da nam link ka GitHub repu pošaljete uz prijavu za posao.

Kriterijumi za ocenu rešenja zadatka su:
- kvalitet primenjenog algoritma,
- čitljivost/urednost koda,
- brzina izvršavanja.