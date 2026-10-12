# Wojna o Szwabię — ekrany od lipca do listopada 1067

**Warstwa źródłowa do osi fabuły.** `POTWIERDZONE_SCREEN` dotyczy widocznych napisów i stanów interfejsu, `OBLICZONE` wyłącznie działań na liczbach, a `WNIOSEK` ostrożnych identyfikacji. Wszystkie poniższe PNG pozostają **załącznikami rozmowy** (nie są fizycznie przechowywane w GitHub). Daty w nazwach plików oznaczają czas rzeczywisty 11 X 2026, nie czas CK3.

**Powiązanie z kampanią:** potwierdzony w save `von_Hohenzollern(10).ck3` (7 VI 1067) konflikt o roszczenie Hermanna 38078 do Szwabii (wojna ID 36, początek 28 IV 1067): [raport](../../07_ANALIZY/rozpoznania_poczatkowe/zmiany_1067-01-29_do_1067-06-07.md). Burkhard 62634 dołączył po stronie księcia Rudolfa 33226 dnia 15 V. Nowsze screeny nie zastępują kompletnego późniejszego save’a.

## Zbiorczy wykaz wojsk do porównywania migawek

Poniższe wartości są **czasowo rozdzielone**. Nie sumować oddziałów z różnych dat ani nie łączyć ich liczebności z zasobami domeny w save’ie.

| Armia / formacja | Dzień i potwierdzony stan | Dowódca, tło, kierunek | Granica identyfikacji |
|---|---|---|---|
| **Hohenberg** | 16 V: zgromadzenie; 3 VI: **751**; 7 VI: armia ID 388, jednostka 395; 19 VII: **745**; 31 VII: **745** w bitwie; 23 VIII: **511** w bitwie; 28 IX: **750**; niedatowany dalszy screen: **744**; 7 XI: na mapie **738** | **Gerhard 62635** jako `commander` w save **7 VI**; 19 V marsz ku Wirtembergii | Dowodzenia Gerharda nie potwierdzono osobno w czasie bitwy, we wrześniu ani w listopadzie; nie wynika z nazwy armii obecność Burkharda |
| **Ulm** | 3 VI: **750**; 7 VI: armia ID 355, jednostka 359; 19 VII: **743** przy oblężeniu Baden; 28 IX: **722** | **Rudolf 33226** jako `commander` w save **7 VI**; 30 V kierunek Baden, 19 VII oblężenie w toku | Z końca września nie znamy wyniku oblężenia, a jego liczebności nie oznaczają końcowych strat |
| **Breisgau** | 1 VII: **463**; 31 VII: atakująca formacja pod Hohenbergiem **463** (WNIOSEK identyfikacji herbu); 23 VIII: **41** na panelu strony atakującej | 1 VII dowódca **Ernst**, marsz na Offenburg, prognoza 6 VII | Dowództwo Ernsta podczas bitwy nie zostało osobno potwierdzone; identyczna liczebność i herb to argument do identyfikacji, ale nie jednoznaczny klucz ID |
| **Schmalkalden** | 28 IX: **392**, w wykazie `Armies in this location` | Dowódca, właściciel, strona wojny **NIEUSTALONE** | Współobecność nie dowodzi sojuszu ani bezpośredniego udziału w bitwie |
| **Villach** | ok. 28 IX: **1370**; 7 XI: znacznik Villach **1357** | Tooltip: **Duke Berthold II**, osobiście dowodzi; **Grünningen**, ETA 2 X; wysoki stopień zgodności z Bertholdem **31865** | Planowane przybycie nie jest wykonanym marszem; nie utożsamiać tej armii z breisgauską formacją spod Hohenbergu |
| **Inne nieidentyfikowane znaczniki** | 7 XI: na mapie również **210** i **296**; 13 XI: m.in. **440** i **296** | Przynależność i dowódcy bez osobnych tooltipów **NIEUSTALONE** | Barwa lub herb nie dostarczają wystarczającej podstawy do utożsamiania wszystkich formacji |

**Podstawa dla wierszy z maja i czerwca:** `von_Hohenzollern(10).ck3`, data 7 VI 1067, [odczyt wojny 36, armii 355/388 i jednostek 359/395](../../07_ANALIZY/rozpoznania_poczatkowe/zmiany_1067-01-29_do_1067-06-07.md), oraz [screeny marszowe 15–30 V](wojna_i_armia_1067-05-15_16.md). `units/359.attached_to_this=[395]` na 7 VI wskazuje powiązanie jednostek Rudolfa i Burkharda, ale nie połączenie armii. W save **7 VI** odczytano `landed_data/current_strength=752` u Burkharda oraz regimenty `light_footmen=300`, `bowmen=300`, co jest **innym zakresem danych** niż wystawione oddziały pokazane na ekranach.

