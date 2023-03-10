 ### Viikkoraportit:
 
[viikko 1](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/viikkorep/vko_1.md)
 
[viikko 2](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/viikkorep/vko_2.md)
 
[viikko 3](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/viikkorep/vko_3.md)
 
[viikko 4](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/viikkorep/vko_4.md)
 
[viikko 5](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/viikkorep/vko_5.md)
 
[viikko 6](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/viikkorep/vko_6.md)
 
 ## tuntikirjanpito
 [tässä](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/kirjanpito.md)
 
 ## Testaus ja toteutus
 [testausdokumentti](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/testaus.md)
 [toteutusdokumentti](https://github.com/sepaww/tira_projekti/blob/master/dokumentaatio/toteutusdokumentti.md)
## Näin saat pelin toimimaan:
kloonaa git clone -komennolla repositorio valitsemaasi git kansioon. muista siirtyä kloonatun kansion sisälle.
1. Asennetaan riippuvuudet komennolla:

```bash
poetry install
```

2. Käynnistetään peli komennolla:

```bash
poetry run invoke start
```

## Peliä voi myös käsitellä seuraavilla terminaali komennoilla:


### Testaus

Testit suoritetaan komennolla:

```bash
poetry run invoke test
```

### Testikattavuus

Testikattavuusreportin voi generoida komennolla:

```bash
poetry run invoke coverage-report
```

Reportin voi lukea _htmlcov_-hakemistosta tai terminaalista.

### Pylint

pelin koodin pelilogiikan laatua voi tarkastella komennolla

```bash
poetry run invoke lint
```
huom! koodia ei ole lintattu
