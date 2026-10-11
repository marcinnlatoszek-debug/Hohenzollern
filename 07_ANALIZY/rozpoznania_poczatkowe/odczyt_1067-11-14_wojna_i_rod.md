# Nowy save — 14 XI 1067: wojna, wojska, ród i dwór

## Źródło i metoda

**POTWIERDZONE_SAVE:** `von_Hohenzollern(20261011-175242).ck3`, 13 952 962 B; **SHA-256** `a64b8551e487aef4fc3df4edc4d1909f51af590829ff4afe6c8e3d5370b66d6b`; CK3 **1.20.0.4**. Kontener `SAV0103`, ZIP `gamestate` **82 755 991 B**, CRC poprawne. Drugi upload `von_Hohenzollern(20261011-173838).ck3` ma identyczny rozmiar i SHA-256 (**alias bajtowy**, nie inna migawka).

**Data gry 14 XI 1067:** odczyt tokenu `meta_date` (surowy identyfikator `0x3157`) = **53154528**. Zdekodowano zgodnie z algorytmem `jomini::common::Date::from_binary`: 24 jednostki/dzień, 365 dni/rok, przesunięcie lat o 5000. `POTWIERDZONE_SAVE`; zapis jest **późniejszy** niż ekran z 13 XI. **Nie odczytano automatycznie każdego rekordu świata**: wykonano selektywną tokenizację Jomini, kontrole własnych rekordów postaci, aktywnej wojny 36, armii wskazanych dowódców i wybranych danych domeny.

**Uwaga do starszego źródła:** przy weryfikacji samodzielnie dostępnego `von_Hohenzollern(9).ck3` ten sam klucz `0x3157` miał wartość **53147688**, która według tego samego dekodera daje **2 II 1067**, nie dawniej wpisane w repozytorium **29 I 1067**. To rozbieżność historycznej metryki wymagająca osobnego uzgodnienia wszystkich porównań — **nie cofano fabuły ani nie zmieniano dat ślubu i innych odrębnie potwierdzonych zdarzeń**. Starsze porównania zasobów zachowują źródłowe oznaczenia i daty, do czasu osobnego audytu.

## Wojna o Szwabię — stan 14 XI

**POTWIERDZONE_SAVE:** konflikt **36** nadal znajduje się w bazie aktywnych wojen. Typ **`claim_cb`**, tytuł docelowy **1216** (księstwo Szwabii); `start_date=53149728` → **28 IV 1067**. Główny atakujący **Berthold 31865**; pretendent **Hermann 38078**; główny obrońca **Rudolf 33226**. Te role pokrywają się z wcześniejszym save z 7 VI.

**Odczytano następujących uczestników z list w obrębie wojny 36:**

| Strona | Postać CK3 ID | Surowa wartość daty w rekordzie | Data z dekodowania pola |
|---|---|---:|---|
| Atakujący | Berthold 31865 | 53149728 | 28 IV 1067 |
| Atakujący | Hermann 38078 | 53151024 | 21 VI 1067 |
| Broniący | Rudolf 33226 | 53149728 | 28 IV 1067 |
| Broniący | Ludwig 31145 | 53150040 | 11 V 1067 |
| Broniący | Burkhard 62634 | 53150136 | 15 V 1067 |
| Broniący | Egino II 37502 | 53154120 | 28 X 1067 |
| Broniący | Eberhard VI 31271 | 53154360 | 7 XI 1067 |
| Broniący | Kuno 34995 | 53154504 | 13 XI 1067 |

**Rozbieżność interpretacyjna:** powiadomienia z obrazów mają dni **26 VI** (Hermann), **2 XI** (Egino) i **12 XI** (Eberhard), za każdym razem **o pięć dni późniejsze** niż data pola wpisu uczestnika w binarnym rekordzie wojny. Nie ustalono semantyki tej różnicy (np. początku zaproszenia lub opóźnienia komunikatu). **Nie zamieniać ekranowej daty powiadomienia w datę technicznego pola**, ani odwrotnie; w fabule zachować ekranowe wiadomości, a pola save oddzielnie oznaczyć. Nowy udział **Kuna z Wirtembergii 34995** jest POTWIERDZONE_SAVE na 14 XI; jego pole daty ma **13 XI**, bez odpowiadającego zrzutu i bez znanej przyczyny przystąpienia.

Blok wojny 36 zawiera zapis o starciu z udziałem **Hermanna 38078 (strona atakująca)** i **Burkharda 62634 (broniący)** oraz pole prowincji `2759`; to źródłowe powiązanie z wcześniej pokazanymi ekranami `Battle of Hohenberg`. Znaczenia surowych znaczników rozstrzygnięcia nie zostały tu zweryfikowane: **nie ogłaszamy wyniku bitwy**. **Wojna aktywna 14 XI** nie oznacza, że oblężenie Baden również nadal trwa.

