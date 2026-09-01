# REGISTR PRŮSMYKŮ — v2.0

Zdroj dat: `alpine_passes_2026.csv` (44 záznamů, dodal autor)
Postavení ve zdrojové hierarchii: **AUTOR** — výšky a názvy z tohoto souboru mají přednost před externími zdroji.
Rozsah dle autora: **hlavní průsmyky, ne vyčerpávající seznam** → menší cols mohou chybět. Seznam je tedy spodní hranice, ne úplná trasa.
Pokyn autora: osm průsmyků, které nejsou v e-mailech, **nebylo vynecháno záměrně** — do původních poznámek se nevešly. Do dalších textů je zapracovat.
Rok dle autora: **všech pět výprav 2026.**

Legenda sloupce „V textu":

- **ANO** — průsmyk je jmenovitě uveden v e-mailu k dané výpravě
- **NOVÝ** — v CSV je, v e-mailu není → nový faktický materiál pro kapitolu

Legenda sloupce „Den": číslo dne je `INFERENCE` z geografie, pokud není označeno `AUTOR`.

---

## Rozdělení podle výprav

| Trip | Průsmyků | Nejvyšší bod | Nejnižší | Nad 2 000 m |
|---|---|---|---|---|
| T-01 Timmelsjoch | 2 | **Passo del Rombo / Timmelsjoch 2 474 m** | Jaufenpass 2 094 | 2 |
| T-02 Andermatt | 6 | **Furkapass 2 429 m** | Oberalppass 2 044 | 6 |
| T-03 Dolomity | 10 | **Passo Sella 2 244 m** | Passo Duran 1 601 | 4 |
| T-04 Bormio | 12 | **Passo dello Stelvio 2 757 m** | Passo della Mendola 1 363 | 8 |
| T-05 Francie | 14 | **Col du Galibier 2 642 m** | Lacets de Montvernier 782 | 2 |
| **Celkem** | **44** | **Stelvio 2 757 m** | Montvernier 782 | 22 |

**Nad 2 500 m (čtyři):** Stelvio 2 757, Galibier 2 642, Gavia 2 621, Umbrail 2 501 — tři ze čtyř na jedné výpravě (T-04).

---

## T-01 — Tyrolsko / Timmelsjoch (2 průsmyky)

| ID | Průsmyk | Také | m | Země | Den | V textu |
|---|---|---|---|---|---|---|
| 19 | Jaufenpass | Passo di Monte Giovo | 2 094 | IT (Bolzano) | D2 | ANO |
| 20 | Passo del Rombo | **Timmelsjoch** | 2 474 | IT/AT (Bolzano/Tirol) | D2 | ANO |

Oba na jednom dni, tam i zpět stejnou cestou (AUTOR). Brenner (~1 370 m), který autor musel přejet mezi Matrei am Brenner a Sterzingem, v CSV není — patrně proto, že ho nepovažuje za cyklistický průsmyk.

---

## T-02 — Švýcarsko / Andermatt (6 průsmyků)

| ID | Průsmyk | Také | m | Země | Den | V textu |
|---|---|---|---|---|---|---|
| 13 | Oberalppass | Pass Alpsu | 2 044 | CH (Uri/GR) | D1 | ANO |
| 16 | Sustenpass | — | 2 224 | CH (Bern/Uri) | D2 | ANO |
| 17 | Grimselpass | Col du Grimsel | 2 164 | CH (Bern/Valais) | D2 | ANO |
| 18 | Furkapass | Col de la Furka | 2 429 | CH (Uri/Valais) | D2 | ANO |
| 14 | Gotthardpass | Passo del San Gottardo | 2 106 | CH (Uri/Ticino) | D3 | ANO |
| 15 | **Tremola** | Via Tremola — jižní rampa Gotthardu | 2 106 | CH (Ticino) | D3 | ANO |

### ✅ Tímto se řeší kontradikce „pět vs. šest průsmyků"

