Äänestyssovellus selaimessa
käyttötapaukset

1. Selaa äänestystuloksia
käyttäjä: käyttäjä, ylläpitäjä
laukaisija: sovelluksen etusivun avaaminen näyttää äänestykset
esiehto: 
jälkiehto: 
tapauksen kulku:
    1- käyttäjä avaa sovelluksen
    2- sovellus hakee ja näyttää käynnissä olevat äänestykset
    3- äänestyksen kohdalla näkyy sen tiedot ja äänet
    4- käyttäjä selaa listaa
poikkeustoiminta:
    - ei äänestyksiä: näytä ilmoitus
    - virhe tietokannassa: näytä ilmoitus


2a. Valitse äänestys
käyttäjä: käyttäjä, ylläpitäjä
laukaisija: käyttäjä valitsee äänestyksen klikkaamalla
esiehto: äänestys näkyy sivulla
jälkiehto: 
tapauksen kulku:
    1- käyttäjä klikkaa äänestystä etusivun listasta
    2- sovellus hakee valitun äänestyksen tiedot. näyttää äänestysvaihtoehdot
    3- 2b
poikkeustoiminta:
    -äänestys poistettu: näytä ilmoitus

2b. Äänestä
käyttäjä: käyttäjä
laukaisija: käyttäjä on valinnut äänestyksen ja klikkaa äänestä
esiehto: äänestys on auki, käyttäjä ei ole vielä antanut ääntä kys. äänestykseen
jälkiehto: annettu ääni tallentuu sovellukseen
tapauksen kulku:
    1- käyttäjä valitsee äänestysvaihtoehdon
    2- sovellus tallentaa annetun äänen
    3- päivittää äänestyksen tuloksen
    4- näyttää käyttäjälle Ok, äänestys onnistui
    5- sovellus näyttää päivitetyn äänestystuloksen
poikkeustoiminta:
    - käyttäjä on jo äänestänyt: ilmoitus "voit antaa vain yhden äänen"
    - virhe tietokannassa: näytä virheilmoitus


3. Luo uusi äänestys
käyttäjä: ylläpitäjä
laukaisija: ylläpitäjä klikkaa uusi äänestys
esiehto: ylläpitäjän oikeudet sivustolle
jälkiehto: uusi äänestys näkyy sivulla
tapauksen kulku:
    1- ylläpitäjä on kirjautunut sivulle
    2- klikkaa Lisää äänestys -> lomake aukeaa
    3- täyttää tiedot (nimi, kuvaus)
    4- hyväksyy -> äänestys tallentuu sivulle
    5- äänestys lisätty
    6- äänestys näkyy sivulla
poikkeustoiminta:
    - uusi äänestys -lomakkeessa tyhjää nimen tai kuvauksen kohdalla: 'täytä kaikki kohdat' -ilmoitus

4. Poista äänestys
käyttäjä: ylläpitäjä
laukaisija: poista äänestys-painike
esiehto: kirjautunut sivulle ylläpitäjänä
jälkiehto: äänestys poistuu tietokannasta ja sivulta
tapauksen kulku:
    1- ylläpitäjä on kirjautunut sivulle
    2- klikkaa 'poista äänestys' poistettavan kohdalla
    3- sovellus varmistaa 'oletko varma?' -> käyttäjä valitsee OK
    4- äänestys poistuu tietokannasta ja sivulta
poikkeustoiminta:
    - äänestystä ei löydy: näytä virheilmoitus