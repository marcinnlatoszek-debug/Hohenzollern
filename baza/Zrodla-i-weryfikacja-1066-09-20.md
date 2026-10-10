# Rejestr źródeł, konflikty i otwarte sprawy — 20 IX 1066

## Źródła i hierarchia
| ID | Datowanie | Materiał i zakres |
|---|---|---|
| **AUTHOR-1066** | sierpień 1066 (autorski kanon) | Wyraźna korekta gracza: Burkhard dziedziczy całe ziemie, rządzi od sierpnia, ojciec Konrad, dziad Ludwig. Ma pierwszeństwo w opisie sukcesji. |
| **SAVE-18A** | 1066-09-18 | Oryginalny plik Library von_Hohenzollern.ck3, starsza rada i regimenty |
| **SAVE-18B** | 1066-09-18 | Oryginalny plik Library von_Hohenzollern(1).ck3, cztery nominacje i ograniczenie oddziałów |
| **SAVE-20** | **1066-09-20** | Oryginalny plik Library von_Hohenzollern(2).ck3 (CK3 1.20.0.4), nadrzędny dla parametrów gry |
| **EXTRACT-20** | 1066-09-20 | [Surowy wyciąg JSON](dane/wyciag-save-1066-09-20.json) z meta_data mods, game_rules, global_variables, Burkharda, czterech tytułów i wybranych kart; **nie pełny zapis gamestate** |
| **REPORT-20** | 10 października 2026 | Plik Library Mody-Hohenzollern-1066-09-20.md (wnioski i porównanie dokumentacji) |
| **KANON-20** | 10 października 2026 | Plik Library Kanon-Hohenzollern-biezacy.md, korekty autora i połączenie trzech save’ów |
| **ANALYSIS-18** | 10 października 2026 | Plik Library Analiza-save-Hohenzollern-1066-09-18.md, wyłącznie historyczny pierwszy stan |
| **COMPARE-20** | 10 października 2026 | Plik Library Burkhard-Zmiany-i-tlo-fabularne-1066-09-20.md, porównanie 18→20 IX |
| **COURT-18** | 10 października 2026 | Plik Library Karty-dworzan-Burkharda-1066-09-18.md (43 karty; poprzednie urzędy nie są bieżące) |

Oryginalne save’y pozostają w Library; GitHub zawiera **wyciąg**, nie w całości duże binarne gamestate. To inne źródła niż stara skasowana kampania 1070–1071. Nie odtwarzano dawnego kanonu.

## Konflikty i potwierdzone korekty
1. **Dziedziczenie**: techniczna historia 15 IX (revoked od Friedricha) jest sprzeczna z potwierdzeniem autora o dziedziczeniu w sierpniu. W narracji obowiązuje AUTHOR-1066. Przyczyna mechanicznej rozbieżności nieustalona.
2. **Podatek Hohenbergu**: REPORT-20 podaje county_tax_gold = 101831, ale EXTRACT-20 z SAVE-20 podaje **101852**. Przyjmij **101852** jako surową wartość, bez przeliczenia na monety.
3. **Wojsko 20 IX**: suma składu regimentów i levy różni się o 2 od zbiorczego current_strength/strength. Zachowaj obie wartości; nie uznawaj różnicy za jednostki konkretnych żołnierzy.
4. **Income**: 6.81698 to pole save, NIE udowodniony bilans netto. Równość 6.19726×1.10 ≈6.81698 odpowiada fokusowi bogactwa; bazowy wzrost nie jest automatycznie realną produkcją.
5. **Skalowanie WoC**: identity pop_*, county_manpower_var i county_tax_gold to **wewnętrzne jednostki**; nie przeliczać ich na ludzi, żołnierzy i złoto bez skryptów.
6. **county_destruction**: typ value bez identity w obu hrabstwach, nie odczytana dodatnia liczba. Nie twierdzić, że na pewno nie wydarzyło się żadne zniszczenie.
7. **Brak głodu i rebelii**: brak w analizowanych źródłach potwierdzenia, nie dowód absolutnej nieobecności. Pełny save/tooltipy mogą ujawnić dodatkowe zdarzenia.
8. **Migracje**: listy 85/80 identyfikatorów, nie 85/80 migrantów. Nie wiemy, czy konkretne przesiedlenia nastąpiły.
9. **Modów jest 24**; nazwa ID 3790487196 nieustalona. Wersje lokalnych skryptów nie są zawarte w wyciągu.
10. **Cechy More Personality Depth**: XP=[1,1,1] Burkharda prawdopodobnie Mild; nie jest to pewny tooltip ani konkretne zachowanie.

## Następne źródła potrzebne do obliczeń
- Z folderów modów: common/script_values, common/scripted_effects, common/scripted_triggers, common/laws, common/court_positions, common/traits, localization, events oraz deskryptory wersji.
- Z gry: pełny bilans netto i jego składowe, tooltipy podatków i praw, utrzymanie lokalnych urzędów/wojsk, zmiany budynków, opinie Norberta, Sigismundów, Wolframa i kapelana.
- Po nowym save: porównanie county_destruction, county_settlement, pop_*, migracji, rozwoju, dochodów i poparcia.
- Dla 20 IX ustalono wszystkich 17 posiadaczy 22 hrabstw de facto i ich siłę w [raporcie Szwabii](szwabia/Polityka-1066-09-20.md). Po nowym save’ie potrzebne ponowne sprawdzenie; nie przenosić liczb z dawnej kampanii 1071.

## Reguła przyszłych wpisów
Każdy wpis zapisuj z ID, datą gry, statusem (POTWIERDZONE_SAVE, KOREKTA_AUTORA, OBLICZONE, WNIOSEK, TLO_FABULARNE, NIEUSTALONE), źródłem i granicą. Życiorysy i sceny odkładaj do osobnej warstwy, nie uzupełniaj nimi statystyk i praw.


## Jednoznaczne identyfikatory i dostęp

S001=SAVE-18A; S002=SAVE-18B; S003=SAVE-20. [Rejestr z hashami](dane/rejestr-zrodel.json) identyfikuje trzy natywne pliki. [Katalog](Indeks-kampanii.md) obejmuje aktywną dokumentację, a [audyt](interpretacja/Audyt-dokumentacji-1066-09-20.md) rozstrzyga zakresy i starsze ograniczenia. Pełny odczyt Szwabii jest wykonany dla wskazanego zakresu, lecz nie zastępuje skanowania całego świata ani lokalnych skryptów modów.