Autor v e-mailu píše „za tři dny jsem projel šest alpských průsmyků", ale jako *průsmyky* jmenuje jen pět. Tremolu v textu zmiňuje („Z vrcholu jsem pokračoval na Tremolu, starou historickou cestu vydlážděnou žulovými kostkami"), ale jako silnici, ne jako průsmyk. CSV má pro tuto oblast **právě šest záznamů** — a šestým je **Tremola**, vedená jako samostatné ID s vlastní výškou (2 106 m, shodná s Gotthardem, protože je to jeho jižní rampa).

**Závěr:** autor počítal Tremolu jako samostatný průsmyk. Nesrovnalost byla ve způsobu, jakým e-mail průsmyky vyjmenovává, ne v realitě.
**Zbývající drobná nejistota:** protože je CSV „hlavní průsmyky", nelze úplně vylučit, že šestým byl jiný, nezaznamenaný col. Ale Tremola je zdaleka nejpravděpodobnější vysvětlení. Otázka je tím **zavřená**; v §12 zprávy už nefiguruje.

**Editorská poznámka:** je-li Tremola vedena jako samostatný průsmyk, potvrzuje to téma „silnice jako stavba" — autor rozlišuje dvě cesty přes tentýž sedlo podle toho, jak jsou postavené. To je pro knihu použitelné.

---

## T-03 — Dolomity (10 průsmyků)

| ID | Průsmyk | Také | m | Země | Den | V textu |
|---|---|---|---|---|---|---|
| 35 | Sella del Monte Zoncolan | Monte Zoncolan | 1 730 | IT (Udine) | D1 | ANO |
| 36 | **Sella di Razzo** | — | 1 760 | IT (Udine) | D1 | **NOVÝ** |
| 37 | Sella Ciampigotto | Passo Ciampigotto | 1 790 | IT (Udine/Belluno) | D1 | ANO |
| 38 | **Passo Tre Croci** | — | 1 805 | IT (Belluno) | D2 | **NOVÝ** |
| 39 | Passo Giau | — | 2 236 | IT (Belluno) | D2 | ANO |
| 40 | Passo Campolongo | Campolongopass | 1 875 | IT (Belluno/Bolzano) | D2 | ANO |
| 41 | Passo Gardena | Grödner Joch; Jëuf de Frara | 2 121 | IT (Bolzano) | D2 | ANO |
| 42 | **Passo Sella** | Sellajoch; Jëuf de Sela | **2 244** | IT (Bolzano/Trento) | D2 | ANO |
| 43 | Passo Pordoi | Pordoijoch | 2 239 | IT (Belluno/Trento) | D2 | ANO |
| 44 | Passo Duran | Forcella Duran | 1 601 | IT (Belluno) | D3 | ANO |

**Nové zjištění — Sella di Razzo.** Razzo a Ciampigotto leží na jedné silnici mezi Forni Avoltri a Vigo di Cadore, vzdálené od sebe jen několik kilometrů. První den tedy nebyl „Zoncolan a pak Ciampigotto", ale **Zoncolan → Razzo → Ciampigotto** — tři sedla za den. To vysvětluje, proč autor dorazil do Auronza „už pěkně unavený".

**Nové zjištění — Passo Tre Croci.** Leží mezi Misurinou a Cortinou d'Ampezzo, tedy přesně na úseku Auronzo → Cortina, který e-mail popisuje jako pouhý přejezd („Z Auronza jsem vyrazil směrem na Cortinu d'Ampezzo"). Druhý den tak nezačal rovinou, ale průsmykem. **Zásadní pro kapitolu:** den 2, popsaný jako „hlavní část celého výletu", měl tedy šest průsmyků, ne pět — Tre Croci, Giau a celou Sellarondu.

