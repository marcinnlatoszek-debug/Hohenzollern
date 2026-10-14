# CK3 — weryfikacja pełnego save'a z 18 października 1073

**Status:** ZATWIERDZONE przez użytkownika 14 X 2026 po przedstawieniu raportu pogłębionej analizy.  
**Nowy punkt świata:** **18 października 1073**.  
**Plik główny:** `von_Hohenzollern(20261014-200855).ck3`.  
**Duplikat:** `von_Hohenzollern(20261014-201208).ck3` — identyczny bajtowo według porównania SHA-256.  
**Poprzedni zatwierdzony pełny punkt:** 12 listopada 1070, `von_Hohenzollern(10).ck3`; różnica **1070 dni gry**.  
**Wersja:** CK3 1.20.1. **Konfiguracja:** identyczna kolejność 19 modów i 10 DLC; 307-elementowa `traits_lookup` identyczna w obu porównanych save'ach.  
**SHA-256 nowego pliku:** `07e38afe8fb3d12149c08ead7beec29f6874a8db1c7ae0028336521bf18ee7b0`.  
**Rozmiar nowego pliku:** 21 866 082 B; `gamestate` po rozpakowaniu: 120 982 518 B.  
**Podstawa:** pogłębiona analiza binarnego zapisu CK3 (format Jomini), porównanie z raportem [12 XI 1070](CK3_1070-11-12_weryfikacja.md) oraz wcześniejszymi zatwierdzonymi ekranami zapisanymi w [osi 1068–1073](../../campaign/Os_czasu_Zollern_1068-1070.md).

## 1. Zmiany rozstrzygnięte bezpośrednio przez save

| Data / stan | Potwierdzenie | Zakres dowodu |
|---|---|---|
| **7 VII 1071** | Zgon Leopolda (81336), syna Burkharda i Hedwig; rekord pośmiertny z datą | `sickly` było cechą zdrowotną, **przyczyna śmierci nieustalona** |
| **7 V 1072** | `battle_won_memory` Burkharda (66952) przeciw Adelheid (31878), zgodne z pamięcią przegranej | Zwycięstwo w bitwie, **nie** koniec wojny; konkretni dowódcy nieustaleni |
| **17 I 1073** | `war_won`: zwycięzca 66952, przegrana 31878; `war_claimant=66952`, `war_attacker=66952`, `war_title=3437` (`c_hohenberg`), `war_memory_cb_claim` | Zakończenie **wojny roszczeniowej o Hohenberg** zwycięstwem Burkharda |
| **17 I 1073** | Historia `c_hohenberg`: posiadacz Adelheid (31878) → Burkhard (66952) | **Data przejęcia hrabstwa** |
| **18 X 1073** | `c_zollern`, `b_zollern`, `c_hohenberg`, `b_hohenberg`: posiadacz 66952 | Burkhard posiada oba hrabstwa i ich odczytane baronie; osobista domena powiększona |
| **18 X 1073** | Hedwig (41150) ma `pregnant`; lista dzieci rodziców nadal obejmuje 79306 i 81336 | **Ciąża trwa**; nie ma potwierdzonego nowego porodu |
| **18 X 1073** | Starszy syn Burkhard (79306) ma `curious` | Cecha dziecięca; data jej nabycia nieustalona |
| **18 X 1073** | Rudolf (35525) posiada `d_swabia`; Heinrich (41198) `e_hre` | Brak zmiany seniora i cesarza |
| **18 X 1073** | Zadanie Radbota (66953) `task_increase_control`, wcześniej `task_organize_levies` | Zmiana **zadania**, niepotwierdzona data ani motyw |
| **18 X 1073** | `b_rottweil`: Wenzel (44447), poprzednio Lothar (48230) | Zmiana lokalnego posiadacza **w nieustalonej dacie** |

**Uwaga o 17 I 1073:** starsze ekrany potwierdzały ukończenie oblężenia 16–17 I, okupację i schwytanie Kathariny; nowy save dodatkowo rozstrzyga zwycięstwo w wojnie i przekazanie tytułu **17 I**. Nie utożsamiać osobnej daty zdobycia fortyfikacji z datą przejścia hrabstwa, jeśli źródło jej nie podaje.

**Uwaga o Hupoldzie:** wcześniejsze ekrany potwierdzają jego dołączenie do wojny Burkharda i oblężenie Ebingen przez jego wojsko; brak dowodu, że dowodził bitwą 7 V. Pamięć `joined_allys_war` z 17 IV 1072 ma `ally=66952`, `enemy=31878`, ale osoba będąca właścicielem pamięci nie została jednoznacznie zidentyfikowana.

## 2. Rodzina i charakter

- **Burkhard 66952:** żyje, pozostaje mężem Hedwig, zachowuje `ambitious`, `diligent`, `patient`, `education_stewardship_3`, `lifestyle_gardener`, `intellect_good_2`. Nadal podlega Rudolfowi.
- **Hedwig 41150:** żyje; `impatient`, `arrogant`, `content` bez zmiany, dodatkowo `pregnant` na 18 X 1073.
- **Burkhard junior 79306:** żyje; odczyt `curious`; nie ustalono dokładnego dnia uzyskania cechy.
- **Leopold 81336:** ur. 21 IV 1070, zmarł **7 VII 1071**. `sickly` jest odczytanym stanem, **nie** dowodem przyczyny zgonu.
- **Rudolf 35525, Hupold III 32545, Heinrich 41198, Radbot 66953, Walpurga 66954, Amalie 66955, Meinhard 69353, Inga 69354, Gerlach 72054, Siegmund 76331, Bertha 43664, Matthias 61022:** aktywne rekordy żyjących postaci w nowym save; brak wykrytych zmian podstawowych cech osobowości u wymienionych dorosłych.

