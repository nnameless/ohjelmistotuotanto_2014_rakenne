## Käyttötapaukset

- Määritä tänne järjestelmän loppukäyttäjät?

Loppukäyttäjät muodostavat ryhmän, joille projektin lopputuotos on suunattu. Järjestelmän eli ”InVisible”-pelin ensisijaisia loppukäyttäjiä ovat Metropolian Leppävaaran toimipisteen uudet opiskelijat, jotka ovat juuri aloittaneet opintonsa heille entuudestaan tuntemattomassa ympäristössä. Toissijaisia loppukäyttäjiä ovat Metropolian Leppävaaran toimipisteen vanhat opiskelijat sekä muu henkilökunta

- Käyttötapauskaavio, jossa järjestelmän keskeiset käyttötapaukset?

Käyttötapaus (use case) on käyttäjän ja järjestelmän välinen interaktio, joka kuvaa käyttäjälle näkyvän toiminnon. Järjestelmän eli ”InVisible”-pelin käyttötapaukset:

* rekisteröityminen
* sisäänkirjautuminen
* profiilin luonti
* käyttäjätietojen muokkaus
* koulutusohjelman ja vaikeustason valinta
* pelitehtävien suorittaminen
* tasolta toiselle eteneminen
* muiden käyttäjien suoritusten kommentoiminen
* pelaamisen lopettaminen
* uloskirjautuminen

- Kuvaile tärkeimmät käyttötapauksista käyttötapausskenaarioina mallipohjaan perustuen?
Käyttäjätarinasta käy ilmi kuka tekee, mitä tekee ja miksi.

-	mallipohja: määritä alkutila (initial state): käyttäjä etsii pelin internetistä ja lataa sovelluksen laitteelleen. normaali kulku (normal flow): Käyttäjä käynnistää pelin ja kirjautuu sisään sovellukseen. Käyttäjä aloittaa pelin pelaamisen, käyttäjä siirtyy vaiheittain pelissä vaikeustasolta toiselle. Jokaisella tasolla käyttäjä saa uuden tehtävän suunnistaa ennalta määrättyyn paikkaan ennalta määrätyssä ajassa, lopputila (end state):käyttäjä ei suoriudu tasosta ennalta määrätyssä ajassa, jolloin peli päättyy ja käyttäjän suoritus tallentuu hänen käyttäjänimensä alle. Käyttäjä kirjautuu ulos sovelluksesta.
-	kerro myös kuinka normaali kulku voi mennä pieleen: virhetilanne voi syntyä tietoliikennehäiriöstä, internetin toimimattomuudesta ja laiteviasta.

-)	Esim. tietoliikenne häiriöstä johtuen käyttäjä ei pääse kirjautumaan sisälle peliin.
-)	Esim. internet-yhteyden hitauden vuoksi pelin pelaaminen ei ole mielekästä
-)	Esim. kännykkä, jolla käyttäjä aikoo pelata peliä, ei käynnisty
-)	Esim. paikannuspalvelu ei ole käytössä

-	mahdolliset vaihtoehtoiset kulut (alternate flow): Pelissä olevia mahdollisia vaihtoehtoisia kulkuja normaalikululle ovat:

-)	käyttäjä on jo suorittanut pelin kaikki tasot, jolloin hän on jo pelannut pelin ”loppuun”
-)	käyttäjä ei pääse ensimmäistä tasoa läpi, jolloin hänen suorituksensa jumiutuu siihen

-)	käyttäjä voi samanaikaisesti olla laitteellaan kirjautuneena muihinkin järjestelmiin ja vastaanottaa viestejä niistä, esim. sähköposti ja sosiaaliset mediat

Käyttötapauskaavio liitteenä: https://github.com/nnameless/ohjelmistotuotanto_2014_rakenne/blob/master/invisible_kaavio.pdf
