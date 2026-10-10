# Gospodarka i społeczeństwo — Zollern oraz Hohenberg (20 IX 1066)

**KLUCZOWA ZASADA:** wartości WoC w kolumnach są SUROWYMI wartościami data.identity. To niezweryfikowane jednostki moda, **nie liczba mieszkańców, monet lub wojsk**. Służą do porównań i liczenia proporcji.

## Zmienne populacji i fiskusa
| Flaga | Zollern / c_zollern 1176 | Hohenberg / c_hohenberg 1183 |
|---|---:|---:|
| pop_peasant | 263156 | 348164 |
| pop_slave | 187968 | 248688 |
| pop_citizen | 14074 | 18620 |
| pop_nobility | 4722 | 6248 |
| pop_clergy | 2349 | 3108 |
| pop_tribesmen | brak identity | brak identity |
| **Suma pięciu dodatnich kategorii** | **472269** | **624828** |
| county_manpower_var | 62163000 | 82242000 |
| county_tax_gold | 76983 | **101852** |
| county_destruction | obecna zmienna bez identity | obecna zmienna bez identity |

Źródło nadrzędne: wyciąg bezpośrednio z save’a **20 IX**, plik [dane/wyciag-save-1066-09-20.json](dane/wyciag-save-1066-09-20.json). **KOREKTA błędu:** dawny raport tekstowy miał Hohenberg county_tax_gold=101831. W JSON z natywnego save’a jest 101852. Poprzednia liczba nie jest obowiązująca. Pozostawiono ślad konfliktu w [źródłach](Zrodla-i-weryfikacja-1066-09-20.md).

## Obliczenia, nie spis powszechny
W obu hrabstwach udział pięciu kategorii w sumie ich surowych wartości: chłopi **55,72%**, zależni pop_slave **39,80%**, mieszczanie **2,98%**, możni **1,00%**, duchowieństwo **0,50%**. Są to **proporcje zmiennych moda, nie potwierdzony realny rozkład demograficzny** ani etykiety prawne mieszkańców. Hohenberg ma wartości sumaryczne ok. **32,3%** większe; relacja county_tax_gold/suma = ok. **0,163** w obu ziemiach. Podobieństwo sugeruje wspólny schemat początkowy modów i skalowanie rozmiarem prowincji; pozostaje WNIOSKIEM. Możliwość, że poszczególne kategorie korzystają z różnych przeliczników, wymaga kodu moda.

## Dochody i skarbiec
| Pole | 18 IX po reorganizacji | 20 IX |
|---|---:|---:|
| income Burkharda | 5.87996 | **6.81698** |
| income posiadłości 2763 | 3.16801 | **3.34320** |
| income posiadłości 2759 | 2.71195 | **2.85406** |
| gold | 94 | **94** |

Suma 3.34320 + 2.85406 = **6.19726**. Mnożenie przez **1,10** daje **6.816986**, praktycznie zgodne z zapisanym 6.81698. Zbieżne z premią dochodową od stewardship_wealth_focus (+10%); bez lokalnych plików efektów modów nie wyklucza to innych składników. Wzrost bazowej sumy 0.31730 nie dowodzi wzrostu fizycznej produkcji w dwa dni. Skarbiec nie urósł. **Income nie jest wyliczonym saldem netto**: nie znamy pełnych wynagrodzeń 9 lokalnych urzędów, kosztów armii, prawa fiskalnego, obciążeń senioralnych i innych wydatków.

## Kontrola, rozwój, presja
Oba hrabstwa: CK3 rozwój **8**, kontrola **100**, kultura szwabska, obrządek rzymskokatolicki. Ujemny county_decline_development do 1067-09-15 (Zollern −0.47862; Hohenberg −0.37479). Jego dokładne przeliczenie nieustalone.

Zmienna county_destruction nie ma dodatniego identity; **nie potwierdza aktywnych dodatnich zniszczeń w tym polu**, nie dowodzi braku wszystkich historycznych szkód. Nie odczytano potwierdzonego głodu, ogólnego buntu chłopskiego lub załamania handlu. Nie zamieniać braku odczytu na kategoryczne stwierdzenie ich nieistnienia.

## Migracje i warstwy społeczne
W listach woc_immigration_county po **85** identyfikatorów (Zollern), **80** (Hohenberg). To **nie liczby migrantów** ani dowód aktualnej migracji; listy mogą reprezentować mechaniczne cele/powiązania. Obecny jest county_settlement. Włączony Weight of Crown Fork, ale woc_levy_system_disabled i woc_no_military_system: wartości county_manpower_var nie są osobistymi regimentami Burkharda. Populated World! generuje osoby/rodziny dworskie, a nie liczby chłopów w WoC.

## Obraz społeczny do powieści (TLO_FABULARNE)
Zollern — polityczna i dworska siedziba Burkharda, obszar pracy wiejskiej i powinności. Hohenberg — wyższa bazowa wartość ludności i podatków modelu, ale nie dowiedziono większego bogactwa per capita. Rottweil — osobny lokalny ośrodek administracji pod Sigismundem; nie opisywać jako późnośredniowiecznej wolnej republiki. Norbert (urząd peasant; cecha peasant_leader) może reprezentować interesy rolników, Sigismund-kupiec finanse, Peter pamięć dawnego zarządu, możni i duchowieństwo wpływy. **Nie przydzielać im przeżytych klęsk, protestów, zawartych układów czy opinii bez nowego źródła.**

## Dalsze pola do odczytu
Dokładna skala WoC (pop_*, tax, manpower), wydatki netto, lista wszystkich budynków i nakładów, treść prawa podatkowego i serfdom, przyczyny spadku rozwoju, przepływy migracyjne, stawki wynagrodzeń. Do tego konieczne są skrypty common/script_values, common/laws, common/court_positions, events i lokalizacja **wersji modów z instalacji gracza** lub właściwe tooltipy.
