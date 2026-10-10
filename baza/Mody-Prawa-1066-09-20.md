# Mechaniki i mody kampanii (save 20 IX 1066)

W meta_data.mods jest **24** wpisy; wcześniejsza dokumentacja rozpoznała 23. Obecność na liście NIE jest potwierdzeniem uruchomienia wszystkich zdarzeń danego moda, numerów wersji ani pełnego zgodnego działania. Własne skrypty z instalacji gracza nie zostały odczytane.

| # | Workshop ID | Mod |
|---:|---|---|
| 1 | 2227658180 | VIET Events |
| 2 | 3006877184 | Royal Court for Dukes |
| 3 | 2261468688 | Clear Notifications |
| 4 | 2721974781 | Councillor’s experience trait |
| 5 | 3150612985 | Real Eyes 3.0 |
| 6 | 2452585382 | Medieval Arts |
| 7 | 3571438676 | Zeitgeist: Situation & Struggle |
| 8 | 2986496756 | More Background Illustrations |
| 9 | 3604729196 | Immersive Domain Management |
| 10 | 3030427202 | Big Battle View |
| 11 | 2220326926 | Better Barbershop |
| 12 | 3255992492 | Simple Graphic Pack |
| 13 | 2712590542 | More Interactive Vassals |
| 14 | 3717989134 | More Personality Depth |
| 15 | 3790487196 | **Nazwa nieustalona** |
| 16 | 3676381111 | Regnum Teutonicum |
| 17 | 3461530706 | Immersive Mercs & Raiders |
| 18 | 3360676953 | Royal Court Event Pack |
| 19 | 3780779762 | Weight of Crown Fork |
| 20 | 2223544446 | Historical Accuracy |
| 21 | 3448267875 | Populated World! |
| 22 | 3433842378 | Additional Lifestyles |
| 23 | 2220098919 | Community Flavor Pack |
| 24 | 3351630685 | Immersive Realm Laws |

## Wpływ na analizę
- **Weight of Crown Fork:** zapisane populacje, podatki, manpower, migracje, prawa systemowe. Reguły woc_cultural_integration_none, woc_immigration_distance_default, woc_mpe_set_up_none i **woc_levy_system_disabled**. W danych także woc_no_military_system i serfdom. Wartości wewnętrzne bez przelicznika. **Populated World!** natomiast generuje osoby i ich rodziny, nie struktury terytorialne.
- **Immersive Domain Management:** dziewięć urzędów lokalnych (patrz [polityka](Polityka-Dwor-1066-09-20.md)); miejscowi możni, kupiec, urząd chłopski, mnich/zakonny i inni. Wynagrodzenia/lojalność/obowiązki wymagają właściwego kodu. Sama rola nie dowodzi działania lub poparcia.
- **Immersive Realm Laws:** 14 rodzin ustaw; cyfra po vassal NIE jest automatycznie indeksem surowości, a sufiks nie dowodzi autorstwa Burkharda. Odczytane pary: religious=1, diplomacy=2, taxation=2, slavery=1, urban=1, officers=2, formality=2, punishment=2, moral=3, women=2, festivity=2, command=3, security=2, vigilance=2 (wszystkie jako gpt_..._law_vassal_N). Inne pola government_expenditure_3, government_tax_3, serfdom.
- **More Interactive Vassals:** aktywne m.in. miv_attacker_behavior_personality, miv_defender_behavior_personality, miv_loyalist_enabled, traitor_vassals_miv_enabled, miv_oathbreakers_enabled, vassals_join_claims_enabled, vassals_defend_titles_enabled, request_vassal_support_miv_enabled, intervention_war_miv_enabled, war_exhaustion_miv_enabled. Wyłączone border_wars_miv_disabled i vassal_wars_miv_disabled (to nie znaczy, że nie ma żadnych wojen wasalnych). ai_aggressiveness_plus_50 to ustawienie, nie mierzalna szansa wojny bez skryptów.
- **More Personality Depth:** dokumentacja łączy XP 50 z Normal i 100 z Intense; Burkhard ma [1,1,1], prawdopodobnie Mild. Niezależny tooltip lub definicja traitów potrzebne dla stuprocentowej identyfikacji.
- **Zeitgeist:** rd_conqueror_enabled i sytuacje regionalne, lecz brak danych do stwierdzenia aktywnego zdobywcy w Szwabii.
- **By God Alone (oficjalna mechanika gry, nie osobny mod listy):** Ora et Labora wiąże się z Gardener, a osobiste spiritual_fulfillment=10 nie jest ani pobożnością, ani dowodem konwersji prowincji.
- **Historical Accuracy, Additional Lifestyles, Councillor’s experience:** mogą zmieniać wyniki AI, rozwój postaci, staż urzędniczy; nie przypisywać nowych perków/bonusów bez ich wpisu.

## Lokalizacja efektów do zdobycia
Wymagane pliki z wersji zainstalowanej dla tej kampanii: common/laws, common/court_positions, common/script_values, common/scripted_effects, common/scripted_triggers, common/traits, localization, events, descriptor.mod. Dopóki ich nie ma, opisujemy mechanizmy, nie fikcyjne stawki fiskalne. **Nigdy nie utożsamiać pop_slave z potwierdzoną strukturą historycznej niewoli na podstawie samej etykiety.**
