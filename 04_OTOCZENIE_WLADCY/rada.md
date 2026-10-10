# Rada Burkharda von Hohenzollern — porównanie dwóch zapisów

**Władca:** Burkhard, CK3 ID **62634**.
**Obserwacje:** 1066-09-16 oraz 1066-09-18, CK3 **1.20.0.4**.
**Źródło 1:** `von_Hohenzollern.ck3`, SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.
**Źródło 2:** `von_Hohenzollern(1).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`.

## Porównanie obsady (POTWIERDZONE_SAVE)

| Funkcja (wniosek z klucza zadania) | ID stanowiska | Zadanie zapisane w save | Stan 1066-09-16 | Stan 1066-09-18 |
|---|---:|---|---|---|
| Kanclerz | 16782042 | `task_foreign_affairs` | [Notker 62636](../02_POSTACIE/62636/karta.md) | [Ezzo 65691](../02_POSTACIE/65691/karta.md) |
| Zarządca | 16782043 | `task_collect_taxes` | [Gerhard 62635](../02_POSTACIE/62635/karta.md) | [Konrad 45254](../02_POSTACIE/45254/karta.md) |
| Marszałek | 16782044 | `task_organize_levies` | **Brak przypisanej postaci** w rekordzie stanowiska | [Gerhard 62635](../02_POSTACIE/62635/karta.md) |
| Mistrz intryg | 16782045 | `task_disrupt_schemes` | [Konrad 45254](../02_POSTACIE/45254/karta.md) | [Gunzelin 65692](../02_POSTACIE/65692/karta.md) |
| Duchowny dworski | 16782046 | `task_religious_relations` | [Helferich 58415](../02_POSTACIE/58415/karta.md) | [Helferich 58415](../02_POSTACIE/58415/karta.md) |

Weryfikacja strukturalna: w rekordzie żyjącego Burkharda (ID 62634), wewnątrz bloku `0x2753` (landed_data), znajduje się tablica `0x2ddd` z pięcioma ID stanowisk 16782042–16782046. Osobne rekordy tych stanowisk zawierają klucz zadania `0x00e1`, identyfikator osoby w `0x2812` (gdy obsadzone) i odsyłacz do Burkharda w `0x299f`. Pierwszy save nie ma przypisanej postaci w rekordzie 16782044, natomiast drugi ma `62635`. Imiona odczytano z pola `0x2755` w rekordach postaci.

## Zmiany między obserwacjami

- Kanclerz: **Notker → Ezzo**.
- Zarządca: **Gerhard → Konrad**.
- Marszałek: **brak przypisanej osoby → Gerhard**.
- Mistrz intryg: **Konrad → Gunzelin**.
- Duchowny: **Helferich → Helferich** (bez zmiany).

Zapis potwierdza stany w dwóch datach. Nie przypisujemy dokładnego dnia odwołania ani powołania, jeśli nie jest on niezależnie udokumentowany.

## Bazowe umiejętności (wartości odczytane z `0x29a5`)

Kolejność standardowej tablicy `skill`: dyplomacja, wojskowość, zarządzanie, intryga, nauka, sprawność. Wartości nie obejmują wszystkich możliwych modyfikatorów interfejsu.

| Stanowisko | Wartość osoby na 16 IX | Wartość osoby na 18 IX | Różnica |
|---|---:|---:|---:|
| Kanclerz, dyplomacja | Notker 5 | Ezzo 5 | 0 |
| Zarządca, zarządzanie | Gerhard 6 | Konrad 8 | +2 |
| Marszałek, wojskowość | brak obsady | Gerhard 9 | nowa obsada |
| Mistrz intryg, intryga | Konrad 9 | Gunzelin 4 | −5 |
| Duchowny, nauka | Helferich 6 | Helferich 6 | 0 |

**Analiza (nie kanon):** zmiana zarządcy zwiększa bazową umiejętność zarządzania obsady o 2 punkty, obsadzono marszałka, lecz spadła bazowa umiejętność intrygi mistrza intryg o 5 punktów. Nie oznacza to automatycznie określonego skutku działań rady.

**NIEUSTALONE:** motywacja zmian personalnych, efektywne umiejętności po modyfikatorach, wszystkie relacje i opinie oraz formalne daty nominacji. Weryfikacja na screenie rady może uzupełnić zakres danych.
