# Egino — CK3 ID 37502

## Aktualizacja ekranowa — hrabia Egino II z Zollern, ród Urach

**POTWIERDZONE_SCREEN:** `Zrzut ekranu 2026-10-10 205019.png` (załącznik `file_0000000064748210bf3bf50aee69c7d6`), portret `Barbershop_Count_Burkhard_of_Hohenberg_1066_10_20_0003.png` (załącznik `file_000000007e5c82468994f684af200535`). Tożsamość połączona z istniejącym ID **37502** dzięki zgodnemu imieniu, wiekowi, tytułowi, rodowi Urach i portretowi. **Data 20 X 1066** pochodzi wyłącznie z nazwy eksportu Barbershop; ekran karty nie zawiera widocznego datownika.

- Interfejs: **Count Egino II of Zollern**, **21 lat**; **Neighboring Fellow Vassal**; herb domu **Urach**; **County of Zollern**, 1 tytuł, **Feudal Realm Vassal**. To są dane z ekranu, nie gwarancja trwałości stanu politycznego.
- **POTWIERDZONE_SCREEN:** profil zbiorczy **Brute**, odrębny od indywidualnych traitów. Potwierdzone w save z 18 IX: `honest`, `patient`, `sadistic`, `education_learning_1`. Etykieta Brute nie dodaje piątej cechy.
- Kultura **Swabian**, obrządek **Roman Rite**; wartości końcowe umiejętności z ekranu: DIP **6**, MAR **10**, STE **8**, INT **3**, LEA **15**, PRO **6**; bazowy zapis `skill=[5,10,7,4,9,4]` z 18 IX pozostaje nietknięty.
- Zasoby i liczby z ekranu: złoto **70**, prestiż **355**, pobożność **203**, wojsko **352**, **Family 4**, **Children 0**, **Siblings 2**, **Courtiers 7**, **Subjects 1**. Obraz pokazuje też rodzica, dziadka i portrety rodzeństwa, ale nie nadaje im bezspornych ID.
- Prawy panel wskazuje `Primary Heir` i `Liege`; nie należy samodzielnie identyfikować widocznych dziedzica i rodzeństwa tylko po portrecie. Na ekranie znajdują się ujemne liczby przy portretach, których dokładna semantyka wymaga tooltipów.
- Data wpisana w nazwie portretu jest późniejsza niż bazowy save 18 IX; nie aktualizować automatycznie danych zapisu na podstawie obserwacji bez powiązania czasowego.

**Pliki uzupełniające:** [wygląd](wyglad.md) · [charakter do narracji](profil_narracyjny.md) · [źródła i referencje](zrodla.md). Oryginalne PNG pozostają załącznikami rozmowy, a nie binarnymi plikami GitHub. Historyczne partie tej karty o braku portretu opisują stan sprzed aktualizacji.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/37502`; imię `Egino`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1045.1.1`.

**OBLICZONE:** wiek **21** na 18 IX 1066, z daty urodzenia.

