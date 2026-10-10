# Burkhard — CK3 ID 62634
**Data stanu gry:** 1066-09-16 • **Źródło:** `von_Hohenzollern.ck3`, SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.
**Status:** POTWIERDZONE_SAVE dla numeru postaci, imienia, powiązań z tytułami i domem. Pola nieopisane semantycznie oznaczono jako NIEUSTALONE.

## Tożsamość
- ID postaci: **62634** (rekord `gamestate`, offset 34509331).
- Imię w rekordzie: **Burkhard** (pole binarne `0x2755`).
- Zapis w metadanych: **Count Burkhard**.
- Dom dynastyczny: **von Hohenzollern**, ID domu **12843**; rekord domu w offset 8464638 zawiera nazwę i referencję do tej postaci 62634; postać odwołuje się do ID 12843 (pole `0x2e5e`).
- Wersja gry w metadanych: **1.20.0.4**.
- Data urodzenia **1050-07-27**, potwierdzona odczytem pola urodzenia zgodnym ze schematem gamestate; surowy token `0x27e9`.
- Identyfikator kultury `40` i pole religijne `0` odczytane, ale ich nazwy oraz dodatkowe mechaniki pozostają nieustalone. Płeć, zdrowie i interpretacja obrządku wymagają odrębnego potwierdzenia.
## Tytuły i domena
- **County of Hohenberg**, klucz `c_hohenberg`, ID tytułu **1239** — rekord tytułu wskazuje posiadacza **62634** (pole `0x27d7`).
- **Barony of Hohenberg**, klucz `b_hohenberg`, ID **1240** — również posiadacz **62634**.
- Powiązanie hrabstwa z księstwem Szwabii (ID **1216**) w strukturze tytułów: POTWIERDZONE_SAVE; interpretacja konkretnych rodzajów zależności wymaga pełnego słownika.
- W hrabstwie Hohenberg jest też tytuł `b_rottweil` (ID **1241**), posiadacz **Konrad**, ID **45254**; to nie dowodzi przynależności do osobistej domeny Burkharda.
- **Domena osobista** w bloku `landed_data` (surowe pole `0x27e6`): `[1239,1240]` = hrabstwo i baronia Hohenberg. **Stolica**: pole `0x2f87=1240` wskazuje baronię Hohenberg (identyfikacja funkcji tego pola na podstawie struktury i analogii; WNIOSEK).
- **Ustrój:** `feudal_government` (wartość pola `0x2ef7` w landed_data).
- **Prawa zapisane w landed_data:** `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law` (blok `0x2f17`).
- **Powiązanie zwierzchnie:** pole `0x2d67` zawiera `[33226]` = Rudolf, władca Szwabii; funkcja tego pola do pełnego potwierdzenia.
- Skarbiec, dochód, kontrola, budynki, wojsko, wojska zawodowe, prestiż, pobożność i roszczenia: NIEUSTALONE.
## Cechy i umiejętności
- Pole `0x29a5` odpowiada sześciu umiejętnościom w standardowej kolejności CK3: dyplomacja **3**, wojskowość **5**, zarządzanie **4**, intryga **5**, nauka **0**, sprawność **8**. Zob. sekcja danych personalnych.
- Pozostałe zidentyfikowane surowe pola w [raporcie technicznym](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_ck3_2026-10-10.md).
- Lista pięciu traitów **z własnego rekordu postaci** odszyfrowana przez wewnętrzną tabelę `traits_lookup`; patrz sekcja danych personalnych. Szczegółowe efekty modyfikatorów i doświadczenie modowe nadal NIEUSTALONE.
## Rodzina, rada, dwór i rycerze
- **Potwierdzone zadania rady:** sprawy zagraniczne — [Notker 62636](../62636/karta.md); pobór podatków — [Gerhard 62635](../62635/karta.md); rozbijanie spisków — [Konrad 45254](../45254/karta.md); stosunki religijne — [Helferich 58415](../58415/karta.md). Piąte zadanie `task_organize_levies` występuje w zapisach bez przypisanego ID wykonawcy: **NIEUSTALONE**, nie nazywać wolnym urzędem bez screena.
- **Rycerze odczytani z playable_data (`0x30f2`):** [Gerhard 62635](../62635/karta.md) i [Gunzelin 65692](../65692/karta.md). Jest to interpretacja pola jako listy rycerzy zgodna z zewnętrznym schematem struktury CK3; wymagane potwierdzenie z interfejsu.
- Inni członkowie rodziny, dworzanie, goście i dowódcy: **NIEUSTALONE**. Nie przypisywać na podstawie bliskości ID.
- Osobny [indeks otoczenia](../../04_OTOCZENIE_WLADCY/indeks_dworu.md).
## Screenshot i referencja wyglądu
- Aktualny zatwierdzony screenshot: **BRAK**.
- Pola do uzupełnienia: `screenshot_postaci`, `data_screena_w_grze`, `panel`, `referencja_Barber_Shop`, `plik_repozytorium`.
- Planowane miejsce: `06_MATERIALY_ZRODLOWE/zrzuty_ekranu/1066-09-16_postac_62634_*.png` (ścieżka proponowana, plik jeszcze NIE istnieje).
- Nie odtwarzać wyglądu wyłącznie z binarnych genów lub nazwy kultury.
## Powiązania
[Hohenberg](../../03_TERYTORIA/HRABSTWA/1239/karta.md) · [Szwabia](../../03_TERYTORIA/KSIESTWA/1216/karta.md) · [Indeks postaci](../indeks_postaci.md).

