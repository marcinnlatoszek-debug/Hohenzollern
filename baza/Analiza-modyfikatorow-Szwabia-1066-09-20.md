# Modyfikatory czasowe i polityczne — Szwabia, 20 IX 1066

**ŹRÓDŁO NADRZĘDNE:** natywny `von_Hohenzollern(2).ck3` (SAVE-20), odtworzony w [szwabia-save](dane/szwabia-save-1066-09-20.json) i [szwabia-relacje](dane/szwabia-relacje-1066-09-20.json). Nie rekonstruować ich z dawnej kampanii 1070–1071.

## Charakter efektów
**POTWIERDZONE_SAVE:** modyfikator `character_realm_prestige_modifier` jest czasowy, występuje u wielu hrabiów Szwabii. `miv_health_plus_2` działa u wielu szwabskich posiadaczy do 1086-09-15. **Nie** utożsamiać nazwy, mnożnika, siły końcowej i przyszłych zachowań postaci. `miv_historical_loyalty` jest osobną flagą/zmienną w odczycie, nie wykazanym samodzielnie okresem lojalności wobec konkretnej osoby.

| ID / postać | character_realm_prestige_modifier do | Surowy multiplier | miv_health_plus_2 do |
|---|---|---:|---|
| 62698 Burkhard, Zollern/Hohenberg | **1067-09-15** | 0.21940 | brak w odczycie |
| 33322 Rudolf, książę Szwabii | **1067-09-17** | 0.30256 | 1086-09-15 |
| 30931 Eberhard, Nellenburg/Zurych | 1067-09-15 | 0.44136 | 1086-09-15 |
| 30932 Anselm, Tübingen | 1067-09-15 | 0.14154 | 1086-09-15 |
| 30408 Hupold, Dillingen | 1067-09-15 | 0.09444 | 1086-09-15 |
| 31630 Rudolf, Urach | 1067-09-15 | 0.08754 | 1086-09-15 |
| 31948 Berthold, Karyntia/Breisgau (kontekst) | 1067-09-15 | 0.78170 | 1086-09-15 |
| 33142 Friedrich, Staufen | 1067-09-15 | 0.25734 | 1086-09-15 |
| 33143 Hartmann, Kirchberg | 1067-09-15 | 0.09444 | 1086-09-15 |
| 34081 Udalrich, Bregenz | 1067-09-15 | 0.11806 | 1086-09-15 |
| 34907 Welf, Ravensburg | 1067-09-15 | 0.16784 | 1086-09-15 |
| 34937 Kuno, Württemberg | 1067-09-15 | 0.09444 | 1086-09-15 |
| 37627 Hartmann, Kyrburg | 1067-09-15 | 0.09444 | 1086-09-15 |
| 38208 Ludwig, Sigmaringen | 1067-09-15 | 0.12628 | 1086-09-15 |
| 38740 Berthold, Fürstenberg | 1067-09-15 | 0.11408 | 1086-09-15 |
| 38741 Manegold, Veringen | 1067-09-15 | 0.12416 | 1086-09-15 |
| 28761 Romuald, Sankt Gallen | brak | — | 1086-09-15 |
| 33624 Embricho, Augsburg | brak | — | 1086-09-15 |
| 45347 Sigismund z Rottweil | brak w odczycie | — | brak w odczycie |

Rudolf z Urach (31630) ma także efekty `sound_foundations_intrigue_gain`, `sound_foundations_martial_gain`, `sound_foundations_learning_gain` z datą 9999-01-01 — zapisana data techniczna sugeruje trwały/bezterminowy charakter, NIE zwykły roczny buff. Rudolf książę (33322) ma `tenet_apostolic_succession_episcopate_modifier` również do daty 9999-01-01 (multiplier=2); interpretować w systemie religijnym aktualnej gry. Welf 34907 i Manegold 38741 mają zmienną `rd_potential_conqueror` z tick=5: **potencjał w mechanice Zeitgeist, nie potwierdzenie trwającej wyprawy czy zdobywcy**.

