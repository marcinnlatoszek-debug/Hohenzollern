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

