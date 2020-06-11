---
layout: post
title: Analiza After Timeout Akcija
lang: hr
lang-ref: ato-analysis
url: ato-analysis
---

![](/assets/ato_analysis/drawing_play.png)

Često čujete kako se treneri hvale zbog njihove sposobnosti crtanja i izvođenja After Timeout (ATO) akcija pa ću zbog toga provjeriti postoji li povezanost između uspješne realizacije ATO akcija i postotka pobjede tima. Razmotrit ću također tko su neki od najuspješnijih igrača u izvođenju istih tih akcija.

<!--more-->

## Podaci

Podaci se prikupljaju putem NBA-ovih Play-by-Play akcija. Pronašao sam sve timeoutove u ovogodišnjoj sezoni, kojih je bilo ukupno 10905. Cilj nakon toga bio je pronaći akciju nakon toga. Evo svih "ATO akcija" koje su se dogodile (s time da sam filtrirao sam sve zamjene nakon timeoutova):

* Promašeni šutovi: 3927
* Zabijeni šutovi: 3030
* Faul 1463
* Izgubljene lopte 1106
* Slobodna bacanja 1095
* Jump Ball 100
* Violation (Delay of game, itd...) 71
* Timeout 53
* Kraj utakmice 31
* Napadački prekršaj 29

Kao što vidite, ovo su prilično ne-optimalni podaci, ovdje možemo filtrirati još akcija koje nisu korisne. Pa sam zbog toga izbacio slobodna bacanja (jer se TO zvao nakon prekršaja/između bacanja), Timeoutove, Jump Balls (vrijedi isto kao za FT-e), "Violations" (nije utjecalo na igru) i Ofanzivni prekršaj sam klasificirao kao izgubljenu loptu (kakav jest). Uz to ulonio sam akcije koje predstavljaju "Kraj Utakmice" jer ne mogu zaista ništa zaključiti iz toga. Rezultat svega ovoga je:

* Promašeni šutovi: 4047
* Zabijeni šutovi: 3121
* Faul: 1307
* Izgubljene lopte: 1136

## Uspjeh tima

Prvo što sam želio pogledati je koliko su ekipe uspješne u tim akcijama. Da bih to učinio, pogledao sam promašene/zabijene šuteve i izgubljene lopte kako bih odredio uspjeh. Prikaz tog uspjeha prikazao sam bar chartom.

![](/assets/ato_analysis/after_timeout_1.png)

Na moje iznenađenje, Orlando Magic je akipa koje je do sada bila najuspješnija, a slijede ga Wizardsi i Thunder. Knicksi na četvrtom mjestu također su iznenađenje.

A Pelikani koji su dominatno posljednji su iznenađjuće daleko od ostalih ekipa.

No, svi su drugi brojevi relativno bliski i nitko stvarno ne iskače.

### Jesu li ekipe koje su uspješne u ATO akcijama generalno bolje (imaju bolji Win%)?

Ne.

Između toga postoji nulta korelacija, stvarno, vrijednost r^2 bila je gotovo nula, što znači da nema ni pozitivne ni negativne korelacije.

![](/assets/ato_analysis/ato_connection.png)

Drugi graf prikazuje uspjeh ATO akcija i Win Percentage. Uspješnost ATO akcija definirao sam kao `(zabijeni šutevi) / (zabijeni šutevi + promašeni šutevi + izgubljene lopte)`.

Do sada ste vjerojatno shvatili da sam u potpunosti izostavio faulove (osim napadačkih prekršaja, koje sam klasificirao kao TO), razlog za to je da je  zaključivanje je li akcija u kojoj je bio faul bila uspješna ili ne jako komplicirano, a nisam baš sitgao zaroniti toliko duboko u podatke.

# Pogled na najuspješnije igrače

Igrači koje generalno smatramo zvijezdama i vođama momčadi pojavili su se kao igrači koji uzimaju najviše šuteva nakon Timeouta.

To možete vidjeti na grafu koji prikazuje neke od igrača s najviše šuteva.

![](/assets/ato_analysis/most_shots_ato.png)

Ovdje su me najviše iznenadili Julius Randle, Marcus Morris i Joe Harris. Prva dva su igrala (ili barem igrala većinu sezone) u Knicksima, pa pretpostavljam da su samo igrali Iso/Drive. Joe Harris je s druge strane jedan od najboljih šutera za 3 poena i više se oslanjao na kreaciju drugih.

Dončić, Dinwiddie i Randle (opet spomenut) iskaču kao najučinkovitiji (najveći FG%) igrači u ovim akcijama. Jokić i Beal su temelj ekipe i to pokazuju time da imaju najviše šuteva u ATO akcijama.

### Assisted vs Unassisted shots

![](/assets/ato_analysis/unassisted_assisted_ato.png)

I zadnji graf nam objašnjava zašto su Randle i Morris imali oba toliko šuteva. Sami su stvorili gotovo sve zabijene koševe (možemo pretpostaviti da su i sami kreirali promašene šuteve) i to potvrđuje teoriju Iso akcija.

Na suprotnoj strani nalaze se Joe Harris i Bryn Forbes. Nalaze se u gornjem lijevom kutu, u "Zemlji centara", a obojica su specijalci u šutevima za 3 poena i ova analiza pokazuje da su prilično i u akcijama nakon timeouta. Ima nekoliko zgodnih akcija za Harrisa koje bih mogao izdvojiti u poseban post.

[Dupli blok](https://videos.nba.com/nba/pbp/media/2020/01/14/0021900599/499/38f6f5d8-4ecf-fabc-7fa6-f2d589aa3e60_1280x720.mp4) za njega, [blok centra i blok/cut beka koji stoji uz Harris](https://videos.nba.com/nba/pbp/media/2019/10/30/0021900059/252/ec71bc32-d34a-38b4-3fa2-2e87c6d4024e_1280x720.mp4) što mu dozvoljava slobodan šut za tri poena.

Luka Dončić me se također jako dojmio, ali njegove ATO akcije su suprotne Harrisu. Većina njegovih šutova nije asistirano, on sam kreira svoj šut tako da ili prodire prema košu (drive) ili se digne na skok šut koristeći (sad već signature) step back jump shot.


## Zaključak

Ovo je bio samo kratki pregled After Timeout Playsa, moglo bi se još puno stvari zaključiti iz ovih akcija, ali nažalost podaci su malo limitirani te ne daju punu sliku. Ovo su samo neke od kul stvari koje su mi pale napamet:

* Provjeriti vrijeme koje je ostalo na Shot Clocku (to se ne može postići koristeći ovakve Play-by-Play podatke)

* Provjeriti imaju li igrača više prostora na šutu u akcijama nakon timeouta (odnosno jesu li obrambeni igrači udaljeniji od njih).

* Provjeriti uzima li osoba više driblinga u akcijama nakon timeouta

* I još mnogo toga...
