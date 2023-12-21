# Raportointi

## Ajan käyttö

Ajan käyttö yhteensä noin 43 tuntia.

### Viikko 47
Työtunnit: noin 4h.

Työtehtävät:

* Projektin pystytys. 
* Bootstrap otettu käyttöön ja tehty grid layout ja navigaatio palkki.

### Viikko 48
Työtunnit: noin 8h.

Työtehtävät:

* Sivuston rungon sommittelu ja login formin implementointi. 
* Oman SVG logon ja login taustakuvan lisäys. 
* Valmistautuminen puoliväli palautteeseen.

### Viikko 49
Työtunnit: noin 7-9h.

Työtehtävät:

* SASS otettu käyttöön. 
* Tekstin ja kuvien lisäys. Tekstin luomiseen käytin apuna ChatGPT:tä.
* Nappuloiden lisäys. 
* Eniten käytetyt tyylit muutettu variableiksi ja mixineiksi.
* Contact Us form lisätty
* Footer tehty ja Font Awesome iconit otettu käyttöön
* Media screenit lisätty

### Viikko 50
Työtunnit: noin 23h

Työtehtävät:
* Omat animaatiot ja värit nappuloihin käyttäen mixiniä.
* Margineita ja skaalautuvuutta säädetty kaikilla sivuilla.
* Bootstrap modalit lisätty index- ja Contact sivuille.
* Sisältöä lisätty.
* joidenkin containereiden järjestys on muutettu siten että ne näytetään eri järjestyksessä isoilla ja pienillä näytöillä. Esim header.
* Paljon hienosäätöä.

## Käytetyt teknologiat

### CSS Kirjastot:
Käytin Bootstrapia grid layoutin, navigaatio palkin, formien, containereiden, modaleiden ja nappuloiotten luomiseen.

Bootstrapin käyttöä opeteltiin aikaisemmin kurssilla, joten Bootstrapin valinta css kirjastoksi oli minulle luontaisin. Bootstrapin avulla responsiivisen layoutin, navigaatiopalkin ja formien luominen oli helppoa ja säästi todella paljon aikaa verrattuna siihen jos olisin itse tehnyt grid layoutin käyttäen felx boxeja. Bootstrapin avulla sain myös käännettyä kuvien ja tekstikenttien järjestystä mobiili näkymässä.

### CSS Preprocessors:
Käytin SASS:ia CSS tiedostojen modulointiin. Yleisimmin käytetyistä tyyleistä kuten väreistä ja varjoista tein variableja, jonka jälkeen tein Mixin tiedoston johon tallensin muita usein käytettyjä elementtejä: border-radius, box-shadow, block-quote sekä nappulat ja niiden animaatiot. Tämän jälkeen niitä oli helppo kutsua tyylitiedostoissa ja html dokumenteissa.
Lisäksi käytin SASS:ia selkeyttämään tyylitiedostojen sisältöä.

### CSS advanced:
CSS advanced teknologioita on yleisesti käytetty kaikissa tyylitiedostoissa. Olen käyttänyt SASS:ia, flex-boxia, media screeneja, animaatioita, varjoja, variableja ym.

### Typografia:
Otin käyttöön "Poppins" fontin googlen fonteista, ja käytin sitä yleisesti kaikilla sivuilla. Lisäksi olen käyttänyt vahvistettua fonttia index sivun modaleissa, ja italic tyyliä blockquote elementissä. Olen käyttänyt tekstissä mustaa sekä punaista väriä sivuston selkeyttämiseksi, ja olen käyttänyt rivin vaihtoja lukemisen helpottamiseksi.

### SVG kuvat:
Tein oman SVG logon jota käytän navigointi palkissa sekä selaimen välilehti ikonina. Tein myös SVG taustakuvan login sivulle.
Tarkoitus oli alunperin käyttää samaa taustakuvaa myös Contact Us sivulla, mutta taustakuva ja footer eivät sopineet yhteen, joten jätin taustakuvan siltä sivulta pois.

* Muut sivustolla käytetyt kuvat ovat joko ilmaisia stock kuvia, tai FontAwesome ikoneita.

### Animaatiot:
Käytin Bootstrapin nappuloita, mutta animoin ne kuitenkin itse. Kun hiiren vie nappulan päälle, nappulan väri tummuu, ja kun nappulaa klikkaa, se tummuu vielä enemmän. Lisäksi värien muuttumiseen on lisätty transitio jotta väri ei vaihdu samantien.
Navigointipalkin linkkeihin lisäsin myös vastaavan hehku animaation kun hiiren vie linkin päälle.
Muut animaatiot ovat Bootstrapin omia animaatioita, enkä kokenut tarpeelliseksi lähteä niitä muuttamaan sillä ne näyttävät mielestäni hyviltä sellaisinaan.

### Semanttinen rakenne.
Käytin semanttisia rakenteita kuten header, footer, nav ja section. Näillä käärin eri osia html dokumentista jotta selaimet saavat paremman käsityksen sivustoni sisällöstä. Koodin lukeminen on myös selkeämpää semanttisella rakenteella.

### FontAwesome
Käytin FontAwesome ikoneja sivuston footerissa (some logot ja pienet ikonit yhteystietojen edessä) sekä Contact Us sivun modalissa (checkmark). Nämä tekevät sivustosta näyttävämmän näköisen, sekä parantavat luettavuutta.

