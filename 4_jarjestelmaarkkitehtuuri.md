##  Järjestelmäarkkitehtuuri

* Pyri kuvailemaan tässä luvussa järjestelmäarkkitehtuuri yleisellä tasolla
* Mitä komponentteja järjestelmään tarvitaan jotta se pystyy palvelemaan määritettyjä käyttötapauksia?

- käyttäjien yksilöinti
	- tietokanta käyttäjien yksilöintiin (autentikointi ja sisäänkirjautuminen)
- sisätilapaikannuskomponentti
	- syöte: puhelimen keräämät wlan-signaalivoimakkuudet
	- tulos: sijaintitiedot (huoneen nimi)
- tietokanta: käyttäjien tiedot + pelisuorituksen tiedot
- chat (käyttäjät voivat kommentoida pelin kulkua keskenään)
- palvelinyhteys (muiden käyttäjien sijaintien jako)
- lukujärjestystiedot (API)
- huonetiedot
- navigointi kartan (koulun pohjapiirustuksen) perusteella