# Indeks źródeł — zapisy CK3 Hohenzollern

| Data w świecie CK3 | Nazwa pliku | SHA-256 | Rozmiar `gamestate` | Wersja gry | Interpretacja |
|---|---|---|---:|---|---|
| 1066-09-16 | `von_Hohenzollern.ck3` | `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57` | 72 844 529 B | 1.20.0.4 | **obserwacja historyczna**; skan 16 967 170 tokenów |
| 1066-09-18 | `von_Hohenzollern(1).ck3` | `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` | 73 103 324 B | 1.20.0.4 | **obserwacja historyczna**; skan 17 024 158 tokenów |

| **1066-10-20** | **`von_Hohenzollern(1).ck3` (nowy upload; inny hash)** | `4db685e32ffb282fb88c436b37d468bf93c955cf57576b335e9679313afcfca0` | 74 504 886 B | 1.20.0.4 | **stan aktualny**; CRC ZIP OK; [raport zmian](../07_ANALIZY/rozpoznania_poczatkowe/zmiany_1066-09-18_do_1066-10-20.md) |

Daty pochodzą ze struktury Jomini zapisów (`meta_date`), a nie z modyfikacji plików na dysku. Nie łączyć stanów obu dat bez chronologicznego oznaczenia.

Metoda: rozpoznanie ZIP, binarna tokenizacja, powiązanie `living`, `landed_titles`, rekordów zadań `council` i `playable_data`. Traity rozszyfrowano przy użyciu 419-wpisowej tablicy `traits_lookup` zapisanej **wewnątrz każdego** save'a. Tam, gdzie brakuje mapowania semantycznego, podawano surowe identyfikatory i oznaczenie NIEUSTALONE. Oryginałów nie modyfikowano.

## Powiązane raporty
- [Raport tokenizacji i identyfikacji z 16 IX](../07_ANALIZY/rozpoznania_poczatkowe/odczyt_ck3_2026-10-10.md)
- [Rozpoznanie Szwabii, stan 18 IX](../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)
- [Rada: porównanie 16 i 18 IX](../04_OTOCZENIE_WLADCY/rada.md)
- [Rozszyfrowane cechy i umiejętności (18 IX)](../07_ANALIZY/rozpoznania_poczatkowe/traits_i_umiejetnosci_1066-09-18.md)

## Alias przesłany w tej rozmowie

`von_Hohenzollern(2).ck3` ma SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`, rozmiar 11 362 371 B. Jest bajtowo identyczny z pozycją (1) z 18 IX, nie nowym punktem czasu. Odczyt Rakaly CLI 0.8.21. [Transkrypcja odczytanych rodzin](notatki_z_wydarzen/rodziny_1066-09-18.md). Zatwierdzenie rozpoznanych modów przez gracza: 10 X 2026, 18:51 czasu Europe/Warsaw.

## Rozszerzenie odczytu 10 X 2026

Ten sam hash (alias (2)) ponownie zweryfikowano lokalnie; oryginału nie zmieniono. Rakaly 0.8.21: odczyt binarny, kontrola brakujących kluczy poprawna. Rozpoznano 112 własnych rekordów, kontrakty i rady, powiązania rodzinne, roszczenia i cesarskie nominacje. [Wybrane pola źródłowe](notatki_z_wydarzen/polityka_1066-09-18.json). Rozszerzenie zastępuje prowizoryczne wnioski w istniejącej analizie, bez nowej daty gry.

## Hohenberg — materiał do analizy charakterów

Ponowny odczyt tego samego save’a 18 IX 1066: dziewięć postaci, surowe XP, języki, daty wejścia na dwór, pamięć 4377 oraz sway 2. [Transkrypcja](notatki_z_wydarzen/charaktery_hohenberg_1066-09-18.json). Profile fabularne są oznaczone jako interpretacja, bez dopisanych wydarzeń.


## Nowy zapis z 20 X 1066 — 10 X 2026

Przesłano nową zawartość pod **ponownie używaną nazwą** `von_Hohenzollern(1).ck3`. SHA-256 nowej zawartości to `4db685e32ffb282fb88c436b37d468bf93c955cf57576b335e9679313afcfca0`, rozmiar kontenera 12 203 029 B; **nie** jest to wcześniejszy plik (1) o SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` z 18 IX. Data z metadanych, nie z nazwy. Sprawdzono CRC ZIP, metadane oraz wskazane rekordy postaci/rad. Dokumentacja porównania: [18 IX → 20 X](../07_ANALIZY/rozpoznania_poczatkowe/zmiany_1066-09-18_do_1066-10-20.md). Oryginalny binarny zapis nie jest składowany w tym publicznym repozytorium.
