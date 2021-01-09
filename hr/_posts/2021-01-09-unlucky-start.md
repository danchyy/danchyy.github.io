---
layout: post
title: Naj(ne)sretnije ekipe kada su u pitanju širom otvorene trice
lang: hr
lang-ref: unlucky-start-20-21
url: unlucky-start-20-21
twitter_img: /assets/unlucky_start/wide_open_table.jpg
---

![](/assets/unlucky_start/wide_open_table.png)

Neke ekipe su započele iznenađujući dobre, a neke iznenađujući loš pa ako bacite pogled na ovu tablicu pa zatim na pravu tablicu u NBA ligi vidjet ćete da ekipe koje su ovdje na vrhu imaju vrlo loš score (Washington 2-7, Denver 3-5, Minnesota 2-6).

Isto tako vrijedi i za ekipe na dnu tablice, Hawksi imaju 4-4, a Knicksi neočekivanih 5-4. Pročitajte u nastavku o čemu je riječ u ovoj tablici.

<!--more-->


## Širom otvoreni šutevi

U ovoj tablici je riječ o širom otvorenim šutevima. To su šutevi kada je najbliži obrambeni igrač udaljen više od 1.8 metara (odnosno 6 stopa - Feet). Kod takvih šuteva možemo reći da obrana više i nema nekog utjecaja jer kada je igrač udaljen 1.8 metara (minimalno) šuter ima vrlo jednostavnu situaciju, čak i uz dignutu ruku, odnosno "contested" šut. Na kraju krajeva, možete se i sami uvjeriti u to, pitajte nekoga da stane otprilike toliko ispred vas i šutirajte, nećete imati problema.

## Definicija metrika/statistika

Prvo ću objasniti ALLOWED WO FG3% stupac, pošto ga je lakše za objasniti. On označava **FG3% na otvorenim tricama protivničkih timova protiv ciljane ekipe**. Dakle ako gledamo Washington Wizardse ovdje, oni svojim protivnicima po utakmici "dozvoljavaju" 49.3% na širom otvorenim šutevima za 3 poena.

Stupac WO FG3% BY OPP TEAMS predstavlja nešto drugo, i teže za objasniti. Dakle dosadašnji protivnici Wizardsa su bili ORL (x2), MIN, CHI (x2), BOS, PHI (x2), BKN. Dakle uzet ćemo sve te protivnike i njihove pokušaje i zabijene širom otvorene trice u dosadašnjoj sezoni (brojke predstavljaju broj šuteva/zabijenih po utakmici):


* ORL -> FG3M: 5.22, FG3A: 14.89
* MIN -> FG3M: 5.75, FG3A: 15.13
* CHI -> FG3M: 7.11, FG3A: 18.22
* PHI -> FG3M: 7.78, FG3A: 18.89
* BOS -> FG3M: 5.2, FG3A: 13.0
* BKN -> FG3M: 6.11, FG3A: 15.78


I sada kada zbrojimo ove brojeve dobijemo FG3M: 37.17 i FG3A: 95.91, a uspješnost tih šuteva je: `37.17 / 95.91 = 0.3876`, odnosno `38.76%`. Dakle ova metrika predstavlja **FG3% na otvorenim tricama protivničkih timova ciljane ekipe u svim utakmicama**.

## Alternativa tablici

Alternativa ovoj tablici može biti *Scatter Plot*.

![](/assets/unlucky_start/wide_open_3pt_luck_hr.png)

Kosa crta predstavlja idealan slučaj, odnosno kada su vrijednosti na x-osi i y-osi jednake. Možete vidjeti iz ovoga, ali i tablice gore da kod Memphisa sreća nema nikakav utjecaj, a Detroit i Boston su jako blizu tome.

S druge strane, ekstremi su već spomenuti Hawksi i Knicksi. Oni "dozvoljavaju" daleko najmanji FG3% na širom otvorenim tricama iako u pravilu njihovi protivnici šutiraju sasvim dobro na takvim šutevima. Možda je to naznaka polaganog pada Knicksa i Hawksa...

S druge strane ekstrema su Wizardsi. Možda je Beal u krivu i mogli bi [čuvati "parkirani automobil"](https://bleacherreport.com/articles/2926076-bradley-beal-says-wizards-cant-guard-a-parked-car-after-loss-to-celtics), ali jednostavno nemaju sreće te čini se da svaki protivnički igrač poprimi oblik Stepha Curryja kada igra protiv Wizardsa.  

## Smirivanje brojki

Za kraj evo još jednog grafa koji dočarava situaciju uspješnosti protivničkih širom otvorenih šuteva kroz sezone.

![](/assets/unlucky_start/mean_stddev_through_years_hr.png).

Prosjek na razini lige ne odskače previše, još uvijek je on oko 39% (iako je bliže 40%), no standardna devijacija je ogromna. Ukoliko niste upoznati s tim pojmom, standardna devijacija je statistički pojam koji označava mjeru raspršenosti podataka. Interpretira se kao prosječno odstupanje od prosjeka i to u apsolutnom iznosu.

Ali to je normalna situacija, jer takva devijacija se javljala svake sezone na početku.

| Sezona | Početna devijacija | Devijacija cijele sezone |
| ------ | ------------------ | ------------------------ |
| 2013-14 | 0.05 | 0.02 |
| 2014-15 | 0.04 | 0.02 |
| 2015-16 | 0.04 | 0.02 |
| 2016-17 | 0.04 | 0.02 |
| 2017-18 | 0.03 | 0.01 |
| 2018-19 | 0.04 | 0.02 |
| 2019-20 | 0.04 | 0.02 |
| 2020-21 | 0.04 | ? |
