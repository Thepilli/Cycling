# PROJECT DISCOVERY REPORT — v2.0

Projekt: osobní cestopisná kniha (sólo silniční cyklistika v Alpách)
Datum zprávy: 27. 8. 2026
Fáze: **discovery** — bez psaní kapitol
Konvence uvozovek: „…" = doslovná citace autora; '…' = editorská poznámka nebo pracovní termín.
Související soubory: `01_TRIP_DATABASE.md`, `02_CHRONOLOGY.md`, `03_PASSES.md`

> **Změny ve v2.0** (po dodání `alpine_passes_2026.csv` a potvrzení roku autorem):
> — Kniha pokrývá **jednu sezónu, 2026**, ne roky cestování. Mění to strukturu, viz §3 a §8.
> — Všech 44 průsmyků má výšky přímo od autora. Faktografická kontrola výšek uzavřena.
> — **Osm průsmyků, o kterých autor v e-mailech nenapsal**, ale přejel je. Detail v `03_PASSES.md`.
> — Tři kontradikce z v1.0 vyřešeny (šest průsmyků v T-02, trasa 1. a 2. dne T-04).
> — **Poslední kapitola knihy se mění z Francie na Dolomity**, protože Dolomity jsou chronologicky poslední výprava sezóny.
>
> **Změny ve v2.1** (po odpovědích autora):
> — Vinice: pointa patří na 5. den, na cestu k Meranu. Kontradikce uzavřena.
> — Osm nezapsaných průsmyků nebylo vynecháno záměrně — do e-mailů se prostě nevešly. **Pokyn autora: zapracovat je do všech dalších textů.**
> — **Změna editorského režimu.** Autor uvolnil zákaz vymýšlení a povolil zážitkový detail z fantazie. Platí kompromis: píšu volně, ale **vymyšlené zážitkové pasáže značím ‹lomenými uvozovkami›**, aby je autor mohl potvrdit, přepsat nebo smazat. Faktografie a autorovy vlastní věty se neznačí. Základní princip projektu tím zůstává funkční: do memoáru nevstoupí nic vymyšleného bez autorova vědomí.
> — Datace ustupuje do pozadí; autor dodá skutečná data později. Chronologické **pořadí** je potvrzené.
> — **Pilotní kapitola T-04 napsána** — `KAPITOLA_04_Stelvio_trikrat.md`.
>
> **Změny ve v2.2** (redakční pokyny autora k pilotní kapitole):
> — **Vyřadit cyklisticko-závodní trivia.** Zamýšlený čtenář nemá závodní znalosti. Jména jezdců, etapy, výsledky a závodní pomníky v textu nemají místo — platí pro všechny další kapitoly. Doloženy zůstávají v aparátu.
> — **Méně encyklopedie.** Faktografie smí sloužit vyprávění, ne ho zaplňovat. Statistické výčty a historické exkurzy krátit.
> — Formulace „přejezdový den" nepoužívat ve významu „den bez obsahu" — všechny dny T-03 až T-05 jsou přesuny mezi místy.
>
> **Změny ve v2.3** (autorovy odpovědi k pilotní kapitole):
> — **Členění T-04 dnů 1 a 2 opraveno.** Den 1 = Maloja → Julier → St. Moritz. Albula je ráno druhého dne. Den 2 má tedy čtyři průsmyky, všechny nad 2 290 m.
> — Potvrzena trasa dne 3, tunel na Gavii, místo přeháňky i pasáž o sólo cestování (ta tím přestala být značená jako vymyšlená).
> — **Slovníkové pravidlo pro celý projekt:** ve významu „nezpracovaný, hrubý" psát **surové**, nikoli *syrové*. Týká se i citací autorova e-mailu, kde si autor vlastní formulaci opravil.
> — **Jezera zmiňovat střídmě.** Autor k nim nemá dost fotografií a nechce čtenáře plést. Platí pro všechny kapitoly, zvlášť pro T-02 (Grimsel) a T-03 (Barcis).
> — Autor ponechal všechny vymyšlené pasáže v pilotní kapitole. Režim značení tedy funguje a pokračuje.
>
> **Změny ve v3.0 — napsány všechny kapitoly:**
> — `KAPITOLA_01_Timmelsjoch.md` · `KAPITOLA_02_Sest_prusmyku.md` · `KAPITOLA_03_Stelvio_trikrat.md` (dříve 04) · `KAPITOLA_04_Galibier.md` · `KAPITOLA_05_Vercors.md` · `KAPITOLA_06_Dolomity.md`
> — Francouzská výprava rozdělena na dvě kapitoly (dny 1–4 a 5–6), jak navrhovala varianta C.
> — ⚠️ **Dvourychlostní stav faktografie.** Kapitoly 1–3 stojí na dokončené rešerši. **Kapitoly 4–6 nikoli** — ověřování se u francouzských Alp a Dolomit nedokončilo. V těch třech kapitolách jsem použil jen údaje, kterými jsem si přiměřeně jistý, všechno ostatní vynechal, a v každém aparátu je seznam toho, co je nutné před tiskem ověřit. **Výjimka: údaje o evropském suchu v létě 2026 v kapitole 6 ověřené jsou** a nesou závěr celé knihy.
> — Otevřené otázky na autora: 5 na kapitolu, celkem 25.

---

## 1. Přehled archivu

Složka `Cycling` obsahuje **pět zdrojových dokumentů, celkem 2 801 slov**, a od v2.0 navíc autorův datový soubor `alpine_passes_2026.csv` (44 průsmyků). Žádné fotografie, žádná GPS data, žádné itineráře, žádné poznámky z cesty.

| Soubor | Slov | Typ | Trip |
|---|---|---|---|
| `timmeljoch.md` | 355 | e-mail rodině | T-01 Tyrolsko |
| `Hospental.md` | 438 | e-mail rodině | T-02 Švýcarsko |
| `Bormio.md` | 456 | e-mail rodině | T-04 Švýcarsko + Itálie |
| `Dolomites.md` | 745 | e-mail rodině | T-03 Dolomity |
| `Grenoble.md` | 807 | e-mail rodině | T-05 Francie |

