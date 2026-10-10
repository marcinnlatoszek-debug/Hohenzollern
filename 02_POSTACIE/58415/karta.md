# Helferich — CK3 ID 58415

**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/58415`; imię `Helferich`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1015.4.11`.

**OBLICZONE:** wiek **51** na 18 IX 1066, z daty urodzenia.

- Dom: ID **NIEUSTALONE / brak pola**, nazwa/klucz `NIEUSTALONE / brak pola`; dynastia ID **NIEUSTALONE / brak pola**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `40`, `culture_template=swabian`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[6, 3, 10, 2, 6, 0]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `impatient` [indeks 58], `gregarious` [indeks 66], `just` [indeks 70], `education_learning_4` [indeks 23].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): nie znaleziono aktualnie posiadanego tytułu.
- Dwór: `court_data/employer=62634` — [Burkhard 62634](../62634/karta.md). To pole dworu, odrębne od kontraktu lennego.
- Duchowny u [Burkhard 62634](../62634/karta.md); zadanie **16782046**, `task_religious_relations`; potwierdzenie w `council_task_manager/database`.

## Rodzina — zapisane relacje

- Rodzice: nie znaleziono powiązania z wybranym ID w odczytanych tablicach dzieci; genealogii nie dopowiedziano.
- Brak własnych wpisów `family_data`; nie dowodzi stanu wolnego ani bezdzietności.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)

<details>
<summary>Wcześniejsze obserwacje i etap rozpoznania — zachowane historycznie</summary>

# Helferich — CK3 ID 58415
**Data obserwacji w świecie gry:** 1066-09-16
**Źródło:** `von_Hohenzollern.ck3`, SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.
**Status:** POTWIERDZONE_SAVE dla ID, imienia i surowych powiązań; funkcja radna/rycerstwo to interpretacja zidentyfikowanego pola Jomini wsparta schematem `CK3 Gamestate Field Schema` (thomandretti/ck3-strategy-advisor).

## Tożsamość i zadania
- Imię: **Helferich** (rekord postaci, ID 58415).
- **Duchowny radny / sprawy religijne**.
- Zadanie `task_religious_relations` (stosunki religijne), rekord zadania 16782046 wskazuje wykonawcę 58415.
- Rekord zadania wskazuje, że właścicielem jest Burkhard (ID 62634), jeżeli dotyczy.

- Brak dowodu na pokrewieństwo z Burkhardem. Nie domniemywać przynależności do osobistej domeny ani innych urzędów.
## Dane biograficzne do uzupełnienia
Data urodzenia, wiek, rodzina, kultura, wiara, obrządek, cechy osobowości, wykształcenie, umiejętności, zdrowie, majątek, relacje, lojalność: NIEUSTALONE.
## Przypisanie screenshotów
Zatwierdzony screenshot/portret: **BRAK**.
Planowana ścieżka: `06_MATERIALY_ZRODLOWE/zrzuty_ekranu/1066-09-16_postac_58415_*.png` (plik jeszcze nie istnieje).
Do uzupełnienia: data gry; ID; widoczny panel; ścieżka w repozytorium; źródło; potwierdzony wygląd / Barber Shop.
## Powiązania
[Rada i rycerze Burkharda](../../04_OTOCZENIE_WLADCY/indeks_dworu.md) · [Burkhard 62634](../62634/karta.md) · [Indeks postaci](../indeks_postaci.md).

## Zmiana stanu rady — 1066-09-18
1066-09-16 i 1066-09-18: **duchowny dworski** Burkharda, `task_religious_relations`, ID stanowiska 16782046. Brak zmiany przypisanej osoby. Bazowa tablica umiejętności: `[6, 3, 10, 2, 6, 0]`.
Źródło nowej obserwacji: `von_Hohenzollern(1).ck3` SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` (CK3 1.20.0.4). Porównanie: [Rada Burkharda](../../04_OTOCZENIE_WLADCY/rada.md). Brak pełnej weryfikacji cech, relacji i portretu.

## Dane personalne — odczyt pól 1066-09-16

**POTWIERDZONE_SAVE:** identyfikatory, surowe wartości, przypisanie numerów traitów do zapisanej w pliku tabeli `traits_lookup` (419 pozycji). Identyfikacja strukturalna `birth`, `skill`, `culture`, `faith`, `dynasty_house` jest wsparta schematem Jomini CK3; wartości nadają się do późniejszego porównania z interfejsem.

- **Data urodzenia:** 1015-04-11 (surowy klucz `0x27e9`, dekodowanie daty Jomini).
- **Kultura — ID:** 40 (nazwy nie ustalono bez mapy kultur).
- **Wiara/obrządek:** surowe pole `0x3e5a` = 0; klasyfikacja wartości i nazwa wiary **NIEUSTALONE**.
- **Dom dynastyczny — ID:** NIEUSTALONE (brak pola w bieżącej sekcji).
- **Umiejętności** (dyplomacja, wojskowość, zarządzanie, intryga, nauka, sprawność): **6 / 3 / 10 / 2 / 6 / 0**; surowy klucz `0x29a5`.
- **Cechy osobowości, wykształcenia i inne**, dokładne angielskie klucze z tablicy zapisanej w save'ie: `impatient` (trait #58); `gregarious` (trait #66); `just` (trait #70); `education_learning_4` (trait #23). Surowy klucz `0x0648`.
- Polska interpretacja nazwy lub konkretnego efektu modyfikatora jest odrębnym etapem; liczby i angielskie klucze zachowano dosłownie.

</details>
