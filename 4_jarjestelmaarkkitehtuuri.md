##  Järjestelmäarkkitehtuuri

* Pyri kuvailemaan tässä luvussa järjestelmäarkkitehtuuri yleisellä tasolla

järjestelmäarkkitehtuurin tarkoituksena on kuvata järjestelmä kokonaisvaltaisesti. Se siältää järjestelmän osat, niiden sijoittumisen järjestelmässä sekä osien toteutus- ja tiedonvälitysperiaatteet.
InVisible-pelin järjestelmäarkkitehtuurin erilaisia osia ovat itse pelisovellus, tietokannat, palvelin ja käyttöliittymä.

* Mitä komponentteja järjestelmään tarvitaan jotta se pystyy palvelemaan määritettyjä käyttötapauksia?

- käyttäjien yksilöinti
	- tietokanta käyttäjien yksilöintiin (autentikointi ja sisäänkirjautuminen)
	
- sisätilapaikannuskomponentti
	- navigointi kartan (koulun pohjapiirustuksen) perusteella
	- syöte: puhelimen keräämät wlan-signaalivoimakkuudet
	- tulos: sijaintitiedot (piste interaktiivisessa kartassa)
	
- sijaintitietojen saatavuuskomponentti
	- palvelinyhteys, jolla mahdollistetaan muiden käyttäjien sijaintietojen jako
	
- pelitiedot
	- tietokanta lukujärjestystietojen ja huonetietojen hallinnointiin
	
- tiedonhallinta
	- tietokanta käyttäjien tietojen + pelisuorituksen tietojen hallinnointiin

- kommunikointi
	- chat, jossa käyttäjät voivat kommentoida pelin kulkua keskenään