**Korekce mého předchozího odhadu:** nejvyšší bod výpravy je **Passo Sella 2 244 m**, ne Pordoi ani Giau (rozdíl proti Pordoi je 5 m). Opraveno v `01_TRIP_DATABASE.md`.

**Poznámka k pořadí Sellarondy — autorovo pořadí je správné.** E-mail uvádí „Campolongo, Gardena, Sella a Pordoi". To je platný celý okruh, pokud se začíná a končí v Arabbě: Arabba → Campolongo → Corvara → Gardena → Selva → Sella → Canazei → Pordoi → Arabba. Navíc je to jediné pořadí, které tomu dni vyhovuje: ze Giau se sjíždí přes Colle Santa Lucia a Caprile do Arabby, a den končí v Agordu po téže Cordevole. Autorův sled tedy netřeba opravovat ani zjišťovat.

*(Poznámka pro pořádek: v první verzi tohoto registru jsem tvrdil, že autorovo pořadí není jezditelné. Bylo to chybné tvrzení, opraveno.)*

---

## T-04 — Švýcarsko + Itálie / Lugano → Bormio → Bolzano (12 průsmyků)

| ID | Průsmyk | Také | m | Země | Den | V textu |
|---|---|---|---|---|---|---|
| 1 | **Malojapass** | Pass da Maloja; Passo del Maloja | 1 815 | CH (GR) | D1 | **NOVÝ** |
| 2 | Julierpass | Pass dal Güglia | 2 284 | CH (GR) | D1 | ANO |
| 3 | Albulapass | Pass d'Alvra | 2 315 | CH (GR) | **D2** | ANO |
| 5 | Berninapass | Pass dal Bernina; Passo del Bernina | 2 328 | CH (GR) | D2 | ANO |
| 6 | **Forcola di Livigno** | Livigno Pass; Fuorcla da Livign | 2 315 | IT/CH | D2 | **NOVÝ** \*|
| 4 | **Passo di Foscagno** | — | 2 291 | IT (Sondrio) | D2 | **NOVÝ** |
| 11 | **Passo dello Stelvio** | Stilfser Joch | **2 757** | IT (Sondrio/Bolzano) | D3, D5 | ANO |
| 10 | Umbrailpass | Passo dell'Umbrail; Giogo di Santa Maria | 2 501 | CH (hranice) | D3 | ANO |
| 8 | Passo del Mortirolo | Passo della Foppa | 1 852 | IT (Sondrio/Brescia) | D4 | ANO |
| 9 | Passo del Tonale | Tonalepass | 1 883 | IT (Trento/Brescia) | D4 | ANO |
| 7 | Passo di Gavia | — | 2 621 | IT (Sondrio/Brescia) | D4 | ANO |
| 12 | Passo della Mendola | Mendelpass | 1 363 | IT (Trento/Bolzano) | D5 | ANO |

\* **Forcola di Livigno — proč NOVÝ, i když e-mail slovo „Livigno" obsahuje.** CSV vede alias „Livigno Pass". `Bormio.md` píše „pokračovat přes Livigno až do Bormia", ale to je *město* Livigno, ne průsmyk. Samotná Forcola ani žádný její alias v e-mailu není. Verdikt NOVÝ platí.

### ✅ Tímto se řeší otevřená otázka trasy 1. dne

Chybějící spojnice Lugano → Graubünden je **Malojapass**. Maloja je jediná cyklistická cesta z Chiavenny do Engadinu (jinak se tam lze dostat přes Berninu z Tirana nebo přes Julier a Albulu od Churu, ale ne z tohoto směru), takže její přítomnost v CSV celý den vysvětluje.

**Členění dnů 1 a 2 — potvrzeno autorem, opraveno proti dřívějšímu odhadu.** Autor uvedl: *„I did Maloja > Julier > St. Moritz. I rode to Albula the first thing in the morning the next day."*