## Obserwacja aktualizacyjna — 1066-09-18
**Źródło:** `von_Hohenzollern.ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` (wersja 1.20.0.4). Wcześniejszy stan z 1066-09-16 pozostaje historycznym źródłem.

**POTWIERDZONE_SAVE:** Rekord ID **62634**, imię **Burkhard**; właściciel tytułu w rekordach: `c_hohenberg 1239; b_hohenberg 1240`. Surowy ID domu w polu `0x2e5e`: **12843**. Pole datowe `0x27e9`: **53002968** (znaczenie biograficzne NIEUSTALONE). Surowe liczby z `0x29a5`: **[3,5,4,5,0,8]** (niezweryfikowana kolejność umiejętności).

**NIEUSTALONE:** dokładna data urodzenia, rodzice, małżeństwa, dzieci, kultura, wiara, obrządek, przyporządkowanie umiejętności, cechy/traits, urzędy, relacje, roszczenia i wygląd. Potrzebne: aktualny screen karty postaci, Family/Relations, tooltipy cech i osobna referencja Barber Shop. Tytuł nie dowodzi przebywania na dworze Burkharda.

## Dane personalne — odczyt pól 1066-09-16

**POTWIERDZONE_SAVE:** identyfikatory, surowe wartości, przypisanie numerów traitów do zapisanej w pliku tabeli `traits_lookup` (419 pozycji). Identyfikacja strukturalna `birth`, `skill`, `culture`, `faith`, `dynasty_house` jest wsparta schematem Jomini CK3; wartości nadają się do późniejszego porównania z interfejsem.

- **Data urodzenia:** 1050-07-27 (surowy klucz `0x27e9`, dekodowanie daty Jomini).
- **Kultura — ID:** 40 (nazwy nie ustalono bez mapy kultur).
- **Wiara/obrządek:** surowe pole `0x3e5a` = 0; klasyfikacja wartości i nazwa wiary **NIEUSTALONE**.
- **Dom dynastyczny — ID:** 12843.
- **Umiejętności** (dyplomacja, wojskowość, zarządzanie, intryga, nauka, sprawność): **3 / 5 / 4 / 5 / 0 / 8**; surowy klucz `0x29a5`.
- **Cechy osobowości, wykształcenia i inne**, dokładne angielskie klucze z tablicy zapisanej w save'ie: `ambitious` (trait #67); `diligent` (trait #54); `patient` (trait #57); `education_stewardship_3` (trait #12); `intellect_good_2` (trait #152). Surowy klucz `0x0648`.
- Polska interpretacja nazwy lub konkretnego efektu modyfikatora jest odrębnym etapem; liczby i angielskie klucze zachowano dosłownie.

