# Bernhard — CK3 ID 45253
**Obserwacja:** 1066-09-16. **Źródło:** `von_Hohenzollern.ck3` SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.

## Potwierdzone
- Imię odczytane z rekordu postaci o numerze 45253: **Bernhard**.
- Powiązanie z aktualnym posiadaniem tytułu, odczytane z rekordów tytułów: **b_reutlingen (1238)**.
- Dalsze związki rodzinne i przynależność do dworu Burkharda: **NIEUSTALONE**. Nie wpisywać do jego rady ani rycerzy bez osobnego potwierdzenia.

## Dane osobowe
Datę urodzenia, wartości umiejętności i traity odczytano — patrz sekcja danych personalnych. Relacje, szczegółowe modyfikatory i nieodczytane pola pozostają **NIEUSTALONE**.

## Screenshoty
Brak zatwierdzonego portretu. Planowane źródło: `06_MATERIALY_ZRODLOWE/zrzuty_ekranu/1066-09-16_postac_45253_*.png` (jeszcze nie utworzono). Docelowe pola: data świata, panel, odnośnik, status weryfikacji, Barber Shop.

## Powiązania i aktualizacje
[Indeks postaci](../indeks_postaci.md). Dane tej karty są datowane; nowe screeny dopisywać jako obserwacje, a nie bez daty nadpisywać dawne wartości.

## Obserwacja aktualizacyjna — 1066-09-18
**Źródło:** `von_Hohenzollern.ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` (wersja 1.20.0.4). Wcześniejszy stan z 1066-09-16 pozostaje historycznym źródłem.

**POTWIERDZONE_SAVE:** Rekord ID **45253**, imię **Bernhard**; właściciel tytułu w rekordach: `b_reutlingen 1238`. Pole ID domu `0x2e5e` niepotwierdzone; dom NIEUSTALONY. Pole datowe `0x27e9`: **52844808** (znaczenie biograficzne NIEUSTALONE). Surowe liczby z `0x29a5`: **[5,7,6,4,7,7]** (niezweryfikowana kolejność umiejętności).

**NIEUSTALONE:** dokładna data urodzenia, rodzice, małżeństwa, dzieci, kultura, wiara, obrządek, przyporządkowanie umiejętności, cechy/traits, urzędy, relacje, roszczenia i wygląd. Potrzebne: aktualny screen karty postaci, Family/Relations, tooltipy cech i osobna referencja Barber Shop. Tytuł nie dowodzi przebywania na dworze Burkharda.

## Dane personalne — odczyt pól 1066-09-16

**POTWIERDZONE_SAVE:** identyfikatory, surowe wartości, przypisanie numerów traitów do zapisanej w pliku tabeli `traits_lookup` (419 pozycji). Identyfikacja strukturalna `birth`, `skill`, `culture`, `faith`, `dynasty_house` jest wsparta schematem Jomini CK3; wartości nadają się do późniejszego porównania z interfejsem.

- **Data urodzenia:** 1032-07-07 (surowy klucz `0x27e9`, dekodowanie daty Jomini).
- **Kultura — ID:** 40 (nazwy nie ustalono bez mapy kultur).
- **Wiara/obrządek:** surowe pole `0x3e5a` = 0; klasyfikacja wartości i nazwa wiary **NIEUSTALONE**.
- **Dom dynastyczny — ID:** NIEUSTALONE (brak pola w bieżącej sekcji).
- **Umiejętności** (dyplomacja, wojskowość, zarządzanie, intryga, nauka, sprawność): **5 / 7 / 6 / 4 / 7 / 7**; surowy klucz `0x29a5`.
- **Cechy osobowości, wykształcenia i inne**, dokładne angielskie klucze z tablicy zapisanej w save'ie: `callous` (trait #76); `calm` (trait #56); `arrogant` (trait #59); `education_learning_1` (trait #20). Surowy klucz `0x0648`.
- Polska interpretacja nazwy lub konkretnego efektu modyfikatora jest odrębnym etapem; liczby i angielskie klucze zachowano dosłownie.