- **D1:** Lugano → Chiavenna → **Maloja** (1 815) → Silvaplana → **Julier** (2 284) → St. Moritz. **Dva průsmyky.**
- **D2:** St. Moritz → **Albula** (2 315) ráno → zpět do doliny → **Bernina** (2 328) → **Forcola di Livigno** (2 315) → Livigno → **Foscagno** (2 291) → Bormio. **Čtyři průsmyky, všechny nad 2 290 m.**

Dřívější verze registru přiřazovala Albulu k prvnímu dni. To bylo odvození z geografie a bylo chybné.

Zbývá jen drobnost: jak přesně byl Julier vyjet (ze Silvaplany nahoru a stejnou cestou zpět, nebo přes vrchol a okolo). V kapitole je to formulováno tak, aby platilo obojí.

Zbývá potvrdit pořadí Julier/Albula (obojí je jezditelné, viz `01_TRIP_DATABASE.md`).

**Poznámka k náročnosti.** Takto zrekonstruovaný první den vychází řádově na 200 km a přes 4 000 m převýšení — na úvodní den výpravy hodně, i když autor píše, že do St. Moritzu dorazil „večer". Podobná otázka je u třetího dne, kde přejezd mezi západní a východní rampou Stelvia přes Umbrail vyžaduje ještě spojku Santa Maria – Müstair – Mals – Prato. Obojí je v rámci možností a e-mail obojí potvrzuje, ale u obou dnů má smysl mít od autora skutečná čísla, než se do kapitoly napíše, jak dlouhý ten den byl. **AUTHOR INPUT** (viz `00_DISCOVERY_REPORT.md` §11, položka „Náročnost T-04 dnů 1 a 3").

### ✅ Tímto se doplňuje trasa 2. dne

Nové průsmyky Forcola di Livigno a Foscagno doplňují úsek St. Moritz → Bormio, který e-mail popisuje jen jako „Bernina Pass … přejezd do Itálie … přes Livigno až do Bormia":

**Bernina** (2 328) → **Forcola di Livigno** (2 315) → Livigno → **Foscagno** (2 291) → Bormio.

**Forcola di Livigno je hraniční přechod mezi Švýcarskem a Itálií.** E-mail říká: „Krátce po přejezdu do Itálie mě zastihla menší přeháňka." Je-li Forcola tím přejezdem, spadl déšť na sjezdu k Livignu.

**Zůstává to INFERENCE, ne fakt.** CSV neobsahuje ani dny, ani trasy — přiřazení Forcoly k druhému dni je odvozeno z geografie a lokalizace dešťě je odvození nad odvozením. Je to velmi pravděpodobné, ale do textu kapitoly to nesmí vstoupit jako popsaná scéna, dokud to autor nepotvrdí. Viz otázka 4 v `00_DISCOVERY_REPORT.md` §12.