## Yleiset mietteet. Mitä opin?
Sivuston kasaamiseen kului lopulta enemmän aikaa kuin oletin. Sain pystytettyä sivuston rakenteen nopeasti bootstrapin avulla, mutta suurin osa työhön käytetystä ajasta kului kuitenkin margineiden ja skaalautuvuuden hienosäätöön, sekä uusien tekniikoiden opettelemiseen (kuten bootstrapin eri toiminnot ja sen vakio tyylien muuttaminen, sekä taustakuvan lisääminen).

Tätä projektia tehdessä vahvistin kurssin aikana oppimiani taitoja, ja palautin mieleen aikaisemmilla kursseilla oppimiani taitoja ja tekniikoita.

Tärkeimmät asiat jotka opin ovat todennäköisesti SASS:n käyttö tyylitiedostojen moduloimiseen ja Bootstrapin käytön oppiminen ja soveltaminen. Kurssin SASS viikkotehtävä oli melko lyhyt, enkä silloin vielä täysin ymmärtänyt SASS:n käyttötarkoitusta. Mutta tämän projektin aikana huomasin kuinka paljon tyylitiedostoja voi putsata tekemällä usein käytetyistä tyyleistä variableja ja mixineitä. Tyylitiedostojen rivi määrä taisi vähentyä ainakin neljännesosalla SASS:n implementoinnin jälkeen.

CSS kirjastoja viikkotehtävissä käytettiin vähän enemmän, mutta tämän projektin aikana pääsin syventymään Bootstrapiin vielä enemmän lisäämällä sivustolleni mm. modaleita ja skaalautuvia kuvia.

## Itsearviointi

### Missä onnistuin:
* Grid layoutin luominen bootstrapilla sujui hyvin.

* Sivusto tuntuu skaalautuvan hyvin eri selaimissa. Testasin skaalautuvuuden Chromessa, Edgessä, Firefoxissa sekä Safarissa (tabletilla). Sivusto näyttää myös hyvältä omalla puhelimellani, joten olen erittäin tyytyväinen siihen kuinka sivusto skaalautuu pienemmille laitteille.

* Kuvien skaalautumisessa minulla oli alkuun ongelmia. Kuvien suhde ei pysynyt samana kaikilla näytön leveyksilä mutta onnistuin kuitenkin ratkaisemaan tämän ongelman Bootstrapin row- ja column asetuksia säätämällä ja muokkaamalla omia CSS/SASS tyylejä.

* Sivusto on minusta selkeä ja hyvin luettavissa. Tyylit ovat johdonmukaiset kaikkien sivujen ja elementtien välillä. Sivusto on myös minusta visuaalisesti näyttävä.

* Sivuston responsiivisuus on minuista myös hyvällä tasolla. Nappuloissa on animaatiot, aktivisella sivulla on navigaatio palkissa pieni hehku, ja contact us sivun "send" nappula avaa modalin joka kertoo käyttäjälle että viesti on vastaanotettu.

* Onnistuin myös lopulta muuttamaan login formin checkboxin värin punaiseksi. Puoliväli palautteessa tämä oli vielä sininen, joka ilmeisesti oli joko bootstrapin tai selaimen vakio väri. Extensiivisen googlailun ja testailun jälkeen onnistuin kuitenkin tuon värin lopulta vaihtamaan.


### Mihin jäi parannettavaa:
En ole täysin tyytyväinen siihen kuinka etusivun header osio skaalautuu näytön leveyden kasvaessa. Tarkoitus oli pitää headerin teksti samassa linjassa headerin kuvan kanssa näytön koosta riippumatta, mutta en tässä täysin onnistunut. Koitin korjata tätä ongelmaa Bootstrapin avulla sekä css tyylien avulla, mutta en millään kombinaatiolla saanut tätä toimimaan kunnolla. Lisäsin tätä varten lopulta uuden media screenin helpottamaan tilannetta, mutta koska itse tein tämän projetin 14 tuuman läppärillä, en oikein osaa sanoa miltä tuo header osio näyttää isommilla näytöillä.
Samasta syystä en ole täysin varma kuinka hyvin login form on keskitettynä login sivulla isommilla näytöillä. (mainitsit tästä puoliväli palautteessa). Omalla keskikokoisella näytöllä skaalautuvuus ja sommittelu näyttää kuitenkin hyvältä.

Koitin myös lisätä tooltipin kun hiiren vie navigaatiopalkissa "MySphere" linkin päälle. Tooltip olisi kertonut että "My Sphere" sivu aktivoituu kun sopimus on tehty ja käyttäjä on kirjautunut sisään. En kuitenkaan saanut tooltipiä näkymään.

### Arvosana:

Käytin sivustoa tehdessä tekniikoita kaikista kurssin aihealueista, joten olettaisin että tämä työ on vitosen arvoinen tai ainakin erittäin lähellä sitä. Olen itse erittäin tyytyväinen lopputulokseen ja se on mielestäni selkeä parannus vastaavaan harjoitustehtävääni web- tekniikat kurssilta, josta myös sain arvosanaksi vitosen.

Arvosanani varmaankin riippuu eniten siitä kuinka iso ongelma headerin skaalautuvuus on, ja käytinkö tarpeeksi SASS ominaisuuksia. Mielestäni käytin Variableja ja mixineitä kaikkiin niihin tarkoituksiin joissa niiden käytöstä oli hyötyä.

Itse antaisin siis tälle työlle arvosanan: 5
