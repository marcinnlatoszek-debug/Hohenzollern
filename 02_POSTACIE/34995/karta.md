# Kuno — CK3 ID 34995

## Aktualizacja ekranowa — Kuno z Wirtembergii

**OBSERVACJA_SCREEN (20 X 1066 według nazwy eksportu Barber Shop):** [źródła](zrodla.md), [wygląd](wyglad.md), [profil narracyjny](profil_narracyjny.md). Karta postaci wskazuje „Count Kuno of Württemberg”, wiek 31, „Fellow Vassal”, profil **Rational Absolver**, kulturę **Franconian** i obrządek **Roman Rite**.

Efektywne umiejętności z interfejsu DIP/MAR/STE/INT/LEA/PRO: **12/2/6/10/19/5**. Złoto 67, prestiż 515, pobożność 103, wojsko 244, dwoje dzieci, dziewięcioro dworzan, jeden poddany. Nie nadpisuje to danych starszego save’a z 18 IX. Cechy z tego zapisu: `forgiving`, `paranoid`, `patient`, `education_learning_4`; Rational Absolver jest osobną etykietą profilu, nie nowym traitem.

Dwa oryginalne screeny pozostają załącznikami rozmowy; ich nazwy i identyfikatory podano w [zrodla.md](zrodla.md). Wcześniejsze wzmianki o braku portretu są historyczne.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/34995`; imię `Kuno`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1035.1.1`.

**OBLICZONE:** wiek **31** na 18 IX 1066, z daty urodzenia.

- Dom: ID **4220**, nazwa/klucz `dynn_WU_rttemberg`; dynastia ID **4220**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `39`, `culture_template=franconian`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[10, 2, 5, 10, 8, 5]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `forgiving` [indeks 82], `paranoid` [indeks 73], `patient` [indeks 57], `education_learning_4` [indeks 23].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `c_wurttemberg 1227` — nazwa zapisana: Württemberg; `b_wurttemberg 1228` — nazwa zapisana: Stuttgart.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Kontrakt **8062**: wasal [Kuno 34995](../34995/karta.md) → senior [Rudolf 33226](../33226/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Kanclerz u [Rudolf 33226](../33226/karta.md); zadanie **9878**, `task_foreign_affairs`; potwierdzenie w `council_task_manager/database`.
- Pierwsze wpisy `landed_data/succession`: [Bruno 40316](../40316/karta.md), [Konrad 41253](../41253/karta.md). Łącznie 2 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=65`, `income=1.7983`; `current_strength=271`, `strength=271`, `levy=171`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice: nie znaleziono powiązania z wybranym ID w odczytanych tablicach dzieci; genealogii nie dopowiedziano.
- `child`: [Bruno 40316](../40316/karta.md), [Konrad 41253](../41253/karta.md).

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)

<details>
<summary>Wcześniejsze obserwacje i etap rozpoznania — zachowane historycznie</summary>

# Kuno — CK3 ID 34995
**Obserwacja:** 1066-09-16. **Źródło:** `von_Hohenzollern.ck3` SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.

## Potwierdzone
- Imię odczytane z rekordu postaci o numerze 34995: **Kuno**.
- Powiązanie z aktualnym posiadaniem tytułu, odczytane z rekordów tytułów: **c_wurttemberg (1227)**.
- Dalsze związki rodzinne i przynależność do dworu Burkharda: **NIEUSTALONE**. Nie wpisywać do jego rady ani rycerzy bez osobnego potwierdzenia.

## Dane osobowe
Datę urodzenia, wartości umiejętności i traity odczytano — patrz sekcja danych personalnych. Relacje, szczegółowe modyfikatory i nieodczytane pola pozostają **NIEUSTALONE**.

## Screenshoty
Brak zatwierdzonego portretu. Planowane źródło: `06_MATERIALY_ZRODLOWE/zrzuty_ekranu/1066-09-16_postac_34995_*.png` (jeszcze nie utworzono). Docelowe pola: data świata, panel, odnośnik, status weryfikacji, Barber Shop.

## Powiązania i aktualizacje
[Indeks postaci](../indeks_postaci.md). Dane tej karty są datowane; nowe screeny dopisywać jako obserwacje, a nie bez daty nadpisywać dawne wartości.

## Obserwacja aktualizacyjna — 1066-09-18
**Źródło:** `von_Hohenzollern.ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` (wersja 1.20.0.4). Wcześniejszy stan z 1066-09-16 pozostaje historycznym źródłem.

**POTWIERDZONE_SAVE:** Rekord ID **34995**, imię **Kuno**; właściciel tytułu w rekordach: `c_wurttemberg 1227`. Surowy ID domu w polu `0x2e5e`: **4220**. Pole datowe `0x27e9`: **52866600** (znaczenie biograficzne NIEUSTALONE). Surowe liczby z `0x29a5`: **[10,2,5,10,8,5]** (niezweryfikowana kolejność umiejętności).

**NIEUSTALONE:** dokładna data urodzenia, rodzice, małżeństwa, dzieci, kultura, wiara, obrządek, przyporządkowanie umiejętności, cechy/traits, urzędy, relacje, roszczenia i wygląd. Potrzebne: aktualny screen karty postaci, Family/Relations, tooltipy cech i osobna referencja Barber Shop. Tytuł nie dowodzi przebywania na dworze Burkharda.

## Dane personalne — odczyt pól 1066-09-16

**POTWIERDZONE_SAVE:** identyfikatory, surowe wartości, przypisanie numerów traitów do zapisanej w pliku tabeli `traits_lookup` (419 pozycji). Identyfikacja strukturalna `birth`, `skill`, `culture`, `faith`, `dynasty_house` jest wsparta schematem Jomini CK3; wartości nadają się do późniejszego porównania z interfejsem.

- **Data urodzenia:** 1035-01-01 (surowy klucz `0x27e9`, dekodowanie daty Jomini).
- **Kultura — ID:** 39 (nazwy nie ustalono bez mapy kultur).
- **Wiara/obrządek:** surowe pole `0x3e5a` = 0; klasyfikacja wartości i nazwa wiary **NIEUSTALONE**.
- **Dom dynastyczny — ID:** 4220.
- **Umiejętności** (dyplomacja, wojskowość, zarządzanie, intryga, nauka, sprawność): **10 / 2 / 5 / 10 / 8 / 5**; surowy klucz `0x29a5`.
- **Cechy osobowości, wykształcenia i inne**, dokładne angielskie klucze z tablicy zapisanej w save'ie: `forgiving` (trait #82); `paranoid` (trait #73); `patient` (trait #57); `education_learning_4` (trait #23). Surowy klucz `0x0648`.
- Polska interpretacja nazwy lub konkretnego efektu modyfikatora jest odrębnym etapem; liczby i angielskie klucze zachowano dosłownie.


## Rodzina — uzupełnienie z 1066-09-18

Wcześniejsze oznaczenie rodziny NIEUSTALONE zastępuje w zakresie wydobytych odniesień [rejestr relacji](relacje.md). Imiona, wiek i własne rekordy krewnych pozostają NIEUSTALONE.

</details>
