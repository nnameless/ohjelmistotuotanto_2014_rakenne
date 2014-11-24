(1.) Selitä seuraavat käsitteet

(1.) Näkymä (view)=Se mitä katsoja pystyy kerralla näkemään, esim. katsojan edessä olevan puhelimen näyttö
(2.) Wireframe (page, schematic, screen blueprint)=Visuaalinen malli, jonka avulla voidaan kuvata esim. verkkosivuston "rautalanka" rakenne
(3.) Mockup=Visuaalinen hahmotelma siitä, miten esim. ohjelmisto tulee toimimaan
(4.) Prototyyppi=Rakenteilla olevan ohjelmiston ensimmäinen versio, jonka perusteella ohjelmiston toiminnallisuutta arvioidaan

(2.) Käyttöliittymän näkymät (User interface, views)

(1.) Miten käyttötapaukset ja käyttöliittymät voisi yhdistää toisiinsa vaatimusmäärittelydokumentaatiossa?
Käyttötapauksien yhdistämisellä käyttöliittymään voidaan kuvata pelin realistinen toiminnallisuus. Käyttötapaukset on määriteltävä ennen käyttöliittymän suunnittelua, jotta sovelluksesta saadaan vaatimusten mukainen ja käyttäjäystävällinen
(2.) Listaa järjestelmän käyttöliittymän olennaisimmat näkymät
Asennusnäkymä, rekisteröitymis/sisäänkirjautumisnäkymä, päänäkymä, valikkonäkymä, pelinäkymä (kartta), uloskirjoutumisnäkymä
(3.) Kuvaile näkymät sanallisesti: mitä näkymällä tehdään ja mitä siinä näkyy. Pyri määrittelemään tässä näkymät toiminnallisesta näkökulmasta, älä niinkään ajattele miltä ne näyttävät
Peli alkaa asennusnäkymällä, kun käyttäjä on valinnut pelin asennettavaksi. Asennuksen jälkeen avautuu sisäänkirjautumisnäkymä, jossa uusi käyttäjä rekisteröityy peliin ja vanha käyttäjä rekisteröityy sisään. Käyttäjä voi myös tilata uuden salasanan, jos hän on unohtanut sen. Rekisteröitymisen jälkeen käyttäjä voi katsella omia tietojaan asetusnäkymästä, jossa on käyttäjän tiedot ja pelin etenemistilanne. Käyttäjä voi halutessaan vaihtaa koulutusohjelmaa valikkonäkymästä, jossa on listattuna kampuksen kaikki koulutusohjelmat, joiden lukujärjestyksen mukaista peliä käyttäjä voi pelata. Päänäkymässä eli pelinäkymässä käyttäjä pelaa peliä. Näkymässä näkyy vasemmassa reunassa käyttäjän valitseman koulutusohjelman lukujärjestys, jossa vilkkuu punaisella seuraa suoritettava tehtävä. Oikealla näkyy kampuksen kartta ylhäältäpäin kuvattuna pohjapiirroksen omaisesti ja käyttäjän sijainti vilkkuu vihreänä pisteenä. Käyttäjä etenee koulussa kartan mukaisesti sisätilapaikannusta hyödyntäen ja käyttäjän liikkeet näkyvät reaaliaikaisesti. Kun käyttäjä haluaa lopettaa pelaamisen, kirjautuu hän ulos pelistä uloskirjoutumisnäkymässä. 
(4.) Määritä näkymien väliset siirtymät korkealla tasolla, mistä näkymästä pääsee minnekin? Millä tavoin visualisoisit tilasiirtymät?
Rekisteröintinäkymästä pääsee pelinäkymään, pelinäkymästä pääsee asetusnäkymään ja uloskirjautumisnäkymään, asetusnäkymästä pääsee valikkonäkymään ja uloskirjautumisnäkymään, uloskirjautumisnäkymästä pääsee takaisin sisäänkirjautumisnäkymään
(5.) Listaa jokaista näkymää kohti tieto siitä, millaista tietosisältöä tai data käyttöliittymässä näytetään.
Rekisteröinti/sisäänkirjautumisnäkymä: pelin logo, syötetiedot: käyttäjän tunnus ja salasana, login/sign up/forgot password
Asetusnäkymä: logo, käyttäjätiedot, koulutusohjelma, pelin taso, kommentit- nappula, uusi koulutusohjelma-nappula, logout-nappula
Pelinäkymä: seuraava tehtävä, koulun kartta, back-nappula, asetus-nappula, kommentit- nappula, uusi koulutusohjelma-nappula, logout-nappula
Valikkonäkymä: koulutusohjelmat listattuna, back-nappula, asetus-nappula, kommentit- nappula, logout-nappula
uloskirjautumisnäkymä: "Kiitos, että valitsit tämän pelin", kirjaudu sisään-nappula

(3.) Visualisoi listaamasi näkymät ja niihin liittyvät siirtymät (väh. 3 näkymää)
kuvat tulossa...