- Dom: ID **4228**, nazwa/klucz `dynn_Urach`; dynastia ID **4228**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `40`, `culture_template=swabian`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[5, 10, 7, 4, 9, 4]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `honest` [indeks 62], `patient` [indeks 57], `sadistic` [indeks 77], `education_learning_1` [indeks 20].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `c_zollern 1235` — nazwa zapisana: Zollern; `b_zollern 1236` — nazwa zapisana: Zollern.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Kontrakt **8405**: wasal [Egino 37502](../37502/karta.md) → senior [Rudolf 33226](../33226/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Lista `playable_data/knights`: [Gebhard 37715](../37715/karta.md), [Bernhard 45253](../45253/karta.md), [Michael 53579](../53579/karta.md).
- Pierwsze wpisy `landed_data/succession`: [Gebhard 37715](../37715/karta.md), [Kuno 38081](../38081/karta.md), ID 33050 — własny rekord poza zakresem, ID 39815 — własny rekord poza zakresem, ID 40518 — własny rekord poza zakresem, ID 41037 — własny rekord poza zakresem, ID 33979 — własny rekord poza zakresem, ID 33051 — własny rekord poza zakresem. Łącznie 19 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=68`, `income=1.8941`; `current_strength=374`, `strength=374`, `levy=171`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice rozpoznani przez odwrotne powiązanie `family_data/child` w rejestrach żywych i zmarłych: [Egino 29144](../29144/karta.md). Nie zgadywano drugiego rodzica przy jednym wpisie.
- Brak własnych wpisów `family_data`; nie dowodzi stanu wolnego ani bezdzietności.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)

<details>
<summary>Wcześniejsze obserwacje i etap rozpoznania — zachowane historycznie</summary>

# Egino — CK3 ID 37502
**Obserwacja:** 1066-09-16. **Źródło:** `von_Hohenzollern.ck3` SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.

## Potwierdzone
- Imię odczytane z rekordu postaci o numerze 37502: **Egino**.
- Powiązanie z aktualnym posiadaniem tytułu, odczytane z rekordów tytułów: **c_zollern (1235); b_zollern (1236)**.
- Dalsze związki rodzinne i przynależność do dworu Burkharda: **NIEUSTALONE**. Nie wpisywać do jego rady ani rycerzy bez osobnego potwierdzenia.

## Dane osobowe
Datę urodzenia, wartości umiejętności i traity odczytano — patrz sekcja danych personalnych. Relacje, szczegółowe modyfikatory i nieodczytane pola pozostają **NIEUSTALONE**.

## Screenshoty
Brak zatwierdzonego portretu. Planowane źródło: `06_MATERIALY_ZRODLOWE/zrzuty_ekranu/1066-09-16_postac_37502_*.png` (jeszcze nie utworzono). Docelowe pola: data świata, panel, odnośnik, status weryfikacji, Barber Shop.

## Powiązania i aktualizacje
[Indeks postaci](../indeks_postaci.md). Dane tej karty są datowane; nowe screeny dopisywać jako obserwacje, a nie bez daty nadpisywać dawne wartości.

## Obserwacja aktualizacyjna — 1066-09-18
**Źródło:** `von_Hohenzollern.ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` (wersja 1.20.0.4). Wcześniejszy stan z 1066-09-16 pozostaje historycznym źródłem.

**POTWIERDZONE_SAVE:** Rekord ID **37502**, imię **Egino**; właściciel tytułu w rekordach: `c_zollern 1235; b_zollern 1236`. Surowy ID domu w polu `0x2e5e`: **4228**. Pole datowe `0x27e9`: **52954200** (znaczenie biograficzne NIEUSTALONE). Surowe liczby z `0x29a5`: **[5,10,7,4,9,4]** (niezweryfikowana kolejność umiejętności).

**NIEUSTALONE:** dokładna data urodzenia, rodzice, małżeństwa, dzieci, kultura, wiara, obrządek, przyporządkowanie umiejętności, cechy/traits, urzędy, relacje, roszczenia i wygląd. Potrzebne: aktualny screen karty postaci, Family/Relations, tooltipy cech i osobna referencja Barber Shop. Tytuł nie dowodzi przebywania na dworze Burkharda.

## Dane personalne — odczyt pól 1066-09-16

**POTWIERDZONE_SAVE:** surowe wartości i numery traitów powiązane z zapisaną w pliku tabelą `traits_lookup`. Identyfikacja pól oparta o schemat Jomini CK3.

- Data urodzenia: **1045-01-01** (surowy token `0x27e9`).
- Kultura — ID: **40** (nazwa wymaga mapy kultur).
- Wiara/obrządek: surowe pole `0x3e5a=0` — nazwa i znaczenie **NIEUSTALONE**.
- Dom dynastyczny — ID: **4228** (nazwa do ustalenia).
- Umiejętności, kolejno: dyplomacja / wojskowość / zarządzanie / intryga / nauka / sprawność: **5 / 10 / 7 / 4 / 9 / 4**.
- Traity: `honest` (ID 62), `patient` (ID 57), `sadistic` (ID 77), `education_learning_1` (ID 20).
- Screenshot/portret: **BRAK**. W przyszłości wiązać obraz z CK3 ID 37502 i datą gry.

</details>