Druhý den je v e-mailu popsaný v podstatě jedním průsmykem (Bernina) a přejezdem přes Livigno. Ve skutečnosti to byly **čtyři průsmyky nad 2 290 m** — Albula 2 315, Bernina 2 328, Forcola di Livigno 2 315, Foscagno 2 291 — a to i při tom, že šlo o přesun ze St. Moritzu do Bormia. Nejnabitější den celé výpravy vedle třetího. (Passo d'Eira mezi Livignem a Foscagnem by byl čtvrtý, ale v CSV není; autor jej mezi hlavní průsmyky nezařadil.)

### Nejvyšší bod celé knihy

**Passo dello Stelvio, 2 757 m** — potvrzuje autorovo „ve výšce přes 2 700 metrů". Stelvio vyjeté třikrát (D3 obě strany, D5 znovu) je nejvyšší bod celého archivu a jediné místo, kde se autorovo vlastní číslo dá ověřit proti jeho vlastnímu datovému souboru. Souhlasí.

---

## T-05 — Francouzské Alpy (14 průsmyků)

| ID | Průsmyk | Také | m | Země | Den | V textu |
|---|---|---|---|---|---|---|
| 21 | Belvédère du Mont du Chat | Relais du Mont du Chat | 1 486 | FR (Savoie) | D1 | ANO |
| 22 | L'Alpe d'Huez | — | 1 860 | FR (Isère) | D2, D4 | ANO |
| 31 | **Col de Sarenne** | — | 1 999 | FR (Isère) | D2 nebo D4 (?) | **NOVÝ** |
| 24 | Col de la Croix de Fer | — | 2 067 | FR (Savoie) | D2 | ANO |
| 23 | Col du Glandon | — | 1 924 | FR (Savoie) | D2 | ANO |
| 25 | Lacets de Montvernier | — | 782 | FR (Savoie) | D3 | ANO |
| 26 | **Col du Chaussy** | — | 1 533 | FR (Savoie) | D3 | **NOVÝ** |
| 27 | Col de la Madeleine | — | 1 993 | FR (Savoie) | D3 | ANO |
| 28 | Col du Mollard | — | 1 638 | FR (Savoie) | D3 | ANO |
| 29 | Col du Télégraphe | — | 1 566 | FR (Savoie) | D4 | ANO |
| 30 | **Col du Galibier** | — | **2 642** | FR (Savoie/H-Alpes) | D4 | ANO |
| 32 | **Col Luitel** | Col du Luitel | 1 262 | FR (Isère) | D4 | **NOVÝ** |
| 33 | Col de Chamrousse | — | 1 795 | FR (Isère) | D4 | ANO |
| 34 | Fort du Saint-Eynard | Fort Saint-Eynard | 1 340 | FR (Isère) | D5 | ANO |

**Nové zjištění — Col du Chaussy.** Lacets de Montvernier nejsou samostatné stoupání; jsou úvodní částí silnice na **Col du Chaussy**. Třetí den tedy nebyl „Montvernier → Madeleine → Mollard", ale **Montvernier/Chaussy → Madeleine → Mollard**. To zároveň vysvětluje, jak se autor z Montvernieru dostal dál — přes Chaussy se sjíždí do doliny Maurienne u La Chambre, tedy přímo k nástupu na Madeleine.

**Nové zjištění — Col Luitel.** Leží na silnici z Grenoblu přes Uriage na Chamrousse. Čtvrtý den tedy končil sledem **Luitel → Chamrousse**. Luitel je spíš rameno na výjezdu na Chamrousse než samostatný cíl, takže počítat jej jako pátý vrchol dne je trochu velkorysé — ale i tak: Télégraphe, Galibier, druhý výjezd na Alpe d'Huez a pak výjezd na Chamrousse přes Luitel dělají ze **dne 4 nejtěžší den celé sezóny.**

**Nejasné zařazení — Col de Sarenne (1 999 m).** Sarenne je sedlo východně od Alpe d'Huez, kterým se přejíždí mezi Alpe d'Huez a Le Freney v dolině Oisans. Autor vyjel Alpe d'Huez dvakrát (D2 a D4), takže Sarenne padá na jeden z těch dvou dnů — **zhruba nastejno pravděpodobné:**

- **D4** je routovací logikou přirozenější: Galibier → Lautaret → sjezd k Le Freney → **výjezd Sarenne** → Alpe d'Huez → Bourg d'Oisans → Grenoble. Druhé Alpe d'Huez jinou silnicí, bez vracení se stejnou cestou.
- **D2** je možné jako sjezd z Alpe d'Huez směrem k nástupu na Croix de Fer.

**AUTHOR INPUT** (nebo se určí z časových značek fotografií).

**Nejsou v CSV, ale v e-mailu ano:** La Bastille a Notre-Dame de Fourvière (městské výjezdy, ne průsmyky) a Les Michallons (výjezd 5. dne přerušený deštěm). Chybí i jakýkoli col ve Vercorsu z posledního dne — buď tam autor žádný sedlo nepřejel, nebo je to důsledek toho, že CSV obsahuje jen hlavní průsmyky. **AUTHOR INPUT, nízká priorita.**

**Autorova vlastní čísla — hrubá plausibilita.** Autor uvádí 1 038 km a 18 000 m za šest dní. Sečteme-li jen samotná stoupání ze čtrnácti záznamů (bez spojovacích úseků a bez druhého výjezdu na Alpe d'Huez), vyjde řádově 13–14 000 m; 18 000 m za šest dní včetně přejezdů a dvou dnů okolo Grenoblu je tedy plausibilní. Není to ověření — na to by byla potřeba GPX data — ale číslo si s registrem neprotiřečí.

---

## Výšky s odlišnými publikovanými hodnotami

Autorovo CSV je pro tento projekt závazné. U několika průsmyků se ale běžně publikované hodnoty liší, obvykle proto, že se měří jinak vrchol silnice a jinak cedule nebo nejvyšší bod vozovky. Pokud se výška dostane do popisku fotografie nebo do textu, stojí za to vědět, že se čtenář může setkat s jiným číslem:

| Průsmyk | CSV (závazné) | Jinde se uvádí | Poznámka |
|---|---|---|---|
| Col de la Madeleine | 1 993 | 2 000 | Cedule na vrcholu uvádí 2 000 m |
| Passo del Rombo / Timmelsjoch | 2 474 | 2 509 | 2 509 je nejvyšší bod silnice na italské straně |
| Passo di Gavia | 2 621 | 2 652 | Rozdíl podle měřicího bodu |
| Sustenpass | 2 224 | 2 260 | Rozdíl vrchol vs. tunel |
| Albulapass | 2 315 | 2 312 | Swisstopo a Wikipedie uvádějí 2 312 |
| Passo della Mendola | 1 363 | 1 362 | Wikipedie a ISPRA uvádějí 1 362 |

Ostatní výšky v CSV odpovídají běžně uváděným hodnotám v rámci pár metrů. **Doporučení:** v knize používat důsledně hodnoty z CSV a nemíchat je s hodnotami z map — jinak vznikne nekonzistence, kterou čtenář-cyklista pozná.

---

## Co registr celkově změnil

1. **Osm průsmyků, které v žádném e-mailu nejsou** (Maloja, Forcola di Livigno, Foscagno, Sella di Razzo, Passo Tre Croci, Col du Chaussy, Col Luitel, Col de Sarenne). Znamená to, že e-maily trasy systematicky podhodnocují — autor psal o tom, co si pamatoval jako důležité, ne o tom, co skutečně přejel. Pro kapitoly je to zisk: chybějící úseky se dají popsat věcně, bez vymýšlení.
2. **Dvě otevřené otázky se zavřely:** šest průsmyků v T-02 (= Tremola) a spojnice Lugano–Engadin (= Maloja). Třetí — čím byl „přejezd do Itálie" na D2 — je vysvětlená Forcolou di Livigno, ale zůstává INFERENCE, protože CSV neobsahuje dny ani trasy.
3. **Dvě dosud řídce vypadající etapy se ukázaly jako těžké:** T-04 den 2 (čtyři průsmyky nad 2 290 m, ne jeden) a T-03 den 2 (šest průsmyků, ne pět).
4. **Jedna korekce mého odhadu:** nejvyšší bod Dolomit je Passo Sella, ne Pordoi (rozdíl 5 m).
5. **Všechny výšky jsou teď AUTOR, ne EXT.** Faktografická kontrola výšek se v podstatě uzavřela.
6. **Nové otázky:** kam patří Col de Sarenne (D2 nebo D4); přejel autor ve Vercorsu nějaké sedlo; jak dlouhé byly ve skutečnosti první a třetí den T-04.
7. **Co registr naopak nezměnil:** pořadí Sellarondy v e-mailu je správné a nepotřebuje opravu.
