# Konrad — CK3 ID 45254

## Referencje ekranowe i narracyjne — aktualizacja dokumentacji 10 X 2026

**Dopisek aktualizacyjny:** Poprzednie oznaczenia „wygląd NIEUSTALONY” lub „brak screena” w historycznych partiach karty należy czytać jako stan sprzed otrzymania opisanych poniżej materiałów. Późniejsze screeny nie aktualizują automatycznie wartości save’a z 18 IX 1066.

- Tożsamość powiązana z CK3 ID **45254**; rozpoznana na ekranie postaci.
- [Źródła i wykaz oryginalnych screenów](zrodla.md) — karta: `Zrzut ekranu 2026-10-10 195609.png`; portret: `Barbershop_Count_Burkhard_of_Hohenberg_1066_09_18_0005.png`.
- [Załącznik opisowy: wygląd do narracji](wyglad.md) — referencja wizualna z Barber Shop, nazwa wskazuje datę **1066-09-18**.
- [Profil charakteru do narracji](profil_narracyjny.md) — pełne traity z save’a, etykieta profilu `Bold Brute` z ekranu, potencjalne sposoby działania oznaczone WNIOSEK.
- Wynik umiejętności z interfejsu (DIP / MAR / STE / INT / LEA / PRO): **7 / 0 / 9 / 10 / 9 / 6** (data panelu niezależnie NIEUSTALONA; nie zamieniać nim wcześniejszych wartości bazowych).
- **Obrazy binarne:** PNG dostępne jako załączniki tej rozmowy, a nie fizyczne pliki w repozytorium. Nie tworzyć fałszywych linków do `zrzuty_ekranu/*.png`.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/45254`; imię `Konrad`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1042.6.22`.

**OBLICZONE:** wiek **24** na 18 IX 1066, z daty urodzenia.

