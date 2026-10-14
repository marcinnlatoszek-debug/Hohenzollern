# Rejestr zatwierdzonych zmian kampanii


## 14 października 2026 — rozpoznanie cech z binarnego zapisu 12 XI 1070

**Polecenie użytkownika:** odczytać cechy z plików gry i dodać je do kart postaci.

- Ponownie nadesłany plik `von_Hohenzollern(20261014-155345).ck3` ma ten sam SHA-256 co już zatwierdzony save `von_Hohenzollern(10).ck3`, więc **oś nie została przesunięta**.
- Zidentyfikowano tabelę **307 nazw cech** w `gamestate` oraz ich indeksy w rekordach (`traits`, token 1608).
- Uzupełniono osiem istniejących kart cechami Burkharda, Hedwig, Radbota, Walpurgi, Meinharda, Ingi, Hupolda III i Leopolda; powiązano Hupolda III z ID 32545.
- Utworzono karty Rudolfa (35525), Gerlacha (72054) i Siegmunda (76331).
- Zaktualizowano indeks postaci i raport źródłowy, w tym odróżnienie cech od automatycznych opisów charakteru i odrębnych pól save'a.
- Nie zatwierdzono żadnego nowego zdarzenia fabularnego ani przyszłego wyniku wojny, sukcesji czy choroby.

Dokument źródłowy: [rozpoznanie cech w raporcie](../07_ANALIZY/raporty_zmian/CK3_1070-11-12_weryfikacja.md#9-uzupełnienie-pełne-rozpoznanie-pola-cech-postaci-14-x-2026).

## 14 października 2026 — zatwierdzenie punktu 12 XI 1070

**Decyzja użytkownika:** „Tak” — akceptacja wcześniej przedstawionego pakietu odczytu `von_Hohenzollern(10).ck3`.

**Poprzedni zatwierdzony save:** 2 VIII 1070, `von_Hohenzollern(9).ck3`.  
**Nowy zatwierdzony save:** 12 XI 1070, `von_Hohenzollern(10).ck3`.  
**Różnica:** 102 dni w świecie gry.  
**Wersja gry:** CK3 1.20.1.

### Aktualizacje

- Zmieniono aktualny punkt stanu w `01_KAMPANIA/stan_aktualny.md` oraz metrykę starszego kanonu.
- Dodano wpis kontrolny w `campaign/Os_czasu_Zollern_1068-1070.md`, zachowując wcześniejsze datowane wydarzenia.
- Zmieniono `06_MATERIALY_ZRODLOWE/indeks_saveow.md` i status raportu `07_ANALIZY/raporty_zmian/CK3_1070-11-12_weryfikacja.md` z oczekującego na zatwierdzony.
- Dodano obserwacje na 12 XI w kartach Burkharda (66952), Hedwig (41150), ich synów (79306, 81336), hrabstwa Zollern i księstwa Szwabii.
- Założono dostępne karty dodatkowych osób z odczytu oraz zaktualizowano indeks. Karty nieobejmujące pełnego stanu postaci jawnie oznaczają braki.

### Wynik źródłowy

Żyją: Burkhard, Hedwig i obaj synowie; rodzina bez zmiany listy dzieci. Utrzymani posiadacze odczytanych tytułów: Burkhard — `c_zollern` i `b_zollern`, Rudolf — `d_swabia` i `c_ulm`, Heinrich — `e_hre`, Matthias — `c_urach`, Adelheid — `c_hohenberg`. W prawach Burkharda zachowany podział konfederacyjny i preferencja męska.

### Ograniczenia

Nie dopisano niepotwierdzonych bitew, wojen, wydarzeń religijnych, narodzin ani zmian w radzie. Statystyki z surowych tokenów binarnych nie są traktowane jako wartości interfejsu gry. Nie ustalono aktualnych zasobów, pełnego składu dworu, frakcji, armii, budynków ani sukcesji poszczególnych tytułów. Osobne karty Rudolfa (35525), Gerlacha (72054) i Matthiasa (61022) nie zostały utworzone w tej operacji; ich dane pozostają w raporcie źródłowym.

[Stan aktualny](stan_aktualny.md) · [Raport 12 XI 1070](../07_ANALIZY/raporty_zmian/CK3_1070-11-12_weryfikacja.md) · [Oś wydarzeń](../campaign/Os_czasu_Zollern_1068-1070.md)
