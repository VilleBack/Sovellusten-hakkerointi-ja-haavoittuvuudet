# h2 Break & unbreak
## x) Lue/katso/kuuntele ja tiivistä
### OWASP: OWASP Top 10: A01 Broken Access Control
* Pääsynhallinta määrittää mitkä oikeudet kenelläkin on. Jos tässä epäonnistutaan, seurauksena voi olla tiedon vuotaminen, muuttaminen, poistaminen tai toiminta johon käyttäjällä ei pitäisi olla oikeuksia.
* Yleisimpiä pääsynhallinta haavoittuvuuksia ovat:
  * Pienimmän oikeuden periaatteen noudattamatta jättäminen.
  *  Pääsynvalvonnan kiertäminen esimerkiksi URL-osoitetta muokkaamalla.
  *  Toisen käyttäjätilin tarkastelu tai muokkaus.
  *  API-suojauksen puute POST, PUT ja DELETE pyynnöissä.
  *  Oikeuksien korottaminen.
  *  Virheelliset CORS-asetukset.
  *  Tavallisena käyttäjänä pääsy admin sivuille pakotetun selaamisen avulla.
* Ennaltaehkäisy:
  * Toteuta pääsynhallinta palvelinpuolella.
  * "deny by default" periaate. Oletusarvona pääsy estetään.
  * Käytä samoja pääsynhallintamekanismeja kaikilla osa-alueilla.
  * Käyttäjillä oikeudet vain omiin tietoihinsa.
  * Poista käytöstä hakemistolistaukset.
  * 
