## Vaatimukset 

- Kuvaile tänne funktionaaliset ja ei-funktionaaliset vaatimukset? 
- Muista esittää vaatimukset jäljitettävässä muodossa, yksiselitteisesti. Keskeinen tapa (erityisesti ei-funktionaalisiin vaatimuksiin) yksiselitteisille kuvauksille on vaatimusten mitattavuus (software metrics)

•	Funktionaaliset vaatimukset tarkentavat käyttötapauksia

1.	Pelin kielen voi muuttaa asetusnäkymästä, vaihtoehtoina suomi, saksa, englanti, venäjä ja kiina
2.	Peliä voi pelata kosketusnäytöllä tai tavallisen näppäimistön nuolinppäimillä
3.	Peli tunnistaa käyttäjät kampuksen verkkoon kytkettyjen laitteiden fyysisten osoitteiden avulla
4.	Pelisuorituksia voi kommentoida (kommentti korkeintaan 50 merkkiä pitkä)
5.	Pelaaja voi vaihtaa nimimerkkinsä
6.	Pelaajan nimimerkki näkyy myös muille käyttäjille
7.	Pelaaja voi lisätä oman kuvansa
8.	Pelaaja voi vaihtaa haluamansa koulutusohjelman, jonka lukujärjestyksen mukaan hän pelaa
9.	Pelaajan ansaitsemat pisteet ilmoitetaan kokonaislukuna
10.	Pelaaja ansaitsee pisteitä tehtävän suoritukseen kuluvan ajan mukaan
11.	Pelaaja ansaitsee lisäpisteitä matkan varrella virtuaalisesti löytämistään kavereista, jotka sovellus on arponut satunnaisesti paikalla olijoista
12.	Pelaaja menettää pisteitä, jos hänet matkan varrella virtuaalisesti näkee joku muu kuin hänen kaverinsa
13.	Pelin edetessä tasot vaikeutuvat ja tehtävät, joissa tarkoituksena on suunnistaa paikasta toiseen, monimutkaistuvat
14.	Painettaessa back-nappulaa käyttäjä pääsee aina edelliseen näkymään
15.	Käyttäjä voi lopettaa pelaamisen koska tahansa painamalla logout-nappulaa
16.	Pelin kaatuessa lähetetään virheilmoitus automaattisesti ylläpitoon

•	Ei-funktionaaliset vaatimukset Esim käytettävyyteen, tietoturvaan, tehokkuuteen, skaalautuvuuteen, hintaan ja prosessimalliin liittyvät vaatimukset

- Tietoturvallisuus:

1.	Käyttäjän henkilökohtaiset tiedot eivät vuoda julkisuuteen
2.	Peli ei vaadi käyttäjältä muiden tietojen antamista kuin nimimerkin, salasanan ja sähköpostin
3.	Peli ei kerää käyttäjästä muita tietoja, kuin sijainnin, pelisuoritukset ja mahdolliset kommentit

- Käytettävyys:

4.	Pelistä oma malli eri laitteille; kännykälle, tabletille, tietokoneelle, pelistä oma 
5.	Pelistä oma malli eri järjestelmille; android, ios, windows
6.	Käyttäjän tulisi oppia pelin käyttö 5 minuutissa

- Tehokkuus:

7.	Peliä tulee pystyä pelaamaan yhtäaikaisesti 1000 pelaajaa
8.	Pelissä toisten käyttäjien suorituksia voi yhtäaikaisesti kommentoida 100 käyttäjää
9. Pelin käynnistämiseen kuluva aika saa olla korkeintaan 5 sekuntia
10. Pelin kaatuessa peli käynnistää itsensä uudelleen 10 sekunnin kuluessa

- Hinta:

11. Peli on ladattavissa ilmaiseksi Metropolian verkkosivuilta