**Surowe umiejętności w save:** Burkhard 66952 `[3,5,4,5,0,8]` bez zmiany, Hedwig 41150 `[5,8,4,9,1,5]` bez zmiany; Burkhard junior z `[0,1,0,1,1,1]` na `[2,3,1,2,1,3]`. **To wartości bazowe struktury, nie wynikowe statystyki UI.** Nie nadpisywać liczb z ekranu.

## 3. Tytuły, polityka Szwabii i cesarstwa

| Tytuł | 12 XI 1070 | 18 X 1073 | Wniosek |
|---|---|---|---|
| `c_zollern` / `b_zollern` | Burkhard 66952 | Burkhard 66952 | ciągłość |
| **`c_hohenberg`** | Adelheid 31878 | **Burkhard 66952** | przejęcie 17 I 1073 |
| `b_hohenberg` | Adelheid 31878 | Burkhard 66952 | stan aktualny, bez odrębnej daty baronii |
| `b_rottweil` | Lothar 48230 | Wenzel 44447 | lokalna zmiana, data nieustalona |
| `c_urach` | Matthias 61022 | Matthias 61022 | ciągłość |
| `d_swabia` / `c_ulm` | Rudolf 35525 | Rudolf 35525 | ciągłość |
| `e_hre` | Heinrich 41198 | Heinrich 41198 | ciągłość |

Porównanie **31 bezpośrednich hrabstw Szwabii** wykazało jedną zmianę posiadacza hrabstwa: **Hohenberg**. Nie jest to dowód niezmienności wszystkich baronii, relacji osobistych, frakcji czy wojen w całym cesarstwie. Burkhard nie uzyskał niezależności ani tytułu książęcego.

Zapisane prawa: Burkhard — `confederate_partition`, `male_preference`, `crown_authority_0`; Rudolf — `confederate_partition`, `male_preference`, `crown_authority_1`; Heinrich — `confederate_partition`, `male_preference`, `crown_authority_0`. Nie ustalono pełnej kolejności spadkobierców dla wszystkich tytułów.

**Regencja:** zatwierdzony ekran z **3 VIII 1073** potwierdza rozpoczęcie regencji Burkharda nad Rudolfem. Nowy odczyt nie ustala, czy trwała jeszcze 18 X. Nie mieszać tej regencji z osobnym ekranem z 16 XI 1070.

## 4. Rada, zasoby, wojsko

| Postać | Złoto 12 XI 1070 → 18 X 1073 | Prestiż | Pobożność | Odczyt pola sił |
|---|---:|---:|---:|---:|
| Burkhard | 242,29 → **318,63** | 632,72 → **728,19** | 168,0 → **90,1** | 749 → **893** |
| Rudolf | 110,41 → **230,50** | 570,15 → **619,49** | 292,7 → **386,3** | 2435 → **2980** |
| Hupold III | 152,03 → **83,99** | 815,55 → **841,76** | −65,59 → **−75,49** | 1027 → **1127** |
| Heinrich | 445,13 → **162,15** | 126,67 → **402,29** | −119,41 → **−98,05** | 8111 → **9059** |

W nowym save Burkharda dwa dodatkowe pola wojskowe wskazują **936**; bez potwierdzenia znaczenia UI nie utożsamiać ich kategorycznie z liczebnością gotowych oddziałów. Zmiana złota nie dowodzi konkretnego źródła przychodów lub wydatków.

**Zadania rady:** Siegmund `task_foreign_affairs`, Gerlach `task_collect_taxes`, Radbot `task_increase_control` (zmiana względem `task_organize_levies`), Walpurga `task_disrupt_schemes`. Zadanie `task_fabricate_claim` występuje w kontekście Burkharda, ale **osoba aktualnego kapelana 18 X 1073 nie została jednoznacznie zmapowana**. Meinhard żyje; ekran z 13 VI 1073 pokazywał go przy roszczeniu do Nagoldgau. Nie potwierdzono aktualnej funkcji Ingi jako medyka na 18 X.

## 5. Granice odczytu i instrukcje dla fabuły

**Potwierdzone:** śmierć Leopolda, bitwa 7 V, zwycięstwo w wojnie i zdobycie Hohenbergu 17 I, ciąża Hedwig na 18 X, osobowości z tabeli `traits_lookup`, tytuły, wybrane zadania i zasoby.  
**NIEUSTALONE:** przyczyna śmierci Leopolda; data nabycia `curious`; tożsamość dowódców bitwy; pełna rekonstrukcja oblężenia; obecne frakcje i sojusze; wynikowe opinie; aktualny kapelan i medyk; obecny stan regencji; wynik ciąży; motywy zmiany zadania Radbota.

**Materiał fabularny, nie nowe wydarzenia:** (1) żałoba rodziny po Leopoldzie, bez dopisywania przyczyny śmierci; (2) długotrwała wojna o Hohenberg zakończona dopiero 17 I 1073, bez niepotwierdzonych dowódców i strat; (3) zarządzanie zdobytym hrabstwem, potwierdzone inspekcją 15 VI–8 VII 1073; (4) rosnące znaczenie Burkharda wewnątrz stabilnej hierarchii lennej; (5) ponowna ciąża Hedwig bez przesądzania porodu.

**Kolejne kroki badawcze:** screenshoty interfejsu z 18 X 1073 dla rady, regencji, frakcji, listy wojen, armii i opinii; weryfikacja szczegółów wojny bez przypisywania czynów na podstawie samych cech.

Powiązania: [oś 1070–1073](../../campaign/Os_czasu_Zollern_1070-1073.md) · [stan kampanii](../../01_KAMPANIA/stan_aktualny.md) · [indeks save'ów](../../06_MATERIALY_ZRODLOWE/indeks_saveow.md).