## Wojsko — odczytane zakresy 14 XI

Pola `landed_data/current_strength`, `strength`, `levy` (odpowiednio: aktualna siła, siła maksymalna w danej migawce, pospolite ruszenie) **nie są jednoznacznie liczbą żołnierzy w wystawionej armii**, dlatego przechowuje się je osobno od mapy i listy armii.

| Władca | ID | `current_strength` | `strength` | `levy` |
|---|---:|---:|---:|---:|
| Burkhard — Hohenberg | 62634 | **745** | 750 | 147 |
| Rudolf — Szwabia | 33226 | **868** | 872 | 669 |
| Egino II — Zollern | 37502 | **210** | 210 | 7 |
| Eberhard VI — Nellenburg | 31271 | **441** | 448 | 137 |
| Berthold — Karyntia | 31865 | **1190** | 1193 | 886 |

**Armie w strukturze `armies`:**

| ID armii | Dowódca z rekordu | ID jednostki armijnej | ID lokalizacji (bez ustalonej nazwy) |
|---|---|---:|---:|
| **388** | **Gerhard 62635** | 395 | 2759 |
| **355** | **Rudolf 33226** | 359 | 2768 |
| **33554661** | **Egino II 37502** | 33554644 | 2764 |
| **16777527** | **Berthold 31865** | 16777533 | 3099 |

Nie utożsamiać lokalizacji armii `2759` automatycznie z nazwą Hohenberg bez osobnego mapowania. **Nie potwierdzono odrębnej armii, której dowódcą byłby Eberhard 31271** w przejrzanych wpisach `commander`; posiada on wpis jednostki w domenie, ale dowódcą mógł być inny człowiek. Liczby ze wcześniejszych ekranów (np. 750 Hohenberg 28 IX, 1370 Villach we wrześniu) mają inne daty i zakresy.

## Postacie i rodzina

- **Burkhard 62634 i Irmengard 38789 są małżeństwem** — obustronne `family_data/primary_spouse` i `spouse`. W tych dwóch własnych blokach rodzinnych **nie ma wpisów `child`**. Nie dopisywać narodzin ani ciąży.
- **Burkhard** nadal ma domenę `[1239,1240]`, bazowe umiejętności `[3,5,4,5,0,8]` oraz sześć cech z tablicy zapisów (`ambitious`, `diligent`, `patient`, `education_stewardship_3`, `lifestyle_gardener`, `intellect_good_2`). W `playable_data` występuje indywidualne `tenet_ora_et_labora`, a `knights` zawiera `62635`, `65692`, `45254`.
- **Gunzelin von Nordgau 65692 żyje 14 XI 1067**, ma własny rekord `living/65692`. `court_data/employer=62634`, zadanie rady `16782045`; w pamięci postaci zachowano flagę `is_in_the_council`. Ekran 23 VIII dokumentuje zranienie; **nie ustalono tu poziomu zdrowia, daty wyleczenia ani wyniku leczenia**. Nie dopisywać śmierci ani pełnego ozdrowienia.
- **Gerhard 62635** figuruje nadal jako dowódca armii ID 388 w bieżącym save; niezależnie od nienazwanego dowódcy na ekranach bitwy. **Kuno 34995** dołącza do potwierdzonej listy wojennej, lecz nie przypisywać mu bez źródła osobistych motywów.

## Oś fabuły: tylko wydarzenia, nie sceny

**Do osi dopisać jako ostatnią potwierdzoną migawkę 14 XI 1067:** wojna o Szwabię trwa; Egino II i Eberhard VI występują jako uczestnicy po stronie Rudolfa i Burkharda, a **Kuno z Wirtembergii** jest również po tej stronie. **Gunzelin żyje mimo wcześniejszego ranienia**. Gerhard nadal prowadzi armię Hohenbergu. Nie tworzyć fikcyjnej sceny spotkania Burkharda z Eginem, Eberhardem lub Kuno, nie ogłaszać zdobycia Baden, wyniku bitwy ani pokoju.

[Chronologia](../../01_KAMPANIA/os_fabuly.md) · [Stan aktualny](../../01_KAMPANIA/stan_aktualny.md) · [Szczegółowy rejestr ekranów bitewnych](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/wojna_szwabska_1067_lipiec_listopad.md) · [Indeks zapisów](../../06_MATERIALY_ZRODLOWE/indeks_saveow.md).
