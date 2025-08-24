# h1 standardit
## a) Termejä
* 3.2 attack

Attack, eli hyökkäys tarkoittaa tapahtumaa missä hyökkääjä koittaa tuhota, varastaa, estää pääsyn tai väärinkäyttää jonkun toisen tietoja.
* 3.31 information security incident

Yksi tai useampi ei toivottu tietoturvatapahtuma, joka vaarantaa yrityksen toiminnan ja tietojen turvallisuuden. 
* 3.56 requirement

Vaatimus, joka on todettu, yleisesti oletettu tai pakollinen.
* 3.58 review

Arvioinnilla selvitetään onko jokin asia tehtävään soveltuva, jotta asetetut tavoitteet voidaan saavuttaa. 

* 3.77 vulnerability

Jonkin asian heikkous, jota voidaan hyväksikäyttää

* Lähde: ISO/IEC 270000-2020

## b) ISO/IEC 27034
Standardin tavoitteena on avustaa organisaatioita integroimaan tietoturva osaksi sovellusten elinkaarta tarjoamalla:
* käsitteitä, periaatteita, viitekehyksiä ja prosesseja.
* Menetelmät tietoturvavaatimusten määrittämiseen, riskien arviointiin ja halutun luottamustason asettamiseen.
* Ohjeet hyväksymiskriteerien määrittämiseen, ulkoistetuissa sovellusprojekteissa.
* Prosesseja joilla osoittaa sovellusten turvallinen käyttö määritellyssä ympäristössä.
* Tukea ISO/IEC 27001 -standardille ja apua tietoturvassa riskienhallinnan kautta.
* Viitekehyksen ISO/IEC 27002 ja muiden standardien mukaiseen tietoturvan toteuttamiseen.

## c) Laatulöpinät 30: Tietoturvallisuus ohjelmistokehityksessä
1. Mikään ohjelmisto ei ole täysin tietoturvallinen.
* Olen täysin samaa mieltä. Ei ikinä kannata ajatella, että ohjelma olisi täysin tietoturvallinen.
2. Hallinnollinen tietoturva on teknisen tietoturvan onnistumisen edellytys.
* Olen samaa mieltä. Hallinnollisen titetoturvan avulla tunnistetaan teknisen tietoturvan tavoitteet.
3. Automaatiotestaus on ohjelmiston tietoturvan kannalta erittäin tärkeää.
* Olen osittain samaa mieltä. Automaatiotestaus nopeuttaa paljon. Täytyy vain tiedostaa mitä kaikkea se testaa ja täytyykö tehdä lisätestejä tai päivittää testiohjelmaa.
4. Ohjelmistoa suunniteltaessa voidaan tehdä paljonkin auttamaan käyttäjää toimimaan tietoturvallisesti. Usein nämä toimenpiteet kuitenkin vaikuttavat negatiivisesti käytettävyyteen.
* Osittain samaa mieltä. Varmasti nämä asiat pystyttäisiin tuomaan käyttäjäystävällisemmin ohjelmistoon, jotta kokemus pysyisi sulavana.
5. Ohjelmiston tietoturvallisuuden suunnitteluun vaikuttaa paljolti se, kuinka arkaluonteisia tietoja ohjelmistolla on tarkoitus käsitellä.
* Olen eri mieltä. Perus tietoturva täytyisi olla aina normi. Vaikka jollain ohjelmistolla ei käsitellä arkaluonteista tietoa, mutta se ei ole puutteellisen tietoturvan takia saatavilla asiakkaille niin se voi tulla hyvinkin kalliiksi.
6. Ohjelmistokehittäjät näkevät omat ohjelmistonsa aina merkittävästi riskialttiimpina, kuin muiden tekemät ohjelmistot.
* Täysin samaa mieltä. Kaikki näkevät omat tuotokset hyvin kriittisessä valossa ja niitä tulee tarkasteltua "suurennuslasin" kanssa. Ainakin itse teen näin, oli kyse sitten koulutyöstä tai musiikista. 
## d) riskienhallintasuunnitelma
* Ympäristö

Kurssia varten asennan omalle tietokoneelleni VMware virtualisointiohjelman jossa käytän Kali Linux käyttöjärjestelmää.

Kurssin harjoitukset tulen siis toteuttamaan virtuaalikoneella enkä omalla windows koneellani.

* Suojaaminen ulkopuolisilta

Käytän virtuaalikoneessa NAT-tilaa mikä rajoittaa yhteyden ottamista koneeseen ulkopuolelta.

Pidän virtuaalikoneen ohjelmistot päivitettynä.

En avaa tarpeettomia portteja.

* Haittaohjelmien leviämisen estäminen

Käytän virtuaalikonetta vain kurssin harjoituksiin.

Isäntäkoneen ja virtuaalikoneen välillä ei jaeta kansioita.

Käytän VMwaren "snapshot" toimintoa, jolla pystyn palauttamaan virtuaalikoneen puhtaaseen tilaan.

Pidän oman koneeni virustorjunnan ajan tasalla, jotta se huomaisi mahdollisimman nopeasti jos leviäminen tapahtuisi.










