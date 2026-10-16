# Indeks zapisów gry CK3

## Potwierdzone punkty

| Data w grze | Plik / źródło | Wersja | Zakres i ograniczenia |
|---|---|---|---|
| 24 XI 1066 | `von_Hohenzollern(2).ck3` | 1.20.0.4 | Historyczny punkt bazowy w kanonie 1066. |
| 6 III 1067 | Save wskazany w zatwierdzonym tle świata | NIEUSTALONA w tym indeksie | Przekrój źródłowy dla rady, wasali, ziem i sytuacji politycznej. |
| **2 VIII 1070** | **`von_Hohenzollern(9).ck3`** | **1.20.1** | Starszy zatwierdzony punkt kontrolny (14 X 2026); odczyt podstawowych tytułów i relacji rodzinnych. |
| **12 XI 1070** | **`von_Hohenzollern(10).ck3`** | **1.20.1** | Archiwalny zatwierdzony save (14 X 2026). Porównanie rodziny, sukcesji w rejestrze praw, wybranych tytułów i żyjących postaci z 2 VIII 1070; pola niezmapowane: NIEUSTALONE. [Raport weryfikacji](../07_ANALIZY/raporty_zmian/CK3_1070-11-12_weryfikacja.md). |
| **18 X 1073** | **`von_Hohenzollern(20261014-200855).ck3`**; duplikat `von_Hohenzollern(20261014-201208).ck3` | **1.20.1** | Ostatni pełny, zatwierdzony audyt save’a przed punktem 1080. Zgon Leopolda 7 VII 1071; wojna i zdobycie Hohenbergu 17 I 1073; Hedwig w ciąży, aktualne tytuły i zadania rady. [Raport](../07_ANALIZY/raporty_zmian/CK3_1073-10-18_weryfikacja.md). |
| **2 X 1080** | **`von_Hohenzollern(20261016-154350).ck3`** | **1.20.1** | Punktowy odczyt zaakceptowany do aktualizacji 16 X 2026: Burkhard włada Zollern i Hohenbergiem, nie prowadzi aktywnej wojny, `last_war_finish_date=1 VI 1080`; dzieci, zaręczyny Adelheid, sukcesja, śmierć Leopolda i stres. To nie pełny audyt wszystkich pól. Szczegóły i rozbieżność daty narracyjnej 18 V opisano w [osi 1078–1080](../campaign/Os_czasu_Zollern_1078-1080.md). Zapis przechowywany poza tym repozytorium. |

## Rozpoznane nowsze zapisy — bez przesunięcia zatwierdzonej osi

| Data w grze | Plik | Status |
|---|---|---|
| **4 II 1075** | `von_Hohenzollern(20261015-182245).ck3` | **Data odczytana z metadanych w badaniu Deep Research 15 X 2026.** Nie zatwierdzono tego pliku jako nowego punktu świata; nie używać stanu 1075 do scen na 18 X 1073. |

Zatwierdzony 15 X 2026 [kanon polityczny Cesarstwa 1067–1073](../campaign/Kanon_polityki_Cesarstwa_1067-1073.md) rozszerza interpretację wcześniejszych pełnych zapisów **bez przesuwania daty ostatniego zatwierdzonego stanu**.

Plik z 2 VIII 1070 zawiera dane Jomini i skompresowaną sekcję `gamestate`; sam rozpoznany format nie oznacza pełnego odczytu. Wartości zasobów uzyskane ze wstępnego mapowania wymagają dalszej walidacji.

**Uwaga o chronologii:** screeny od września do 3 XI 1070 poprzedzają save z 12 XI; zatwierdzone obserwacje ekranowe 1078–1080 kończą się 1 X 1080, a punktowy odczyt save’a obejmuje 2 X 1080. Nie interpolować nieodczytanych zdarzeń między źródłami.

Powiązanie: [aktualny rejestr punktów](../01_KAMPANIA/stan_aktualny.md).