### Oś dyplomatyczna uczestników wojny

- **Berthold 31865** — główny atakujący, od 28 IV, w imieniu roszczenia jego syna **Hermanna 38078** do Szwabii.
- **Rudolf 33226** — główny obrońca; **Ludwig 31145** dołącza 11 V; **Burkhard 62634** dołącza **15 V** — wszystkie daty z `active_wars` na 7 VI.
- **Hermann 38078** — dołącza do wojny po stronie przeciwnej graczowi według powiadomienia **26 VI**; nie utożsamiać jego wcześniejszej roli roszczącego z tym późniejszym dniem wejścia.
- **Egino II 37502** — powiadomienie dołączenia **2 XI**, po stronie gracza.
- **Eberhard VI 31271** — powiadomienie dołączenia **12 XI**, po stronie gracza; wcześniejszy sojusz rodzinny z Burkhardem istniał już w 1066.

**Obecność obu nowych sojuszników nie oznacza znanej liczebności ich oddziałów ani ich obecności na ekranie bitwy.**

## Materiały z początku lipca — rozpoznanie powtórzeń

- `Zrzut ekranu 2026-10-11 191435(2).png`, `file_0000000052e88210857b5a3f8a189c29`, SHA-256 `729f6bb06b7dafe2037bc20c9e297b8ed9d9ffcaf432f9af913cf3bf58a996c3`. **Bajtowo identyczny** z wcześniej odnotowanym `191435(1).png`, nie nowa migawka. Potwierdza znane fakty z 1 VII: komunikat z **26 VI** o dołączeniu Hermanna do przeciwników; **Ernst** prowadzi armię Breisgau (463) w kierunku Offenburga, przewidywany termin **6 VII** — bez dowodu dotarcia.
- `Zrzut ekranu 2026-10-11 192007(1).png`, `file_00000000042082108f7f002fab936b62`, SHA-256 `4069b7ac4085e08df8d5d7c64eaca269ba2644ee2c70b04b200da7de6ca41061`. Powtórna **wizualna prezentacja** wcześniej opisanej sceny oblężenia Baden ok. **19 VII 1067** (roku na obrazie nie widać w całości). Armia Ulm 743 oblegających przeciw 632 obrońcom, poziom fortyfikacji 3; wynik pozostaje nieustalony. Nie ustanawiać drugiego oblężenia na podstawie kopii obrazu. Brak potwierdzenia identyczności bajtowej z oryginalnym `192007.png`.

## Bitwa pod Hohenbergiem — kolejne migawki

Cztery ekrany zawierają podpis **Battle of Hohenberg**. Strona **Defender** ma herb Hohenbergu; **Attacker** ma herb w barwach poprzednio widocznej armii Breisgau (przypisanie nazwy sił po herbie: WNIOSEK; dowódca strony atakującej w chwili bitwy nieidentyfikowany w tooltipie). Napis **Reinforcements: ... nearby** oznacza pobliskie posiłki w interfejsie, a nie oddziały już dodane do licznika armii ani potwierdzenie ich przybycia.

| Data widoczna na ekranie | Broniący — aktualna liczba na panelu | Atakujący — aktualna liczba na panelu | Dwa mniejsze liczniki pod stanem głównym | Źródło |
|---|---:|---:|---|---|
| **31 VII 1067** | **745** | **463** | 0 / 0 | `192111(2).png` |
| **6 VIII 1067** | **686** | **367** | 52 / 90 | `192249(1).png` |
| **12 VIII 1067** | **598** | **218** | 110 / 186 | `192308(1).png` |
| **23 VIII 1067** | **511** | **41** | 165 / 302 | `192331(1).png` |

**To kolejne stany tej samej nazwanej bitwy, nie cztery odrębne bitwy.** Dokładna data jej rozpoczęcia i zakończenia oraz oficjalny wynik **NIEUSTALONE**; ekran 31 VII dowodzi trwania bitwy tego dnia, nie że wtedy się zaczęła. Liczb z kolumny nie wolno nazywać automatycznie poległymi ani wnioskować wyłącznie z różnicy liczebności o całkowitych stratach, ucieczce lub zwycięstwie. Mniejsze liczniki przepisano bez niezależnie potwierdzonej interpretacji ikon.

