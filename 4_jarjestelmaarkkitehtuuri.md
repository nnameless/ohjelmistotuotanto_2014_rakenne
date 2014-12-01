##  Järjestelmäarkkitehtuuri

* Pyri kuvailemaan tässä luvussa järjestelmäarkkitehtuuri yleisellä tasolla

järjestelmäarkkitehtuurin tarkoituksena on kuvata järjestelmä kokonaisvaltaisesti. Se siältää järjestelmän osat, niiden sijoittumisen järjestelmässä sekä osien toteutus- ja tiedonvälitysperiaatteet.
InVisible-pelin järjestelmäarkkitehtuurin erilaisia osia ovat itse pelisovellus, tietokannat, palvelin ja käyttöliittymä.

* Mitä komponentteja järjestelmään tarvitaan jotta se pystyy palvelemaan määritettyjä käyttötapauksia?

- autentikointi
	- tietokanta käyttäjien autentikointiin ja sisäänkirjautumiseen
	
- sisätilapaikannus
	- navigointi kartan (koulun pohjapiirustuksen) perusteella
	- syöte: puhelimen keräämät wlan-signaalivoimakkuudet
	- tulos: sijaintitiedot (piste interaktiivisessa kartassa)
	
- sijaintitiedon jako
	- palvelinyhteys, jolla mahdollistetaan muiden käyttäjien sijaintietojen jako
	
- lukujärjestys- ja tilatietokanta 
	- tietokanta lukujärjestystietojen ja huonetietojen hallinnointiin
	
- käyttäjätietokanta
	- tietokanta käyttäjien tietojen + pelisuorituksen tietojen hallinnointiin

- Chat
	- pikaviestipalvelu, jossa käyttäjät voivat kommentoida pelin kulkua keskenään