- Dom: ID **NIEUSTALONE / brak pola**, nazwa/klucz `NIEUSTALONE / brak pola`; dynastia ID **NIEUSTALONE / brak pola**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `40`, `culture_template=swabian`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[6, 0, 8, 9, 3, 6]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `callous` [indeks 76], `gregarious` [indeks 66], `arrogant` [indeks 59], `education_learning_3` [indeks 22].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `b_rottweil 1241` — nazwa zapisana: Rottweil.
- Ustrój: `republic_government`; prawa `landed_data/laws`: `city_succession_law`, `male_preference_law`.
- Kontrakt **16786985**: wasal [Konrad 45254](../45254/karta.md) → senior [Burkhard 62634](../62634/karta.md), grupa `republic_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Zarządca u [Burkhard 62634](../62634/karta.md); zadanie **16782043**, `task_collect_taxes`; potwierdzenie w `council_task_manager/database`.
- Surowe zasoby: `gold/value=30`, `income=0.84`; `current_strength=90`, `strength=90`, `levy=90`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice: nie znaleziono powiązania z wybranym ID w odczytanych tablicach dzieci; genealogii nie dopowiedziano.
- Brak własnych wpisów `family_data`; nie dowodzi stanu wolnego ani bezdzietności.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)


## Charakter — pakiet do fabuły, 18 IX 1066

**WNIOSEK, nie nowy fakt:** Sprawny w kontaktach i interesach; możliwe napięcie między potrzebą uznania a kosztami ponoszonymi przez innych.

Osobowość czytać razem z wiekiem, edukacją, kompetencjami i obowiązkiem. Natężenie traitów pozostaje nieprzypisane; zachowano XP. [Pełny profil i granice interpretacji](../../07_ANALIZY/rozpoznania_poczatkowe/charaktery_hohenberg_1066-09-18.md#45254-konrad). Scen i biografii nie dopisano.

<details>
<summary>Wcześniejsze obserwacje i etap rozpoznania — zachowane historycznie</summary>

# Konrad — CK3 ID 45254
**Obserwacja:** 1066-09-16. **Źródło:** `von_Hohenzollern.ck3` SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.

## Potwierdzone
- Imię odczytane z rekordu postaci o numerze 45254: **Konrad**.
- Powiązanie z aktualnym posiadaniem tytułu, odczytane z rekordów tytułów: **b_rottweil (1241)**.
- **Powiązanie z radą Burkharda potwierdzone:** rekord zadania **16782045** `task_disrupt_schemes` wskazuje Konrada (ID 45254) jako wykonawcę, a Burkharda (ID 62634) jako właściciela zadania. Funkcja odpowiada działalności mistrza intryg. Nie zakładać poza tym niepotwierdzonych więzi rodzinnych lub dworskich.

## Dane osobowe
Datę urodzenia, wartości umiejętności i traity odczytano — patrz sekcja danych personalnych. Relacje, szczegółowe modyfikatory i nieodczytane pola pozostają **NIEUSTALONE**.

## Screenshoty
Brak zatwierdzonego portretu. Planowane źródło: `06_MATERIALY_ZRODLOWE/zrzuty_ekranu/1066-09-16_postac_45254_*.png` (jeszcze nie utworzono). Docelowe pola: data świata, panel, odnośnik, status weryfikacji, Barber Shop.

## Powiązania i aktualizacje
[Indeks postaci](../indeks_postaci.md). Dane tej karty są datowane; nowe screeny dopisywać jako obserwacje, a nie bez daty nadpisywać dawne wartości.

## Obserwacja aktualizacyjna — 1066-09-18
**Źródło:** `von_Hohenzollern.ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` (wersja 1.20.0.4). Wcześniejszy stan z 1066-09-16 pozostaje historycznym źródłem.

**POTWIERDZONE_SAVE:** Rekord ID **45254**, imię **Konrad**; właściciel tytułu w rekordach: `b_rottweil 1241`. Pole ID domu `0x2e5e` niepotwierdzone; dom NIEUSTALONY. Pole datowe `0x27e9`: **52932048** (znaczenie biograficzne NIEUSTALONE). Surowe liczby z `0x29a5`: **[6,0,8,9,3,6]** (niezweryfikowana kolejność umiejętności).

**NIEUSTALONE:** dokładna data urodzenia, rodzice, małżeństwa, dzieci, kultura, wiara, obrządek, przyporządkowanie umiejętności, cechy/traits, urzędy, relacje, roszczenia i wygląd. Potrzebne: aktualny screen karty postaci, Family/Relations, tooltipy cech i osobna referencja Barber Shop. Tytuł nie dowodzi przebywania na dworze Burkharda.

## Dane personalne — odczyt pól 1066-09-16

**POTWIERDZONE_SAVE:** identyfikatory, surowe wartości, przypisanie numerów traitów do zapisanej w pliku tabeli `traits_lookup` (419 pozycji). Identyfikacja strukturalna `birth`, `skill`, `culture`, `faith`, `dynasty_house` jest wsparta schematem Jomini CK3; wartości nadają się do późniejszego porównania z interfejsem.

- **Data urodzenia:** 1042-06-22 (surowy klucz `0x27e9`, dekodowanie daty Jomini).
- **Kultura — ID:** 40 (nazwy nie ustalono bez mapy kultur).
- **Wiara/obrządek:** surowe pole `0x3e5a` = 0; klasyfikacja wartości i nazwa wiary **NIEUSTALONE**.
- **Dom dynastyczny — ID:** NIEUSTALONE (brak pola w bieżącej sekcji).
- **Umiejętności** (dyplomacja, wojskowość, zarządzanie, intryga, nauka, sprawność): **6 / 0 / 8 / 9 / 3 / 6**; surowy klucz `0x29a5`.
- **Cechy osobowości, wykształcenia i inne**, dokładne angielskie klucze z tablicy zapisanej w save'ie: `callous` (trait #76); `gregarious` (trait #66); `arrogant` (trait #59); `education_learning_3` (trait #22). Surowy klucz `0x0648`.
- Polska interpretacja nazwy lub konkretnego efektu modyfikatora jest odrębnym etapem; liczby i angielskie klucze zachowano dosłownie.

</details>