**Skład wojsk na ekranie 31 VII:** strona Hohenbergu pokazuje pospolite ruszenie 148, `Light Footmen` 298, `Bowmen` 297 i 2 rycerzy; strona atakująca pospolite ruszenie 261, `Pikemen` 200 i 2 rycerzy. Są to wskazania interfejsu tego dnia, nie stany całej domeny w save’ie z 7 VI. Dalsze kadry pokazują zmieniające się liczebności tych samych rodzajów oddziałów. Nawet widoczna przewaga broniących nie stanowi potwierdzenia wygranej.

### Utrata zdolności bojowej Gunzelina — 23 VIII 1067

**POTWIERDZONE_SCREEN:** komunikat na ekranie bitwy 23 VIII 1067: `Our knight Gunzelin von Nordgau was wounded by an enemy soldier!`. Wiązać z [Gunzelinem 65692](../../02_POSTACIE/65692/karta.md), wcześniej potwierdzonym rycerzem i mistrzem intryg Burkharda. **Gunzelin został ranny w trakcie bitwy**. Nie dowodzi to jego śmierci, trwałego kalectwa, sposobu leczenia ani dokładnej chwili kontuzji przed widocznym powiadomieniem. Nie przenosić urazów na wcześniejsze daty.

### Pościg i podsumowanie zwycięstwa — 27–31 VIII 1067

**27 VIII:** ekran bitwy ogłasza **Victory**; Hohenberg jest w fazie **Pursuing**, strona przeciwna **Retreating**. To potwierdza wygraną i pościg, nie zamknięcie bitwy.

**31 VIII:** ekran końcowy zatytułowany **Slaughter at Hohenberg** podaje **Victory** i datę 31 August, 1067. Bilans z ikonami czaszki: Hohenberg **40 poległych**, strona atakująca **196 poległych**. Pozostałe stany na tym ekranie: 705 i 267; wyświetlone wartości początkowe: 745 i 463. Dodatkowo ekran przyznaje 21 Prestige, +7% War Score i +92 Contribution. Nie rozpisywać różnic z wcześniejszych paneli na inne kategorie strat bez źródła. Tytuł ekranu nie potwierdza strat wśród ludności cywilnej. Zwycięstwo bitwy nie oznacza zwycięstwa w wojnie 36, zdobycia Baden ani zawarcia pokoju.

**Powiadomienia widoczne 27 VIII:** 25 VIII kapelan dworski Helferich nie dał się przekonać; komunikat informuje o zresetowaniu zgromadzonego postępu i kolejnej próbie, więc plan trwał dalej. 22 VIII pojawia się nagłówek **Excommunication**, ale ekran nie ujawnia osoby ani sprawcy; nie przypisywać tego zdarzenia żadnej postaci.

**Metadane czterech obrazów:**

| Plik | SHA-256 | Załącznik |
|---|---|---|
| `Zrzut ekranu 2026-10-11 192111(2).png` | `d61deda51f1300f5539ad5d56522151a8cc7327632771fffff86fd19746a4bd5` | `file_000000002c008210a01c862ccb13d859` |
| `Zrzut ekranu 2026-10-11 192249(1).png` | `6f308ab373d4b198e07ea7c09cee5f893344ff6468f76d6672693da13bdd57b3` | `file_000000001f8c820a8627488f291094f6` |
| `Zrzut ekranu 2026-10-11 192308(1).png` | `e97b8b230ea92c8482a2f814e453872a3286f8a43bf8ffe2f0741817a5455890` | `file_000000004d988210aa29d781214d200d` |
| `Zrzut ekranu 2026-10-11 192331(1).png` | `915365f23872acf6c3a40ab5b055d29410b4269ca3bf522f8dabaed84cbee4e9` | `file_00000000c8748243959467265b607ed7` |

## Armie jesienią 1067

**28 IX 1067:** osobny [panel zbiorczy trzech armii](obserwacja_armii_1067-09-28.md) potwierdza w jednej lokalizacji: Hohenberg **750**, Ulm **722**, Schmalkalden **392** (łączna suma tylko dla trzech wpisów **1864**, OBLICZONE). To stan punktowy; nie oznacza łącznej armii ani wspólnego dowództwa.

**Tożsamość osobnej armii 1370 — nowy ekran:**

