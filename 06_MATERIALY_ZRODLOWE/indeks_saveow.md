# Indeks save'ów

| Plik | SHA-256 | Kontener | Wpis danych | CK3 | Data gry | Odczyt |
|---|---|---|---|---|---|---|
| `von_Hohenzollern.ck3` | `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57` | ZIP | `gamestate` 72 844 529 B, binarny Jomini | 1.20.0.4 | 1066-09-16 | Integralność i nagłówek odczytane; data z pola binarnego metadanych; struktury osób/terytoriów jeszcze niesparsowane |
| `von_Hohenzollern(1).ck3` | `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` | ZIP | `gamestate` 73 103 324 B, binarny Jomini | 1.20.0.4 | 1066-09-18 | Integralność i nagłówek odczytane; metadane gracza i lista 20 identyfikatorów modów zgodne z poprzednim zapisem; obiekty świata jeszcze niesparsowane |

Źródła załączone w rozmowie dnia 2026-10-10. Pliku binarnego nie przesyłano do repozytorium; rejestrowany jest jego identyfikator i zakres wiarygodnego odczytu.

Metoda ustalenia daty: odczyt wartości binarnej daty w nagłówku Jomini, następnie przeliczenie na datę kalendarza gry; wartości 53144352 i 53144400 oznaczają odstęp 48 godzin. Obydwa pliki mają jednakowy zapisany ciąg UUID `08090d06-47a8-4247-b442-72c21000dea7`, ale jego rola w strukturze nie została niezależnie potwierdzona. CRC danych `gamestate` w obu archiwach poprawne.
