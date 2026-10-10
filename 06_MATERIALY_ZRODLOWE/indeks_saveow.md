# Indeks źródeł — zapisy CK3 Hohenzollern

| Data w świecie CK3 | Nazwa pliku | SHA-256 | Rozmiar `gamestate` | Wersja gry | Interpretacja |
|---|---|---|---:|---|---|
| 1066-09-16 | `von_Hohenzollern.ck3` | `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57` | 72 844 529 B | 1.20.0.4 | **obserwacja historyczna**; skan 16 967 170 tokenów |
| **1066-09-18** | **`von_Hohenzollern(1).ck3`** | `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` | 73 103 324 B | 1.20.0.4 | **stan aktualny**; skan 17 024 158 tokenów |

Daty pochodzą ze struktury Jomini zapisów (`meta_date`), a nie z modyfikacji plików na dysku. Nie łączyć stanów obu dat bez chronologicznego oznaczenia.

Metoda: rozpoznanie ZIP, binarna tokenizacja, powiązanie `living`, `landed_titles`, rekordów zadań `council` i `playable_data`. Traity rozszyfrowano przy użyciu 419-wpisowej tablicy `traits_lookup` zapisanej **wewnątrz każdego** save'a. Tam, gdzie brakuje mapowania semantycznego, podawano surowe identyfikatory i oznaczenie NIEUSTALONE. Oryginałów nie modyfikowano.

## Powiązane raporty
- [Raport tokenizacji i identyfikacji z 16 IX](../07_ANALIZY/rozpoznania_poczatkowe/odczyt_ck3_2026-10-10.md)
- [Rozpoznanie Szwabii, stan 18 IX](../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)
- [Rada: porównanie 16 i 18 IX](../04_OTOCZENIE_WLADCY/rada.md)
- [Rozszyfrowane cechy i umiejętności (18 IX)](../07_ANALIZY/rozpoznania_poczatkowe/traits_i_umiejetnosci_1066-09-18.md)