- `Zrzut ekranu 2026-10-11 193332.png`, załącznik `file_00000000f978821090c0d8a8a5e3efa3`, SHA-256 `d540966fcf09486ef10ff19f8cb4943030f79876ec71015033f9ba49a8867b46`.
- Tooltip jednoznacznie nazywa **1st Army of Villach**, liczebność **1370**, **Commander: Duke Berthold II**, dopisek **Commanded by Ruler**, zaopatrzenie 100. Cel **Grünningen**, 4 dni do planowanego przybycia **2 X 1067**. Na tej podstawie datę bieżącego stanu można **wyliczyć na ok. 28 IX 1067**, choć kalendarz nie jest pokazany w tym kadrze. Nie twierdzić, że armia dotarła 2 X.
- Zestawienie z ustalonym księciem [Bertholdem 31865](../../02_POSTACIE/31865/karta.md), atakującym w wojnie o Szwabię, uzasadnia identyfikację **WNIOSEK o wysokiej zgodności**, ale sam kadr nie zawiera ID 31865.
- **Rozstrzygnięta wcześniejsza niewiadoma:** znacznik 1370 z ekranu 28 IX jest zgodny z armią Villach Bertholda, bez potrzeby zgadywania z samego herbu; nie dopisujemy, że te wojska walczyły w tej chwili.

`Zrzut ekranu 2026-10-11 193502.png`, załącznik `file_0000000029f481f4aabbd59b768024c3`, SHA-256 `eb7c9cca43bddcac13eafb0feb5a41314574132546cba8c4df6ca9e51f43e069`: znacznik **744** przy Hohenbergu oraz **1370** przy herbie armii Villach w sąsiednim miejscu. **Data gry niewidoczna**; nie należy automatycznie łączyć liczb z 28 IX ani uznawać tej mapy za dowód bitwy.

## Listopadowe dołączenia do wojny

**7 XI 1067** — `Zrzut ekranu 2026-10-11 193533.png`, załącznik `file_000000005e8482469a33d39d9ca3b0d2`, SHA-256 `3a7a47674eede6784c89a67698a2959b060778bdf2a36ebaeb9b83ac84208357`.
Powiadomienie **Ally Joins War: Count Egino II**, datowane **2 Nov**, mówi `has joined the War on your side`. **POTWIERDZONE_SCREEN:** od **2 XI 1067** [Egino II z Zollern 37502](../../02_POSTACIE/37502/karta.md) dołączył do strony gracza. Nie ma dowodu jego obecności na polu bitwy, motywów, osobistego pojednania rodów ani daty innego sojuszu.

**13 XI 1067** — `Zrzut ekranu 2026-10-11 193603.png`, załącznik `file_000000000b2c8246a6306663a20fb5f0`, SHA-256 `62193f12d0b73830f28b77106e22b64998fcece469b9518792bf5a8ae8acd942`.
Powiadomienie **Ally Joins War: Count Eberhard VI**, datowane **12 Nov**, mówi `has joined the War on your side`. **POTWIERDZONE_SCREEN:** od **12 XI 1067** [Eberhard VI von Nellenburg 31271](../../02_POSTACIE/31271/karta.md), ojciec Irmengard i teść Burkharda, dołączył do strony gracza. Jest to **uczestnictwo wojenne**, odrębne od wcześniejszego związku rodzinnego i wpisu `alliances` potwierdzonego już w save 20 X 1066. Nie datować samego powstania sojuszu na 12 XI.

Widoczne na mapach znaczniki (m.in. 738 Hohenberg, 1357 Villach, 210 i 296 na 7 XI; 440 i 296 na 13 XI) są **migawkami wojsk**. Nie podano pewnych dowódców i tożsamości wszystkich tych sił, nie dopisywać starć na podstawie ich współobecności. Obecność kolejnych komunikatów o przystąpieniu sprzymierzeńców nie oznacza wyniku wojny.

## Ograniczenia narracyjne

Zapisz jako **wydarzenia**: wojna o Szwabię, oblężenie Baden (lipcowa obserwacja), bitwa pod Hohenbergiem (potwierdzone fazy 31 VII–23 VIII), **ranienie Gunzelina**, obecność wojsk Bertholda na mapie i dołączenie Egina II oraz Eberharda VI. Postacie wprowadzać przez funkcję i relację; fakt dołączenia Egina może mieć znaczenie wobec rodzinnej historii Zollern, lecz **nie jest dowodem pojednania, negocjacji, zdrady lub zmiany jego charakteru**. Nie dopisano wygranej bitwy, śmierci rycerza, zajęcia Baden, odwrotu Bertholda ani końca wojny. Liczebności pozostają w rejestrze wojsk, a nie w prozie kroniki.