## POTWIERDZONE −20 za odwołanie z rady
W [rejestrze relacji](dane/szwabia-relacje-1066-09-20.json) cztery rekordy `fired_from_council_opinion` dotyczą opinii niżej wymienionych **względem Burkharda 62698**:
- Liutpold 62700;
- Peter 62703;
- Gebhard 62702;
- Sigismund z Rottweil 45347.

**Każdy: −20, od 1066-09-18 do 1076-09-18.** Pola `value` i `modify` nie sumują się do −40. To pojedynczy modyfikator opinii, nie opinia końcowa, nie dowód frakcji, wrogości ani spisku. Burkhard zachował ich przy dworze lub w przypadku Sigismunda ziemię.

## Prowincje de facto księstwa Szwabii
**23 wpisy hrabstw objętych odczytem** (22 de facto + Breisgau Bertholda jako najważniejszy kontekst sąsiedzki). We wszystkich: `county_decline_development` z ujemnym mnożnikiem i datą wygaśnięcia w 1067, kontrola 100. Wszystkie poziom rozwoju 8 poza Augsburgiem (12). Liczby multiplier są polami mechaniki, **nie wolno utożsamiać ich ze stratą punktów rozwoju na rok**.

| Hrabstwo | multiplier | Wygaśnięcie |
|---|---:|---|
| Augsburg | −0.54152 | 1067-09-15 |
| Urach | −0.50209 | 1067-09-15 |
| Zollern | −0.47862 | 1067-09-15 |
| Kyrburg | −0.47862 | 1067-09-15 |
| Kirchberg | −0.47862 | 1067-09-15 |
| Württemberg | −0.47862 | 1067-09-15 |
| Dillingen | −0.47766 | 1067-09-18 |
| Sankt Gallen | −0.45642 | 1067-09-15 |
| Fürstenberg | −0.41180 | 1067-09-15 |
| Bregenz | −0.39826 | 1067-09-15 |
| Veringen | −0.37750 | 1067-09-15 |
| Hohenberg | −0.37479 | 1067-09-15 |
| Sigmaringen | −0.37028 | 1067-09-15 |
| Staufen | −0.37028 | 1067-09-15 |
| Nellenburg | −0.37028 | 1067-09-15 |
| Nördlingen | −0.35403 | 1067-09-15 |
| Burgau | −0.35286 | 1067-09-16 |
| Tübingen | −0.31883 | 1067-09-15 |
| Breisgau | −0.31815 | 1067-09-15 |
| Grisons | −0.30890 | 1067-09-15 |
| Ravensburg | −0.22945 | 1067-09-15 |
| Zürich | −0.21953 | 1067-09-15 |
| Ulm | −0.21607 | 1067-09-16 |

Średnia arytmetyczna tych 23 zapisanych `multiplier` wynosi ok. **−0.38623**, nie jest średnim rocznym spadkiem rozwoju ani podstawą podatkową. System nie dotyka tylko młodego Burkharda. W pełnym binarnym save’ie nazwa `county_decline_development` występuje tysiące razy (2451 wystąpień wyszukiwania bajtów), co silnie sugeruje efekt szerokiej inicjalizacji, ale **nie potwierdza** dokładnego algorytmu ani jednakowego efektu dla każdego county.

**Wniosek ekonomiczno-fabularny:** ogólne utrudnienie rozwoju Szwabii przy 100 kontroli nie oznacza klęski głodu, masowego buntu czy spalonych wsi. Zollern ma silniej ujemny parametr niż Hohenberg. Augsburg ma większy poziom development i najbardziej ujemną wartość tej jednej zmiennej; nie ma podstaw do utożsamienia tego ze zniszczonym dobrobytem miasta.

## Kolejny odczyt
Po 15–18 IX 1067 sprawdzić rzeczywisty rozwój, income, zniknięcie wygasłych modyfikatorów i nowe czasowe efekty. Po 18 IX 1076 nie dopisywać pojednania — jedynie planowany koniec konkretnej kary `fired_from_council_opinion`. MIV `miv_health_plus_2` jest wpisany do 1086, co nie gwarantuje przeżycia postaci do tej daty.
