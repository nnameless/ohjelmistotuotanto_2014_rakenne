

### Käyttöliittymän näkymät

* Asennusnäkymä
* Rekisteröitymis/sisäänkirjautumisnäkymä
* Asetusnäkymä
* Valikkonäkymä
* Pelinäkymä (päänäkymä)
* Kommenttinäkymä
* Uloskirjautumisnäkymä

### Käyttötapaukset ja käyttöliittymät

Käyttötapauksien yhdistämisellä käyttöliittymään voidaan kuvata sovelluksen realistinen toiminnallisuus. 
Käyttötapaukset on määriteltävä ennen käyttöliittymän suunnittelua, jotta sovelluksesta saadaan vaatimusten mukainen
ja käyttäjäystävällinen. Käyttötapaukset auttavat hahmottamaan sovelluksessa tarvittavat käyttöliittymät, kun
käyttötapaukset ryhmitellään loogisiin kokonaisuuksiin, jotka muodostavat toisistaan erillisiä toimintaympäristöjä.

### Tilasiirtymät

* Asennusnäkymästä siirrytään automaattisesti rekisteröintinäkymään. 
* Rekisteröintinäkymästä pääsee pelinäkymään
* Pelinäkymästä pääsee asetus-, valikko- kommentti- tai uloskirjautumisnäkymään. 
* Asetusnäkymästä pääsee peli-, valikko-, kommentti- tai uloskirjautumisnäkymään. 
* Valikkonäkymästä pääsee peli-, asetus-, valikko- kommentti- tai uloskirjautumisnäkymään. 
* Uloskirjautumisnäkymästä pääsee takaisin sisäänkirjautumisnäkymään.

### Näkymien kuvailu

Peli alkaa asennusnäkymällä, kun käyttäjä on valinnut pelin asennettavaksi. 
Asennuksen jälkeen avautuu sisäänkirjautumisnäkymä, jossa uusi käyttäjä rekisteröityy
peliin ja vanha käyttäjä kirjautuu sisään. Käyttäjä voi myös tilata uuden salasanan, 
jos hän on unohtanut vanhan. 
Kirjautumisen jälkeen käyttäjälle avautuu pelinäkymä, jossa hän voi aloittaa pelin 
pelaamisen, siirtyä katselemaan omia tietojaan asetusnäkymästä, lähettää kommentin 
muille käyttäjille, joka tallentuu kommenttinäkymään tai kirjautua ulos. 
Päänäkymässä eli pelinäkymässä käyttäjä pelaa peliä. 
Näkymässä on kampuksen kartta ylhäältäpäin kuvattuna pohjapiirroksen omaisesti. 
Käyttäjän sijainti vilkkuu kartalla vihreänä pisteenä ja kohde, johon käyttäjä suunnistaa
vilkkuu keltaisena tähtenä. Pelinäkymässä näytetään myös mitä tasoa käyttäjä suorittaa. 
Käyttäjä etenee koulussa kartan mukaisesti sisätilapaikannusta hyödyntäen ja käyttäjän 
liikkeet näkyvät reaaliaikaisesti.

Asetusnäkymässä näkyvät käyttäjän tiedot sekä pelin etenemistilanne. 
Käyttäjä voi halutessaan vaihtaa käyttämäänsä nimimerkkiä ja kuvaa sekä valita 
haluamansa koulutusohjelman pelattavakseen.

Käyttäjä voi halutessaan vaihtaa koulutusohjelmaa valikkonäkymästä, 
jossa on listattuna kampuksen kaikki koulutusohjelmat, joiden lukujärjestyksien mukaista 
peliä käyttäjä voi valita pelaavansa. Kun käyttäjä on valinnut haluamansa koulutusohjelman, 
hän voi aloittaa pelin pelaamisen.

Kun käyttäjä haluaa lopettaa pelaamisen, kirjautuu hän ulos pelistä ja näytölle ilmestyy 
uloskirjoutumisnäkymä, jossa on lopputekstit sekä mahdollisuus kirjautua uudelleen peliin sisään.


### Näkymien sisältämä tieto käyttöliittymässä: 

* Rekisteröinti/sisäänkirjautumisnäkymä: pelin logo, syötetiedot: käyttäjän tunnus ja salasana, login/sign up/forgot password-nappulat

* Pelinäkymä: seuraava tehtävä, koulun kartta, suoritettava taso, back/asetus/uusi ikoulutusohjelma/kommentti/logout-nappulat

* Kommenttinäkymä: Käyttäjien kommentit listattuna, back/logout-nappulat

* Asetusnäkymä: logo, käyttäjätiedot, koulutusohjelma, pelin taso, aloita/uusi koulutusohjelma/kommentti/logout-nappulat

* Valikkonäkymä: koulutusohjelmat listattuna, back/aloita/asetus/kommentit/logout-nappulat

* Uloskirjautumisnäkymä: "loppu"-teksti, login-nappula


### Visuaalinen näkymä

https://suursoho.mybalsamiq.com/projects/copyofthesisapp/prototype/Aloitussivu?key=0643d8a87dcd5357d976d8b955731d9ee004064a
