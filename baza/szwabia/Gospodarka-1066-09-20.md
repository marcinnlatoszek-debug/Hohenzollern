# Gospodarka Szwabii i Burkharda — S003

## Porównanie domen

Wszystkie 22 hrabstwa de facto mają county_control=100. Rozwój wynosi 8, poza Augsburgiem (12). Brak obniżenia kontroli nie dowodzi zadowolenia ludności. We wszystkich odczytanych hrabstwach występuje county_decline_development z ujemnym multiplier i datą wygaśnięcia w 1067; nie jest to dowód, że liczba development już spadła, ani wydarzenia głodu. Kultura 40 i rite 0 są polami dominującymi; WoC może przechowywać odrębną strukturę mniejszości.

| Domena Burkharda | Budynki zapisane | holding income | Fortyfikacja |
|---|---|---:|---:|
| Prowincja 2759 | castle_01, curtain_walls_01, windmills_01 | 2.85406 | 3 |
| Prowincja 2763 | castle_01, curtain_walls_01, cereal_fields_01 | 3.3432 | 3 |

Nie odczytano nowej budowy między 18 a 20 IX. Historia zmiany nie pozwala uznać wiatraków ani pól za inwestycję Burkharda w tych dwóch dniach. Wartości levy w rekordzie holding są identyfikatorami regimentów, nie liczbą żołnierzy.

Skarbiec pozostaje 94; income wzrosło z 5.87996 do 6.81698. Różnica arytmetyczna wynosi 0.93702, lecz jej pełne rozbicie na przyczyny i netto nie jest potwierdzone. Koncentracja na bogactwie, cecha ogrodnika i Ora et Labora mają potwierdzenie w ostatnim stanie. Nie dopisywać natychmiastowego wzrostu plonów jako wyniku mechanicznego.

## Ludność, podatki i urzędy

WoC zapisuje pop_clergy, pop_tribesmen, pop_slave, pop_peasant, pop_citizen, pop_nobility oraz county_manpower_var. Surowe data.identity nie mają potwierdzonej skali jednostek; bardzo duże wartości mogą być ujemnym fixed-point zapisanym unsigned. Nie nazywać ich bez dekodowania złotem, liczbą mieszkańców ani poborowych. W tej konfiguracji woc_no_military_system i wyłączony system poborowych WoC ograniczają stosowanie opisów standardowego systemu militarnego moda.

Populated World! generuje rodziny i postacie, a WoC modeluje zmienne ludności: to dwa odmienne poziomy. Dziewięć urzędów IDM daje społeczne kanały wpływu: miejscowa szlachta, wojownicy, duchowieństwo, chłopi i handel. Nie oznacza to nowożytnego parlamentu ani reprezentacji wybieranej. Kosztów urzędów nie wyliczono bez odpowiednich skryptów i tooltipów.

Ocena: Burkhard ma mocne zapisane income i pełną kontrolę, lecz sukcesja, poparcie kapelana, koszty wojsk oraz lokalnych urzędów pozostają bardziej istotnymi niewiadomymi niż narracja o już następującym kryzysie. Następny save należy porównać po gold, income, regimentach, kontroli, development, modyfikatorach i populacyjnych kluczach o tej samej skali.