**Charakter materiálu.** Všech pět dokumentů je stejný žánr: retrospektivní shrnující e-mail rodině, napsaný po návratu, otevřený oslovením „Ahojte rodinove" (ve čtyřech případech bez diakritiky, v `Hospental.md` „rodinové") a zakončený odkazem na album Google Photos. Nejde o deník ani o poznámky z cesty. To má tři důsledky pro celý projekt:

1. **Materiál je konzistentní ve hlasu, ale plochý v čase.** Vše je vyprávěno zpětně a s odstupem, což znamená hodnocení („byl to náročný den, ale zároveň přesně ten typ cyklistického dne, kvůli kterému člověk do Dolomit jede") místo scén se konkrétním časem, místem a průběhem. Kniha bude potřebovat scény, které v archivu prakticky nejsou.
2. **Materiál je systematicky pozitivní.** V každé výpravě všechno vyšlo. Rodinný e-mail je žánr, který nehlásí problémy. Skutečné potíže, pochybnosti, nuda, špatná jídla, špatné noclehy, chybná odbočení v archivu chybí — ne proto, že se nestaly, ale proto, že se do e-mailu rodině nepíší.
3. **Nechybí souvislost, chybí detail.** Denní členění je u všech pěti výprav úplné a přehledné. To je nečekaně dobrá výchozí pozice: struktura kapitol je hotová, chybí zrno.

**Co v archivu úplně chybí:** data, vzdálenosti a převýšení (kromě T-05), fotografie jako soubory, jídlo, ubytování jako zážitek, konkrétní lidé, jakýkoli dialog, náklady, mechanické problémy (kromě „3 píchlé duše" jako čísla), příprava a trénink, dojezdy vlakem/autobusem jako zážitek.

**Vybavení a kolo** se objevují jen v náznacích — „kolo jelo krasne" a „příležitost vytáhnout nepromoky" (T-04), „na silničním kole to člověka trochu vytřese" (T-02). Autor o technice nepíše, přestože o silnicích a stavbách píše rád; je otázka, jestli to je záměr, nebo jen formát e-mailu.

---

## 2. Trip inventory

Plná verze v `01_TRIP_DATABASE.md`. Zkráceně:

| ID | Trip | Dny | Země | Trasa | Klíčová stoupání | Km / m | Status |
|---|---|---|---|---|---|---|---|
| T-01 | Timmelsjoch | 3 | DE/AT/IT | Mnichov → Matrei am Brenner → Mnichov | Timmelsjoch 2 474, Jaufenpass 2 094 | UNKNOWN | Outline |
| T-02 | Hospental / Andermatt | 3 | CH | Curych → Andermatt → Curych | Oberalp, Susten, Grimsel, **Furka 2 429**, Gotthard, Tremola | UNKNOWN | Outline |
| T-03 | Dolomity | 3 | AT/IT | Spittal an der Drau → Udine | Zoncolan, *Razzo*, Ciampigotto, *Tre Croci*, Giau, Sellaronda (4, nejvýš **Sella 2 244**), Duran | UNKNOWN | Outline |
| T-04 | Bormio / Stelvio | 5 | CH/IT | Lugano → Bormio → Bolzano | *Maloja*, Julier, Albula, Bernina, *Forcola di Livigno*, *Foscagno*, **Stelvio 2 757 (3×)**, Umbrail, Mortirolo, Tonale, Gavia, Mendel | UNKNOWN | Outline |
| T-05 | Francouzské Alpy | 6 | CH/FR | Ženeva → Grenoble/Valmeinier → Lyon | Mont du Chat, Alpe d'Huez 2×, *Sarenne*, Croix de Fer, Glandon, Montvernier/*Chaussy*, Madeleine, Mollard, Télégraphe, **Galibier 2 642**, *Luitel*, Chamrousse | **1 038 km / 18 000 m** | Outline |

*Kurzívou* průsmyky, které jsou v autorově CSV, ale v žádném e-mailu nejsou.

Celkem: **20 dní na kole, 5 zemí, 44 průsmyků, nejvyšší bod Stelvio 2 757 m** — všechno v jediné sezóně 2026.

| Trip | Průsmyků | Nejvyšší bod | Nad 2 000 m |
|---|---|---|---|
| T-01 Timmelsjoch | 2 | Timmelsjoch 2 474 | 2 |
| T-02 Andermatt | 6 | Furka 2 429 | 6 |
| T-03 Dolomity | 10 | Passo Sella 2 244 | 4 |
| T-04 Bormio | 12 | **Stelvio 2 757** | 8 |
| T-05 Francie | 14 | Galibier 2 642 | 2 |

Čtyři průsmyky nad 2 500 m: Stelvio 2 757, Galibier 2 642, Gavia 2 621, Umbrail 2 501 — tři ze čtyř na jedné výpravě (T-04). Dvacet dva ze čtyřiačtyřiceti průsmyků je nad 2 000 m.

---

## 3. Chronologická osa — jedna sezóna 2026

Detail v `02_CHRONOLOGY.md`. **Autor potvrdil, že všech pět výprav proběhlo v roce 2026.** To je nejdůležitější jediná informace, která do projektu zatím přišla, protože mění povahu knihy.

Nejde o „roky cestování", ale o **jedno léto**: 20 dní na kole, 44 průsmyků, pět zemí, mezi jarem a srpnem 2026. Poslední výprava je stará nejvýš pár týdnů.

**Revidované pořadí.** Ve v1.0 jsem odvodil, že Francie je poslední výprava, protože je největší a autor ji retrospektivně srovnává s ostatními. **To padlo:** Francie proběhla během Tour de France, tedy v červenci, a Dolomity téměř jistě až v polovině srpna.

```
V/VI    T-01  Timmelsjoch   víkend    2 průsmyky    max 2 474 m
VI/VII  T-02  Andermatt     víkend    6 průsmyků    max 2 429 m
VI/VII  T-04  Bormio        5 dní    12 průsmyků    max 2 757 m   ← nejvyšší bod sezóny
VII     T-05  Francie       6 dní    14 průsmyků    max 2 642 m   ← 1 038 km / 18 000 m
14.–16. VIII* T-03 Dolomity 3 dny    10 průsmyků    max 2 244 m   ← horko a sucho
(* jediný termín odvozený, ne potvrzený)
```

**Datování T-03 na 14.–16. srpna 2026** je INFERENCE s vysokou spolehlivostí: druhý den připadl na italský státní svátek (AUTOR), text zdůrazňuje horko a sucho (tedy letní vrchol), Ferragosto 15. 8. 2026 je sobota, a pátek–nedělní vzorec autor prokazatelně používá u T-01 i T-02. Řetěz úvah včetně kontroly alternativ v `02_CHRONOLOGY.md` §3.

**Sezóna má tři fáze:** rozjezd (dva víkendy, blízké destinace), vrchol (dvě velké výpravy zpět za sebou, 11 dní, 26 průsmyků, Tour de France) a dozvuk (Dolomity v srpnovém horku).

**Zbývající neznámá v posloupnosti:** vzájemné pořadí T-04 a T-05. Obě padají do června–července a materiál je vůči sobě neumisťuje.

**Výhrada k rámování.** T-05 říká, že se výprava „zařadil mezi moje nejlepší cyklistické dovolené **vůbec**" (mužský rod dle zdroje) — z toho vyplývá, že výpravy z předchozích let existují, jen k nim ve složce není zdrojový text. Kniha tedy zachycuje jednu sezónu, ne celou cyklistickou historii autora. Naopak formulace v T-03 „po všech těch výletech přes Alpy" je v rámci jediné sezóny plně vysvětlitelná — odkazuje na čtyři výpravy, které jí předcházely.

---

## 4. Nejsilnější kandidáti na kapitoly

### A — Silné kapitoly (materiál nese kapitolu už teď)

**T-04 Bormio / Stelvio.** Nejikoničtější sada stoupání v archivu a nejčistší vnitřní struktura: příjezd → tři dny ze základny v Bormiu → odjezd jiným směrem. Má také nejlepší pointu v celém archivu — kontrast ledovců nad 2 700 m ráno a vinic večer (pozor, viz kontradikce v §11). Den 4 (Mortirolo–Tonale–Gavia) rozlišuje tři průsmyky jako tři různé povahy, což autor dělá i v T-02 (Susten–Grimsel–Furka), ale tady nejzřetelněji. A Gavia je místo, kde nejkonkrétněji pojmenuje, co pro něj sólo cestování znamená (týž e-mail to zobecňuje ještě jednou v závěru, a znovu se k tomu vrací T-05). To je přirozený emocionální vrchol kapitoly.

**T-05 Francouzské Alpy.** Nejbohatší materiál, jediná výprava s čísly a jediná, kde je vnější událost (Tour de France) rovnocenným tématem s vlastním výkonem. Obsahuje také jediný pořádný zvrat v archivu: zrušený den ve Vercorsu, improvizované pevnosti a návrat do Vercorsu poslední den, který se povede. To je hotový narativní oblouk — selhání, náhradní program, druhá šance, uzavření. Zvažte rozdělení na dvě kapitoly (Maurienne / Galibier–Tour × Vercors a odjezd na Lyon).

**T-03 Dolomity.** Silná ne kvůli stoupáním, ale kvůli pozorování, které v archivu nemá obdobu: **suché léto.** Autor si všímá, že řeky a potoky mají místy minimum vody, že jezera včetně Lago di Barcis jsou znatelně níž, a že to boří jeho vlastní představu Dolomit jako zelené vodnaté krajiny. Je to jediné místo, kde text nezávisle vypovídá o něčem širším než o vlastním zážitku. Také obsahuje nejlepší popisnou pasáž („pocit, že projíždím nějakou úplně pravěkoup krajinou") a lidskou scénu — italský svátek, plná parkoviště u nástupů na túry, davy mířících do hor.

### B — Kapitoly vyžadující doplnění

**T-02 Hospental / Andermatt.** Struktura je bezvadná (tři dny, tři jasně odlišené charaktery hor, Tremola jako neobvyklý závěr) a Tremola je vizuálně i historicky nejzajímavější silnice v archivu. Ale text je jen 438 slov a je téměř bez konkrétních detailů. Potřebuje autorský vstup ke třem věcem: co bylo na Furce jiné než na Susten a Grimselu, jaké to bylo jet Tremolu na silničním kole a jaké to bylo mít Gotthard brzy ráno téměř bez lidí. Také je nutné dořešit rozpor v počtu průsmyků.

### C — Krátká interlude

**T-01 Timmelsjoch.** Nejkratší a nejméně detailní materiál, ale má něco, co nemá žádná jiná výprava: **impulzivnost.** Rozhodnutí ve středu večer, v pátek odjezd z Mnichova. To je téma na krátkou kapitolu nebo interlude, ne na plnou kapitolu. Hodí se ideálně jako úvodní kapitola knihy nebo jako vsuvka mezi dvě velké výpravy. Detail s únikovými pruhy pro kamiony je nejlepší jednotlivá vizuální drobnost v celém archivu — přesně ten typ technického pozorování, který dává knize charakter.

### D — Pouze archiv

Nic. Všech pět dokumentů obsahuje použitelný materiál. **Žádný zdroj nemazat ani nepřepisovat** — originály zůstávají jako referenční vrstva, kapitoly se píší do nových souborů.

---

## 5. Stories requiring additional material — souhrn priorit

| Trip | Co nejvíc chybí | Priorita |
|---|---|---|
| T-02 | scénový detail, cokoli konkrétního (438 slov na 6 průsmyků) | **vysoká** |
| T-01 | motivace, průběh sobotního výjezdu, jak vlastně vypadal ten spontánní odjezd | **vysoká** |
| T-04 | vyřešení kontradikce s vinicemi; skutečná délka dnů 1 a 3 | **vysoká** (pilotní kapitola) |
| T-03 | jakýkoli detail k italskému svátku (nejlidnatější scéna archivu po Galibieru) | střední |
| T-05 | datace, počet nocí v Grenoblu, jak vypadal ten déšť | nízká |

---

## 6. Opakující se témata (co z materiálu skutečně vyrůstá)

Následující témata jsou v archivu prokazatelně přítomná, ne dosazená:

1. **Silnice jako stavba, ne jako trasa.** Nejsilnější a nejcharakterističtější téma celého archivu. Autor obdivuje serpentiny Stelvia jako inženýrský výkon („nezbývá než obdivovat, co se tady podařilo vybudovat"), Tremolu jako historickou dlážděnou cestu, Lacets de Montvernier jako „silnice poskládaná jako vystřižená z modelové železnice", silnice Vercorsu vytesané ve skalách, únikové pruhy pro kamiony na cestě do Innsbrucku, přehrady na Grimselu. Toto téma odlišuje knihu od jakéhokoli jiného cyklistického cestopisu a mělo by být její kostrou.

2. **Až na kole si člověk uvědomí, jak velké ty hory jsou.** Autorova vlastní teze, doslovně vyslovená v T-03 („člověk si teprve na kole uvědomí, jak gigantické ty hory ve skutečnosti jsou") a znovu v T-05 („Člověk si každé převýšení poctivě odšlape, nahoře si výhled zaslouží"). Vrací se i nepřímo: silnice vypadá titěrně proti dolomitským masivům. Toto je téma doslovu.

3. **Kontrast na malé vzdálenosti.** Explicitně pojmenováno v T-04 („jak odlišný charakter mají jednotlivá údolí a průsmyky, přestože jsou od sebe často jen pár desítek kilometrů") a strukturálně přítomno všude jinde: Susten vs. Grimsel vs. Furka, Mortirolo vs. Tonale vs. Gavia, vysoké průsmyky vs. Vercors, hory vs. nížina u Udine.

4. **Město jako protipól hor.** Každá výprava končí nebo se láme v městě: Mnichov, Lucern, Udine, Bolzano, Lyon a Fourvière. U Mnichova, Lucernu a Lyonu je to popsaný zážitek, u Udine a Bolzana jen koncový bod. Autor to nikde netematizuje, ale dělá to důsledně — jde o skutečný, autorem nepojmenovaný vzorec, což je z editorského hlediska cenné.

5. **Sólo jako podmínka, ne jako osamělost.** Explicitně na Gavii („Právě tady jsem si asi nejvíc uvědomil, jakou svobodu člověku dává cestování na kole o samotě") a v T-05. Nikde není ani stopa po stesku nebo osamělosti. Kniha by neměla sólo cestování romantizovat směrem k melancholii — v materiálu není.

6. **Postupné zvyšování ambicí.** Dva průsmyky za víkend (T-01) → čtyři až šest velkých stoupání v jednom dni (T-05 d4, T-03 d2); 3 dny → 6 dní; okružní víkend se stejným startem i cílem → 1 038 km napříč Francií s řetězcem ubytování. Osa knihy, pokud bude chronologická.

7. **Cyklistická historie jako kulisa.** Silné jen v T-05 (Tour, jména vítězů v serpentinách) a jako jméno v T-04, kde je Stelvio „legenda všech legend" a Zoncolan „jeden z těch kopců, o kterých člověk slyší mezi cyklisty" (Mortirolo ani Gavia autor legendami nenazývá). Není to nosné téma celé knihy, ale je to téma jedné kapitoly.

8. **Suché léto.** Zatím jednorázové (T-03), ale je to jediné místo, kde text přesahuje osobní zážitek. Pokud existují další výpravy s podobným pozorováním, může z toho být druhá vrstva celé knihy.

**Témata, která materiál NEnese** (nedosazovat): utrpení a překonávání sebe sama jako hlavní motiv (autor je konzistentně spokojený a pragmatický), setkávání s konkrétními lidmi (v archivu žádné není — lidé se objevují jen jako davy: fanoušci Tour, motorkáři na Grimselu, turisté o italském svátku), duchovní nebo životní krize řešená v horách (žádná stopa), gastronomie (nulová zmínka za všech pět výprav).

**Téma na hranici:** místní prostředí a architektura se objevují, ale vždy jen jako povšimnutí v jedné větě — „typické švýcarské vesničky, zelené pastviny a všude dokonale upravené domy" a historické centrum Lucernu (T-02), „projet se kolem historických budov" v Mnichově (T-01), „bylo krásné vidět, jak Italové tráví svátek venku" (T-03). Nosné téma to zatím není, ale je to nejsnadněji rozvinutelný směr, pokud kniha nemá být jen o silnicích.

---

## 7. Autorský hlas — profil

**Základní charakteristika.** Pragmatický, technicky uvažující, nadšený, ale nikdy exaltovaný vypravěč, který mluví k lidem, kteří ho znají. Nepředstavuje se a nepotřebuje, aby mu čtenář fandil. Své „proč" vysloví jen jednou za celý archiv, a to až ve třetím odstavci od konce T-05 („cestovat na kole je ten nejlepší způsob, jak hory opravdu poznat") — tam je jádro doslovu.

**Stavební prvky hlasu, které je nutné zachovat:**

- **Neosobní „člověk" jako první osoba.** Nejcharakterističtější rys celého archivu: „člověk měl občas pocit, že stoupání snad nikdy neskončí", „nezbývá než obdivovat", „člověk si připadá jako součást historie Tour". Autor takto odstupuje od vlastního zážitku a zobecňuje ho. Je to zdvořilé, mírně ironické a velmi středoevropské. **Nepřepisovat mechanicky do „já"** — ale ve scénách, kde má být napětí, „já" použít, protože „člověk" napětí zabíjí.
- **Podhodnocující popis obtížnosti.** „ví, že to nebude zadarmo", „pěkně výživný", „nohy rozhodně věděly, co mají za sebou", „nohy trochu těžší". Nikdy „trápil jsem se" nebo „bylo to utrpení".
- **Sebeironie u vlastních rozhodnutí.** „Vyjet tuhle horu podruhé během jediné cesty už byla spíš otázka cti než rozumu." To je nejlepší věta v archivu a šablona pro humor celé knihy.
- **Technická drobnost jako pointa.** Únikové pruhy pro kamiony, žulové kostky Tremoly, 16 % na Zoncolanu, 21 serpentin se jmény vítězů, 3 píchlé duše. Autor pointuje čísly a detaily, ne emocemi.
- **Statistické uzavření.** „Sečteno a podtrženo: 1038 km, 18 tisíc výškových metrů, 3 píchlé duše, a jeden spokojený opálený cyklista." Zachovat jako formát — ideálně jako sjednocenou grafickou vrstvu na konci každé kapitoly.
- **Otevřený konec směrem k další výpravě.** „mám takové tušení, že jsem tam rozhodně nebyl naposledy", „Teď už jen vymyslet, kam vyrazit příště". Funkční jako spojka mezi kapitolami.

**Co je v hlase slabé a co má editace řešit:**

- **Opakující se rámování „podle plánu".** Ve třech textech doslova: „Trasa vyšla přesně podle plánu" (T-04), „Všechno vyšlo přesně podle plánu" + „Trasa vyšla přesně podle plánu" + „další výlet splněn podle plánu" (T-03, tedy 3×), „všechno vycházelo přesně podle plánu" (T-05). Ve zbylých dvou totéž jinými slovy: „Celkově vyšel víkend nad očekávání dobře" (T-01), „Celkově vyšlo úplně všechno – počasí, trasy i nohy" (T-02). Souhrnně tedy pět z pěti textů uzavírá stejným gestem: všechno vyšlo. V knize to zabije napětí. Řešení: ponechat jednou nebo dvakrát jako charakterový rys (autor je plánovač a záleží mu na tom), jinak nechat vyplynout z vyprávění.
- **Vyprázdněná superlativa.** „fantastické", „naprosto úchvatný", „parádní", „nádherný", „krásný" se opakují bez rozlišení. Nahradit konkrétním popisem — materiálu k tomu je málo, proto §12.
- **Formulkové závěry.** Tři z pěti textů (`timmeljoch.md`, `Dolomites.md`, `Grenoble.md`) končí variantou 'bylo to super a určitě se vrátím'. Zbylé dva mají konec vlastní a lepší: „Švýcarsko je pro silniční cyklistiku opravdu těžko překonatelné" a „nenapadá mě jediná věc, kterou bych udělal jinak". Každá kapitola potřebuje vlastní konec — tyhle dva ukazují, že autor to umí.
- **Hodnocení místo scény.** Viz §1. Hlavní editorská práce celého projektu.

**Cíl:** ne „literární cestopis", ale **dobře redigovaný dopis rodině, který si smí dovolit být delší a pomalejší.** Původní žánr je zároveň největší silou materiálu.

---

## 8. Možné struktury knihy

### Varianta A — Chronologická

```
1. Timmelsjoch — impulzivní víkend            (T-01, V/VI)
2. Šest průsmyků za tři dny                   (T-02, VI/VII)
3. Stelvio třikrát                            (T-04, VI/VII)
4. Galibier v očekávání Tour                  (T-05, VII)
5. Dolomity v suchém srpnu                    (T-03, 14.–16. VIII — odvozeno)
Doslov — proč na kole
```

**Proč funguje:** oblouk je vestavěný a po potvrzení roku ještě silnější. Sezóna jde od dvou průsmyků za víkend k dvanácti a čtrnácti, a to během několika měsíců — z vágního vývoje se stává příčinná linie jednoho léta. Nejkratší materiál (T-01) stojí na začátku, kde krátkost funguje jako předehra.

**Slabiny:** chybí měsíce čtyř výprav a pořadí T-04/T-05. Tři prostřední kapitoly mají podobný tvar (přijet, jet průsmyky, odjet) a chronologické řazení to zvýrazní.

**Zásadní změna proti v1.0:** kniha už nekončí Francií, ale Dolomity. To je paradoxně lepší — sezóna nekončí největším výkonem, ale nejsilnějším pozorováním (vyschlé řeky, nízká jezera, srpnové horko). Viz §9.

### Varianta B — Tematická / geografická

```
ČÁST I — ŠVÝCARSKO: silnice jako stavba       (T-02, část T-04)
ČÁST II — DOLOMITY: krajina jako protivník    (T-03)
ČÁST III — TYROLSKO: spontánní rozhodnutí     (T-01)
ČÁST IV — FRANCIE: kolo a jeho historie       (T-05)
```

**Proč funguje:** dovoluje seskupit materiál podle témat z §6 a tím zamaskovat, že tři kapitoly mají stejný tvar. Umožnilo by rozdělit T-04 mezi Švýcarsko a Itálii.

**Slabiny:** při pěti výpravách je členění na čtyři části absurdně těžké — každá „část" má jednu kapitolu. Trhá to T-04, což je nejlepší celistvá kapitola v archivu. Ztrácí oblouk rostoucích ambicí. **Pro současný rozsah archivu nedoporučuji.** Variantu B otevřít znovu, až bude výprav aspoň deset.

### Varianta C — Hybridní (doporučeno)

Chronologické řazení kapitol, ale s **explicitní tematickou vrstvou** nesenou třemi krátkými nečíslovanými vsuvkami mezi kapitolami. Vsuvky vytahují témata, která by v jednotlivých kapitolách zmizela:

```
Předmluva — jedno léto, dvacet dní, čtyřicet čtyři průsmyků

1. Timmelsjoch                                (T-01, V/VI)
   ↳ Vsuvka: Únikové pruhy — o silnicích jako stavbách
2. Šest průsmyků za tři dny                   (T-02, VI/VII)
   ↳ Vsuvka: Tremola — cesta, po které se jezdilo dřív
3. Stelvio třikrát                            (T-04, VI/VII)
   ↳ Vsuvka: Sám — o tom, proč sólo
4. Galibier v očekávání Tour                  (T-05, dny 1–4, VII)
5. Vercors, druhý pokus                       (T-05, dny 5–6, VII)
6. Dolomity v suchém srpnu                    (T-03, 14.–16. VIII — odvozeno)

Doslov — až na kole si člověk uvědomí, jak velké to je
Přehled: 20 dní, 5 zemí, 44 průsmyků, nejvýš Stelvio 2 757 m
```

**Proč doporučuji C:** zachová oblouk varianty A, dostane do knihy témata varianty B, a hlavně — vsuvky jsou krátké texty, které lze napsat z existujícího materiálu plus externí faktografie **bez potřeby autorského vstupu.** To dovoluje na knize pracovat, i když nebudou hned zodpovězeny všechny otázky. Rozdělení T-05 na dvě kapitoly řeší jeho nepoměrnou délku.

**Nová výhoda po potvrzení roku:** Dolomity jako závěrečná kapitola dávají knize konec, který nevymýšlíme — sezóna doopravdy skončila v srpnovém horku u vyschlých řek a sjezdem z hor do naprosté nížiny u Udine. Poslední větou knihy může být pozorování o suchu, ne shrnutí výkonu. Vsuvka „Tremola" se navíc posunula, protože Tremolu autor sám vede jako samostatný průsmyk (viz `03_PASSES.md`) — to jí dává faktickou oporu, nejen editorský nápad.

---

## 9. Předběžný obsah s premisami kapitol

| # | Pracovní název | Trip | Premisa (jedna věta) | Otevírací scéna | Konec | Status |
|---|---|---|---|---|---|---|
| — | Předmluva | — | Kniha není o kole; kolo je způsob, jak se dostat dovnitř krajiny. | — | — | Nezaloženo |
| 1 | Timmelsjoch | T-01 | Ve středu večer bylo škoda sedět doma, v pátek vyjížděl z Mnichova. | Rozhodnutí ve středu, nebo prudký sjezd s únikovými pruhy | Sebevědomí, že dlouhé průsmyky jsou zvládnutelné | Outline |
| — | Vsuvka: Únikové pruhy | — | Silnice v horách jsou stavby, které někdo musel vymyslet. | — | — | Nezaloženo |
| 2 | Šest průsmyků za tři dny | T-02 | Susten, Grimsel a Furka se vejdou do jednoho dne, a přece jsou to tři různé hory. | Zahřívací Oberalp jako signál, že jde o víc než přejezd | Lucern, jezero, historické centrum — kontrast po dvou dnech v průsmycích | Outline |
| — | Vsuvka: Tremola | — | Než postavili novou silnici, jezdilo se po žulových kostkách. | — | — | Nezaloženo |
| 3 | Stelvio třikrát | T-04 | Ráno ledovce nad 2 700 m, večer vinice — a mezi tím jedna etapa. | Vrchol Stelvia a pohled dolů na serpentiny | Gavia a svoboda sólo cestování / „nenapadá mě jediná věc, kterou bych udělal jinak" | Outline |
| — | Vsuvka: Sám | — | Sólo není o osamělosti, je o tom, že se člověk nemusí s nikým dohadovat. | — | — | Nezaloženo |
| 4 | Galibier v očekávání Tour | T-05 d1–4 | Vyjet legendární kopec den, kdy se na něj scházejí desetitisíce lidí, je jiný sport. | Karavana Tour v Chambéry — atmosféra, kterou zná hlavně z televize | Nejtěžší den sezóny: Télégraphe, Galibier, druhé Alpe d'Huez, Luitel, Chamrousse — „spíš otázka cti než rozumu" | Outline |
| 5 | Vercors, druhý pokus | T-05 d5–6 | Jediný den, který nevyšel — a den, který to napravil. | Déšť, který postupně zesílí, až nemá smysl pokračovat | Fourvière nad Lyonem jako poslední kopec před autobusem | Outline |
| 6 | Dolomity v suchém srpnu | T-03 | Konec sezóny: hory, které si člověk pamatuje jako zelené a vodnaté, byly vyprahlé. | Italský svátek, plná parkoviště, davy mířících do hor | Sjezd z hor do naprosté nížiny u Udine — a poznámka o suchu jako poslední větě knihy | Outline |
| — | Doslov | — | Až na kole si člověk uvědomí, jak velké ty hory jsou. | — | — | Nezaloženo |

---

## 10. Fotoarchiv — zjištění

**Ve složce nejsou žádné fotografie.** Všech pět dokumentů odkazuje na album Google Photos:

| Trip | Odkaz |
|---|---|
| T-01 | `photos.app.goo.gl/Tre8wT2Dt8jWuEX48` + výškový profil sobotní etapy |
| T-02 | `photos.app.goo.gl/9U6RHmK4G4Cbgq4P9` |
| T-03 | `photos.app.goo.gl/wsPV9b7tLYuLmsVTA` |
| T-04 | `photos.app.goo.gl/f1dh11QwzMPyEovZ6` |
| T-05 | `photos.app.goo.gl/tZ5KmmfD8MphLUkx8` |

**Blokující problém.** K albům nemám přístup a fotografie z Google Photos nelze do projektu stáhnout automaticky. Bez lokálních souborů nelze číst EXIF (datum, GPS). Po dodání CSV a potvrzení roku už fotky **nejsou jediná cesta k datování** — chybí jen měsíce čtyř výprav — ale zůstávají jedinou cestou k vizuálnímu detailu, k zařazení Col de Sarenne a k tomu, na které silnici spadla přeháňka 2. dne T-04.

**Doporučený postup — nejvyšší priorita celého projektu:**

1. Vytvořit ve složce `Cycling` podsložku `photos/` s pěti podsložkami `T-01` … `T-05`.
2. Exportovat albumy z Google Photos **v originální kvalitě a se zachovanou metadatou** (Google Takeout, ne stažení přes prohlížeč — to EXIF u některých formátů odstraní).
3. Nahlásit hotovo. Pak z EXIF vytáhnu data, časy a GPS, sestavím skutečnou kalendářní osu, přiřadím fotografie ke dnům a trasám a založím `04_PHOTO_INDEX.md` s tagovacím systémem podle projektových instrukcí.

Tento krok odemkne datace, ověření tras, kontrolu pořadí průsmyků i většinu chybějícího vizuálního detailu — s fotkami před sebou budou autorské otázky v §12 mnohem konkrétnější a přesnější.

**Poznámka k výškovým profilům.** T-01 zmiňuje sdílený „sobotní profil". Pokud existují GPX nebo Strava/Garmin záznamy z výprav, jsou po fotkách druhý nejcennější zdroj — dodají vzdálenosti, převýšení a data, která v archivu chybí u čtyř z pěti výprav.

---

## 11. Kontradikce a nejistoty

### ✅ Vyřešeno dodáním `alpine_passes_2026.csv` a odpověďmi autora

1. **T-02 — počet průsmyků.** Autor psal „šest alpských průsmyků" a jako průsmyky jmenoval pět. Tremolu v textu zmiňuje, ale jako silnici („starou historickou cestu vydlážděnou žulovými kostkami"), ne jako průsmyk — a v CSV ji vede jako samostatné ID (2 106 m, jižní rampa Gotthardu). Šestým průsmykem je tedy Tremola. Drobná výhrada: CSV obsahuje „hlavní průsmyky", takže teoreticky mohl být šestým jiný col — Tremola je ale zdaleka nejpravděpodobnější.
2. **T-04 — chybějící spojnice Lugano → Graubünden.** Je to **Malojapass** (1 815 m). První den zněl Lugano → Chiavenna → Maloja → Silvaplana → Julier → Albula → St. Moritz.
3. **T-04 — členění a úseky dnů 1 a 2.** ✅ Potvrzeno autorem: den 1 = Maloja → Julier → St. Moritz (dva průsmyky); **Albula patří na ráno druhého dne.** Den 2 je pak St. Moritz → Albula → Bernina → **Forcola di Livigno** (= přejezd do Itálie, kde spadla přeháňka) → Livigno → **Foscagno** → Bormio: přesun mezi dvěma městy se **čtyřmi** průsmyky nad 2 290 m.
4. **Výšky průsmyků.** Všech 44 má teď hodnotu přímo od autora. Faktografická kontrola výšek je v podstatě uzavřena; zbývá jen vědět, že u čtyř průsmyků se běžně publikují jiná čísla (tabulka v `03_PASSES.md`).
5. **Rok všech pěti výprav.** 2026, potvrzeno autorem.

### Stále k vyřešení — prioritně

6. ✅ **VYŘEŠENO autorem.** Věta o vinicích u Bormia byla zkratka — vinice byly **na cestě na východ k Meranu** (5. den), a v nížinách byly obecně všude sady a vinice. Pointa „ráno ledovce, večer vinice" tím zůstává platná, jen se přesouvá na správný den. Faktograficky sedí: Vinschgau jsou jablka, vinice od Merana na jih.
7. **T-02 — Andermatt vs. Hospental.** Text mluví o návratu do Andermattu, soubor se jmenuje `Hospental.md`. Obce jsou 3 km od sebe.
8. **Pořadí T-04 a T-05.** Obě padají do června–července; materiál je vůči sobě neumisťuje.
9. **Měsíce čtyř výprav.** T-03 je odvozeno (14.–16. 8.), u ostatních zbývá měsíc a víkend.

10. **Náročnost T-04 dnů 1 a 3.** Zrekonstruovaný první den vychází řádově na 200 km a přes 4 000 m; třetí den vyžaduje mezi rampami Stelvia spojku Santa Maria – Müstair – Mals – Prato. Obojí je možné, ale než se napíše, jak dlouhý ten den byl, chtěl bych skutečná čísla.

### Nové otázky, které CSV otevřelo

11. **Col de Sarenne (1 999 m)** — jediná zbývající nejasnost tohoto typu. — padá na D2 nebo D4 výpravy T-05, protože Alpe d'Huez byl vyjet dvakrát. Nastejno pravděpodobné, s mírnou preferencí D4 (Galibier → Lautaret → Le Freney → Sarenne → Alpe d'Huez → Grenoble je routovací logikou přirozenější).
12. ✅ **Přeháňka na T-04 den 2 — VYŘEŠENO.** Autor potvrdil, že přejezdem do Itálie byla Forcola di Livigno a déšť spadl na sjezdu z ní. V kapitole je to už normální text, ne editorská poznámka.
13. **Vercors bez sedla.** Poslední den T-05 nemá v CSV žádný průsmyk. Buď autor žádné sedlo nepřejel, nebo je to důsledek toho, že CSV obsahuje jen hlavní průsmyky.
14. **E-maily trasy systematicky podhodnocují.** Osm průsmyků, které autor přejel a nenapsal o nich. Dva dny, které v e-mailu vypadají řídce, byly ve skutečnosti těžké: T-04 den 2 (tři průsmyky nad 2 290 m, ne jeden) a T-03 den 2 (šest průsmyků, ne pět). Při psaní kapitol je nutné vycházet z CSV, ne z e-mailu.

### Opraveno v v2.0

**Autorovo pořadí Sellarondy je správné.** „Campolongo, Gardena, Sella a Pordoi" je platný okruh z Arabby. V v1.0 jsem zde chybně tvrdil, že jezditelné není, a odvozoval z toho otevřenou otázku. Tvrzení bylo mylné a otázka zrušena.

### Editorské / faktografické (neblokující)

15. **Monte Zoncolan, Sella di Razzo a Sella Ciampigotto leží v Karnských Alpách**, ne v Dolomitech. Vyřešit formulačně jako cestu do Dolomit, ne jako faktickou chybu.
16. **Vercors je regionální přírodní park** (Parc naturel régional du Vercors), autor píše „národní park".
17. **Croix de Fer a Glandon.** Vrcholy jsou od sebe ~2,5 km a spojuje je křižovatka pod Croix de Fer. Sekvence v T-05 d2 je standardní a soudržná — jen si vyžádá jednu vysvětlující větu pro čtenáře.
18. **Pravopis:** `timmeljoch` → **Timmelsjoch** (it. Passo del Rombo). Sjednotit napříč projektem a přejmenovat soubor.
19. **Rozsah archivu.** T-05 mluví o tom, že se výprava „zařadil mezi moje nejlepší cyklistické dovolené **vůbec**" (mužský rod dle zdroje), což naznačuje výpravy z předchozích let, k nimž ve složce zdrojový text není.

---

## 12. AUTHOR INPUT NEEDED

Otázky 1 a 4 z v1.0 jsou vyřešené (rok potvrzen, šestý průsmyk = Tremola). Pět nových, seřazených podle toho, co odemknou.

1. **Měsíce.** U kterých měsíců a víkendů proběhly Timmelsjoch, Andermatt, Bormio a Francie? A jelo se Bormio před Francií, nebo po ní? Rok už mám; chybí jen tohle, aby byla osa hotová. A ještě jedna kontrola: byla dolomitská výprava opravdu **14.–16. srpna** (svátek Ferragosto v sobotu)?

2. **Bormio a vinice.** Píšeš, že jsi byl ráno mezi ledovci nad 2 700 m a večer „seděl s Bormiu obklopeném vinicemi". Bormio vinicemi obklopené není — bylo to Merano, nebo Bolzano, poslední den? Je to pointa, na které stojí celá kapitola, takže potřebuju vědět, které město to bylo a co si z toho večera pamatuješ.

3. **Gavia.** Píšeš, že „právě tady jsem si asi nejvíc uvědomil, jakou svobodu člověku dává cestování na kole o samotě". Byl to konkrétní moment — zastavení, výhled, ticho, prázdná silnice — nebo postupný pocit během celého stoupání? Emocionální vrchol nejsilnější kapitoly a nejkonkrétnější místo v archivu, kde říkáš, co pro tebe sólo znamená.

4. **Osm nenapsaných průsmyků.** V CSV je osm sedel, o kterých v e-mailech není ani slovo: Maloja, Forcola di Livigno, Foscagno, Sella di Razzo, Passo Tre Croci, Col du Chaussy, Col Luitel, Col de Sarenne. Zajímá mě dvojí. Za prvé prakticky: patří **Sarenne** ke druhému, nebo ke čtvrtému dni ve Francii? Za druhé podstatněji: **byly to pro tebe jen spojovací kopce, nebo si na některý z nich pamatuješ něco, co se do e-mailu nevešlo?** Zvlášť u Forcoly di Livigno, protože právě tam tě podle všeho zastihl ten déšť.

5. **Švýcarský víkend.** Nejlepší struktura, nejméně detailu (438 slov na šest průsmyků). Tři věci: čím se Furka lišila od Sustenu a Grimselu, že tě bavila „asi nejvíc"? Jak to bylo jet Tremolu na silničním kole? A jaké to bylo, když na Gotthardu brzy ráno „skoro nikdo nebyl"?

**Plus jedna technická prosba, ne otázka:** export pěti Google Photos albumů do `Cycling/photos/T-01` … `T-05` (Google Takeout, originální kvalita, aby zůstala metadata), a jestli existují, i GPX/Strava/Garmin záznamy. Doplní vzdálenosti a převýšení čtyř výprav a většinu vizuálního detailu.

---

## 13. Doporučené další kroky

| # | Krok | Kdo | Blokuje |
|---|---|---|---|
| 1 | Odpovědi na 5 otázek v §12 | autor | kapitoly 3 a 6 |
| 2 | Export fotoalb do `Cycling/photos/T-0X/` + případné GPX | autor | fotokurátorství, vzdálenosti, zařazení Sarenne |
| 3 | Potvrzení struktury (doporučeno varianta C, Dolomity jako závěr) | autor | číslování kapitol |
| 4 | Pilotní kapitola: **„Stelvio třikrát" (T-04)** jako první plný draft | agent | — |
| 5 | Vyhodnocení pilotní kapitoly autorem — hlas, délka, míra faktografie | autor | zbývající kapitoly |
| 6 | Vsuvky (Únikové pruhy, Tremola, Sám) — lze psát paralelně bez autorského vstupu | agent | — |
| 7 | Sestavení `04_PHOTO_INDEX.md` z EXIF | agent | blokováno krokem 2 |
| 8 | Dohledání etap Tour de France 2026 (Chambéry, Galibier) → datace T-05 na den | agent | jen na pokyn autora |

**Návrh.** Pilotní kapitolu T-04 lze začít hned po odpovědi na otázku 2 — a je teď v lepším stavu než ve v1.0, protože CSV doplnilo tři chybějící průsmyky prvních dvou dnů a zúžilo místo té jediné přeháňky na jednu silnici. Z pěti dnů, z nichž dva vypadaly jako přejezdové, jsou teď dny s obsahem.

**Poznámka k prioritám.** Před dodáním CSV byl fotoarchiv jednoznačně první prioritou, protože blokoval datování. Teď je první prioritou §12 — konkrétně otázky 2 a 4, které jsou obě krátké a obě odemykají psaní.

---

**Status projektu: DISCOVERY v2.0 — faktografie průsmyků a rok uzavřeny, čeká se na §12 a fotoarchiv.**
Žádná kapitola dosud nebyla psána. Zdrojové dokumenty nebyly nijak měněny.