[Oś fabuły](../../01_KAMPANIA/os_fabuly.md) · [Stan i źródła](../../01_KAMPANIA/stan_aktualny.md) · [Indeks ekranów](../indeks_screenow.md).

## Nowy zapis — 14 XI 1067: potwierdzenie wojny i dowódców

**POTWIERDZONE_SAVE:** `von_Hohenzollern(20261011-175242).ck3` (alias o tym samym SHA-256 `20261011-173838`) przesuwa ostatni punkt mechaniczny kampanii do **14 XI 1067**. Konflikt ID **36** pozostaje aktywny. Po stronie obrońców: Rudolf 33226, Ludwig 31145, Burkhard 62634, Egino II 37502, Eberhard VI 31271 oraz **Kuno 34995**. Atakujący: Berthold 31865 i Hermann 38078. Na 14 XI **Gunzelin 65692 żyje**, choć był ranny w bitwie 23 VIII. Nie rozstrzygnięto na podstawie tego rekordu, czy bitwa została wygrana lub czy oblężenie Baden zakończone.

### Siły zapisane w domenach 14 XI (nie utożsamiać z armiami na mapie)

| Władca / ID | `current_strength` | `strength` | `levy` |
|---|---:|---:|---:|
| Burkhard 62634 | 745 | 750 | 147 |
| Rudolf 33226 | 868 | 872 | 669 |
| Egino II 37502 | 210 | 210 | 7 |
| Eberhard VI 31271 | 441 | 448 | 137 |
| Berthold 31865 | 1190 | 1193 | 886 |

W nowych blokach armii zapisano **Gerharda 62635 jako dowódcę armii Hohenbergu ID 388** (jednostka 395, lokalizacja ID 2759); **Rudolfa 33226 jako dowódcę armii 355** (jednostka 359, lokalizacja ID 2768); **Egina II 37502 jako dowódcę armii 33554661** (jednostka 33554644, lokalizacja ID 2764); **Bertholda 31865 jako dowódcę armii 16777527** (jednostka 16777533, lokalizacja ID 3099). Nazwy prowincji z tych numerów NIEUSTALONE. Nie sumować obu stron wojny jako pełnych dostępnych sił, nie dodawać w nich automatycznie każdej armii z wrześniowego ekranu.

### Dni z pól uczestników a powiadomienia

**POTWIERDZONE_SAVE:** pole uczestnika Hermanna = 21 VI; Egina II = 28 X; Eberharda VI = 7 XI; Kuna = 13 XI. **POTWIERDZONE_SCREEN:** komunikaty mają daty 26 VI, 2 XI i 12 XI dla pierwszych trzech postaci. Występuje powtarzalne przesunięcie **pięciu dni**. Nie ustalono mechanicznej przyczyny tej różnicy, więc **daty komunikatu i daty technicznych pól pozostają osobnymi obserwacjami**. Dla Kuna brak własnego powiadomienia. 

[Źródło, identyfikatory, wersja i ograniczenia odczytu](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_1067-11-14_wojna_i_rod.md). Do osi wydarzeń trafia samo potwierdzenie jego uczestnictwa, nie domniemane okoliczności dołączenia ani rozkazy.


### Dodatkowe źródła zwycięstwa pod Hohenbergiem

| Ekran | Załącznik | SHA-256 | Ustalenie |
|---|---|---|---|
| `Zrzut ekranu 2026-10-11 192351.png` | `file_000000002df081f4abb32bdce7e9d125` | NIEZAPISANY | 27 VIII: zwycięstwo, pościg Hohenbergu, odwrót przeciwnika |
| `Zrzut ekranu 2026-10-11 192540.png` | `file_000000000b4081f4a4836ba550d40ad6` | `9c79077b9650f37f17bdbf95fb7cc324b57959a44efe332d6919493d11378870` | 31 VIII: końcowe podsumowanie zwycięstwa i bilans |
| `Zrzut ekranu 2026-10-11 192540(1).png` | `file_00000000e7548210b8429251019fa963` | `9c79077b9650f37f17bdbf95fb7cc324b57959a44efe332d6919493d11378870` | Bajtowy duplikat poprzedniego obrazu; ten sam wynik, bez nowego wydarzenia |

