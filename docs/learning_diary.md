Oppimispäiväkirja – Module 3 Part 1/2

Tässä tehtävässä tavoitteena oli julkaista staattinen HTML-tiedosto GitHub Pagesin avulla.
Tarkoituksena oli saada aiemmin tehty Google Teachable Machineen liittyvä käytännön toteutus, tai ainakin toimiva index.html-tiedosto, näkyviin julkisena verkkosivuna selaimessa avattavan linkin kautta.

Tehtävän alussa jouduin ensin hahmottamaan paremmin, mikä ero on tavallisella GitHub-repositoriolla, GitHub Enterprisella ja GitHub Pagesilla.
Aluksi katsoin väärää kohtaa ja päädyin enterprise-vaihtoehtoihin, mutta tehtävän aikana selvisi, että tähän tarvittiin vain tavallinen julkinen GitHub-repository. 
Tämä oli hyvä oppi, koska huomasin, että GitHubissa on paljon eri palveluja, mutta tämän tehtävän kannalta yksinkertaisin ratkaisu oli oikea.

Loin repositorion kurssitehtäviä varten ja aloin rakentaa sille selkeää kansiorakennetta moduuleittain. 
Sen jälkeen siirsin staattisen index.html-tiedoston oikeaan paikkaan. Tärkeä oppi tässä oli se, että GitHub Pages ei julkaise sisältöä mistä tahansa alikansiosta silloin, kun käytetään branch-pohjaista julkaisua. Tiedoston piti olla joko repositorion juuressa tai docs-kansiossa. Tämän vuoksi siirsin index.html-tiedoston repositorion juureen, jotta GitHub Pages pystyi käyttämään sitä.

Mallitiedostojen täytyy olla juuri siinä kansiorakenteessa, johon koodissa viitataan.
Omassa tapauksessani HTML-tiedosto odotti Teachable Machine -tiedostoja tm-kansiosta. Siksi model.json, metadata.json ja weights.bin piti sijoittaa oikein.
Julkaisu ei tarkoita vain yhden tiedoston siirtämistä verkkoon, vaan myös sitä, että kaikki viitatut tiedostot ovat oikeissa paikoissa.

Tehtävän aikana tuli myös ongelmia GitHub Pagesin kanssa. Yhdessä vaiheessa sivusto lakkasi toimimasta muutosten jälkeen, ja jouduin tarkistamaan GitHub Pagesin asetukset uudelleen. Tästä opin, että julkaisulähteen täytyy olla oikein määritelty. Toimiva asetus oli main-branch ja root-kansio. Huomasin myös, että repositorion näkyvyys vaikuttaa julkaisuun, joten repositorion piti olla public, jotta sivu toimi odotetulla tavalla.

Kun rakenne ja asetukset oli korjattu, sivusto alkoi toimia. Tämä oli hyödyllistä, koska pääsin näkemään koko julkaisuputken käytännössä alusta loppuun: repositorion luominen, tiedostojen sijoittelu, GitHub Pagesin käyttöönotto ja lopullisen julkisen linkin testaaminen.

Opin, miten GitHub Pages toimii, miten tärkeä kansiorakenne on ja miten pienetkin virheet tiedostopolussa tai asetuksissa voivat estää julkaisun toiminnan.

Kokonaisuutena tehtävä oli hyvä johdatus web-sivun julkaisemiseen. Oli hyödyllistä nähdä, miten staattinen sivu voidaan muuttaa oikeasti toimivaksi verkkolinkiksi. 