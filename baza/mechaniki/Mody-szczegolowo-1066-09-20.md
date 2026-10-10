# Mody kampanii Hohenzollern — odczyt save’a i dokumentacja

Źródło stanu: **von_Hohenzollern(2).ck3**, 20.09.1066, CK3 **1.20.0.4**. Dokumentacja sprawdzona 10.10.2026. Rozpoznano nazwy 23 z 24 pozycji. Odczytano pełny rozpakowany zapis, nie pliki z instalacji użytkownika. Save nie zawiera kompletnego kodu modów, ich lokalizacji ani gwarantowanego numeru wydania każdego moda. Aktualna strona autora może opisywać nowszą wersję.

**Najważniejsza zmiana interpretacji:** ogrodnictwo Burkharda można powiązać z osobistym przyjęciem Ora et Labora w oficjalnym dodatku By God Alone. Dodatkowe rodziny na dworze, prawa państwa i populacje hrabstw należy natomiast analizować przez mody, które je wprowadzają.

## 1. Lista wszystkich pozycji

Kolejność poniżej odpowiada tablicy `meta_data.mods`; nie jest niezależnym potwierdzeniem kolejności rozstrzygania wszystkich nadpisanych plików. Link prowadzi do strony autora danego elementu Steam Workshop. Krótki opis przedstawia zakres moda, a nie dowód, że każda jego funkcja została już wykorzystana w tej kampanii.

| # | ID Workshop i źródło | Mod | Znaczenie dla odczytu |
|---:|---|---|---|
| 1 | [2227658180](https://steamcommunity.com/sharedfiles/filedetails/?id=2227658180) | VIET Events — A Flavor and Immersion Event Mod | Wydarzenia codzienności i kontekst historyczny; zapisane reguły VIET. |
| 2 | [3006877184](https://steamcommunity.com/sharedfiles/filedetails/?id=3006877184) | Royal Court for Dukes | Dwór królewski dostępny dla książąt; Burkhard jest hrabią, więc sama obecność moda nie dowodzi posiadania takiego dworu. |
| 3 | [2261468688](https://steamcommunity.com/sharedfiles/filedetails/?id=2261468688) | Clear Notifications | Obsługa powiadomień, bez dowodu zmian biografii. |
| 4 | [2721974781](https://steamcommunity.com/sharedfiles/filedetails/?id=2721974781) | Councillor’s experience trait | Doświadczenie i specjalizacja doradców; sprawdzać osobno od edukacji. |
| 5 | [3150612985](https://steamcommunity.com/sharedfiles/filedetails/?id=3150612985) | Real Eyes 3.0 | Palety oczu; nie mechanika charakteru. |
| 6 | [2452585382](https://steamcommunity.com/sharedfiles/filedetails/?id=2452585382) | Medieval Arts | Monumenty i sztuka mapy; reguły dopuszczają również monumenty ahistoryczne. |
| 7 | [3571438676](https://steamcommunity.com/sharedfiles/filedetails/?id=3571438676) | Zeitgeist: Situation & Struggle | Sytuacje regionalne i pomniejsi zdobywcy; zapisane reguły `rd_*`. |
| 8 | [2986496756](https://steamcommunity.com/sharedfiles/filedetails/?id=2986496756) | More Background Illustrations | Ilustracje zależne od regionu i pory roku. |
| 9 | [3604729196](https://steamcommunity.com/sharedfiles/filedetails/?id=3604729196) | Immersive Domain Management | Lokalni możni i dodatkowe stanowiska; główny kontekst dziewięciu zapisanych urzędów. |
| 10 | [3030427202](https://steamcommunity.com/sharedfiles/filedetails/?id=3030427202) | Big Battle View | Rozbudowany widok bitwy, nie dowód zmian wyniku walk. |
| 11 | [2220326926](https://steamcommunity.com/sharedfiles/filedetails/?id=2220326926) | Better Barbershop | Edycja wyglądu i prezentacja postaci. |
| 12 | [3255992492](https://steamcommunity.com/workshop/filedetails/?id=3255992492) | Simple Graphic Pack | Zestaw zmian graficznych, mapy i elementów interfejsu. |
| 13 | [2712590542](https://steamcommunity.com/sharedfiles/filedetails/?id=2712590542) | More Interactive Vassals | Wojny seniorów i wasali, lojalność, zdrada, wyczerpanie oraz liczne reguły kampanii. |
| 14 | [3717989134](https://steamcommunity.com/sharedfiles/filedetails/?id=3717989134) | More Personality Depth | Natężenie cech osobowości; kluczowy dla kart postaci. |
| 15 | [3790487196](https://steamcommunity.com/sharedfiles/filedetails/?id=3790487196) | **Nazwa nieustalona** | Strona nie została odczytana; wyszukiwanie dokładnego ID nie rozstrzygnęło nazwy. Nie przypisano mu mechanik przez zgadywanie. |
| 16 | [3676381111](https://steamcommunity.com/sharedfiles/filedetails/?id=3676381111) | Regnum Teutonicum | Historyczne rodziny i tytuły Świętego Cesarstwa; nie dowód genealogii konkretnej postaci bez sprawdzenia rekordów. |
| 17 | [3461530706](https://steamcommunity.com/sharedfiles/filedetails/?id=3461530706) | Immersive Mercs & Raiders | Najemnicy, najazdy i wydarzenia zależne od charakteru dowódców. |
| 18 | [3360676953](https://steamcommunity.com/sharedfiles/filedetails/?id=3360676953) | Royal Court Event Pack | Dodatkowe wydarzenia dworskie. Obecność moda nie potwierdza konkretnego wydarzenia. |
| 19 | [3780779762](https://steamcommunity.com/workshop/filedetails/?id=3780779762) | Weight of Crown Fork | Populacje społeczne, migracje, podatki i zasoby ludzkie hrabstw. |
| 20 | [2223544446](https://steamcommunity.com/sharedfiles/filedetails/?id=2223544446) | Historical Accuracy | Zmiany AI, płodności, działań wojskowych i wybranych reguł rozwoju; nie tylko kosmetyka. |
| 21 | [3448267875](https://steamcommunity.com/sharedfiles/filedetails/?id=3448267875) | Populated World! | Rodziny dworzan, opiekunowie i demografia postaci; odrębne od populacji hrabstw WoC. |
| 22 | [3433842378](https://steamcommunity.com/sharedfiles/filedetails/?id=3433842378) | Additional Lifestyles | Dodatkowe drzewka i działania; sama koncentracja bogactwa Burkharda jest standardowym kluczem gry. |
| 23 | [2220098919](https://steamcommunity.com/workshop/filedetails/?id=2220098919) | Community Flavor Pack | Historyczne akcesoria portretów; flaga `cfp_is_loaded`. |
| 24 | [3351630685](https://steamcommunity.com/sharedfiles/filedetails/?id=3351630685) | Immersive Realm Laws | Czternaście dodatkowych rodzin praw `gpt_*`. |

## 2. Osobowość — najważniejsze dla przyszłych kart

Autor More Personality Depth opisuje trzy natężenia: **Mild, Normal, Intense**. Podaje wartości XP **50** dla Normal i **100** dla Intense. Tylko poziom Normal lub wyższy liczy się do archetypów AI według tej dokumentacji. Mod nadpisuje definicje osobowości oraz elementy okna i podpowiedzi postaci.

Odczyt Burkharda: `ambitious`, `diligent`, `patient`, a `trait_xp_amounts={ 1 1 1 }`. **Najbardziej prawdopodobna interpretacja: wszystkie trzy cechy mają poziom łagodny.** To wniosek z dokumentacji i zgodności liczby wpisów, nie zweryfikowany tooltip z tej instalacji. Nie przedstawiać hrabiego jako skrajnie ambitnego, niezmordowanego czy niewzruszonego wyłącznie na podstawie nazw cech.

Poniżej dokładne tablice. Kolejność XP wobec śledzonych cech wymaga definicji; nie wszystkie cechy postaci są śledzone, a niektóre mają dodatkowy tor. Dlatego celowo nie podpisano każdej liczby nazwą cechy.

| Postać | ID | Osobowość w kolejności save’a | Surowe `trait_xp_amounts` |
|---|---:|---|---|
| Burkhard | 62698 | ambitious, diligent, patient | 1, 1, 1 |
| Sieghard, kanclerz | 66576 | calm, callous, zealous | 50, 50, 1 |
| Sigismund, zarządca | 66605 | paranoid, temperate, arbitrary | 1, 50, 1 |
| Humbert von Venis, marszałek | 66598 | just, vengeful, gregarious | 50, 1, 1, 0 |
| Stefan, mistrz intryg | 65797 | impatient, sadistic, lustful | 50, 1, 50 |
| Sigismund, kapelan | 58283 | gluttonous, impatient, diligent | 50, 1, 1 |
| Liutpold | 62700 | zealous, honest, vengeful | 50, 50, 1 |
| Peter | 62703 | compassionate, calm, trusting | 1, 50, 1, 0 |
| Gebhard, były doradca | 62702 | stubborn, lustful, sadistic | 50, 1, 1 |
| Wolfram | 66593 | stubborn, arrogant, wrathful | 1, 1, 50, 0 |
| Elisabeth | 66610 | lustful, content, forgiving | 50, 50, 100 |
| Emma | 66601 | trusting, diligent, calm | 100, 50, 100, 0 |

Przykładowo Elisabeth ma zapis o innym natężeniu niż Burkhard, lecz bez mapowania torów nie ustanawiam jako pewnika, że to właśnie wyrozumiałość odpowiada za 100. Nie utożsamiać `trait_xp_amounts` z doświadczeniem edukacji lub stażem w radzie.

## 3. Dziewięć lokalnych urzędów — odczytane osoby

Immersive Domain Management przedstawia możnych jako zakorzenionych w domenie pośredników władzy, z rodzinami i interesami. Autor opisuje dziedziczenie stanowisk, trudność swobodnego usuwania ich posiadaczy oraz generowanie rodzin nawet przez trzy pokolenia. To mocny kontekst dla dużej liczby spokrewnionych dworzan w tym save’ie.

| Urząd zapisany w grze | Osoba | ID |
|---|---|---:|
| `gpt_dip_noble_court_position` | Sieghard von Genf | 66576 |
| `gpt_dip_noble_court_position` | Gebhard | 66583 |
| `gpt_claimant_court_position` | Wolfram | 66593 |
| `gpt_prw_noble_court_position` | Humbert von Breisgau | 66595 |
| `gpt_prw_noble_court_position` | Humbert von Venis | 66598 |
| `gpt_monk_court_position` | Emma | 66601 |
| `gpt_peasant_court_position` | Norbert | 66602 |
| `gpt_merchant_court_position` | Sigismund | 66605 |
| `gpt_int_noble_court_position` | Elisabeth | 66610 |

Wszystkie wpisy mają techniczne `hire_date=1066.9.15`. Nie ustanawia to dnia objęcia rządów Burkharda, który według użytkownika rządzi od sierpnia. Nazwy polskie i dokładne kompetencje tych stanowisk wymagają lokalizacji moda. Emma na stanowisku `monk` nie staje się przez to kapelanem — kapelanem jest Sigismund 58283. Urząd lokalnego możnego i stanowisko w radzie mogą występować u jednej osoby jednocześnie.

**Wniosek polityczny:** powołanie Siegharda, kupca Sigismunda i Humberta von Venis do rady łączy zwykłe funkcje rady z przedstawicielami lokalnych środowisk. Można interpretować to jako budowanie współpracy z elitami domeny; save nie dowodzi zawartej umowy, przyjaźni ani lojalności. Trzeba sprawdzać ich wsparcie/aptitude, krewnych i opinię. Nie wyliczono sumy wynagrodzeń dodatkowych urzędów.

## 4. Dodatkowe prawa Burkharda

Immersive Realm Laws opisuje czternaście rodzin praw z pięcioma wariantami każda, głosowanie możnych i wpływ osobowości na politykę. Save potwierdza następujące warianty u Burkharda:

| Rodzina prawa | Odczytany klucz |
|---|---|
| Religia | `gpt_religious_law_vassal_1` |
| Dyplomacja | `gpt_diplomacy_law_vassal_2` |
| Podatki | `gpt_taxation_law_vassal_2` |
| Niewolnictwo | `gpt_slavery_law_vassal_1` |
| Miasta | `gpt_urban_law_vassal_1` |
| Urzędnicy | `gpt_officers_law_vassal_2` |
| Formalności | `gpt_formality_law_vassal_2` |
| Kary | `gpt_punishment_law_vassal_2` |
| Moralność | `gpt_moral_law_vassal_3` |
| Kobiety | `gpt_women_law_vassal_2` |
| Uroczystości | `gpt_festivity_law_vassal_2` |
| Dowodzenie | `gpt_command_law_vassal_3` |
| Bezpieczeństwo | `gpt_security_law_vassal_2` |
| Czujność | `gpt_vigilance_law_vassal_2` |

Przekład rodziny prawa jest opisem roboczym, nie pełną polską lokalizacją wariantu. **Cyfra 1/2/3 nie wystarcza do nazwania prawa liberalnym, represyjnym czy neutralnym.** Również sufiks `_vassal_` nie dowodzi, że Burkhard sam przegłosował ustawę. Lista tych praw nie zmieniła się między dwoma ostatnimi zapisami.

Z innych praw są m.in. `woc_no_military_system`, `government_expenditure_3`, `government_tax_3`, `serfdom`. Pierwszy klucz i reguła `woc_levy_system_disabled` wskazują wyłączenie dodatkowego systemu wojskowego WoC. Pozostałych premii i nazw wariantów nie ustalono bez definicji. Nie dopisywać do narracji nowej reformy podatkowej tylko dlatego, że prawo jest obecne.

## 5. Weight of Crown Fork — gospodarka i ludność

Dokumentacja autora opisuje warstwy społeczne, migracje, proporcje kultur i religii oraz manpower. W save’ie występuje globalna flaga `woc_mod_set_up`, prawa WoC i następujące zmienne tytułów:

| Pole | Zollern 1176 | Hohenberg 1183 |
|---|---:|---:|
| `pop_clergy` | 2349 | 3108 |
| `pop_tribesmen` | Brak identity | Brak identity |
| `pop_slave` | 187968 | 248688 |
| `pop_peasant` | 263156 | 348164 |
| `pop_citizen` | 14074 | 18620 |
| `pop_nobility` | 4722 | 6248 |
| `county_manpower_var` | 62163000 | 82242000 |
| `county_tax_gold` | 76983 | 101831 |

Wartości w tabeli to **surowe `data.identity`**, nie potwierdzone liczby mieszkańców, żołnierzy ani monet. Puste identity pozostawiono jako brak, bez twierdzenia o znaczeniu wartości domyślnej. Pole `type=value` ma reprezentację techniczną; jednostki i przeliczniki muszą wynikać z kodu moda.

U Burkharda jest też `county_tax_gold_adjustment_woc_var` z identity `18446744073709353316`. Interpretacja tego zapisu jako dodatniego majątku byłaby błędem: przy odczycie signed 64-bit ta liczba odpowiada **−198300**. Dalsze dzielenie przez skalę stałoprzecinkową i wpływ na dochód pozostają niepotwierdzone. Nie odejmujemy −198300 od złota 94.

Listy `woc_immigration_county` i `county_settlement`, wpisy kultur i wiary oraz listy zaopatrzenia regimentów wskazują utrwalony stan systemu. Nie potwierdzają, że konkretna rodzina wyemigrowała lub że Burkhard zarządził osiedlenie.

Reguły: `woc_cultural_integration_none`, `woc_immigration_distance_default`, `woc_mpe_set_up_none`, **`woc_levy_system_disabled`**. Nie wolno więc automatycznie tłumaczyć redukcji jego wojska włączeniem systemu poboru WoC. Prowincjonalne pola `levy` mogą być referencjami do regimentów, a nie liczbą ludzi; odczytane osobiste `landed_data.levy=333` jest innym polem.

**Populated World! dotyczy demografii postaci**, podczas gdy WoC utrzymuje populacje terytoriów. Duża rodzina na dworze nie jest odczytem `pop_peasant`. Populated World! obejmuje również zmiany zdrowia, stresu i płodności według aktualnego opisu, więc przy kartach nie zakładać wszystkich standardowych efektów podstawowej gry.

## 6. More Interactive Vassals i Zeitgeist — realne ustawienia

MIV według autora rozbudowuje udział wasali w wojnach, wybór stron w buntach i negocjowanie poparcia. W tej kampanii zapisane są m.in.:

| Zapisana reguła | Ostrożny odczyt |
|---|---|
| `miv_attacker_behavior_personality`, `miv_defender_behavior_personality` | Wybrane zachowanie zależne od osobowości. |
| `war_exhaustion_miv_enabled`, `ally_exhaustion_miv_enabled` | Włączone mechaniki wyczerpania. |
| `miv_loyalist_enabled`, `traitor_vassals_miv_enabled`, `miv_oathbreakers_enabled` | Włączone mechaniki lojalistów, zdrady i łamania przysiąg. |
| `vassals_join_claims_enabled`, `vassals_defend_titles_enabled` | Udział wasali związany z roszczeniami i obroną tytułów. |
| `request_vassal_support_miv_enabled`, `intervention_war_miv_enabled` | Prośby o wsparcie i interwencje. |
| `border_wars_miv_disabled`, `vassal_wars_miv_disabled` | Te konkretne dodatkowe moduły są wyłączone; nie oznacza to braku wszelkich wojen wasali. |

Zapis zawiera też `ai_aggressiveness_plus_50`, `ai_kingdom_stability_very_high` i `ai_empire_stability_high`. To nazwy wybranych opcji; bez skryptów nie przeliczam ich na prawdopodobieństwo wybuchu wojny. Włączona możliwość zdrady nie jest dowodem, że Sigismund z Rottweil zdradza hrabiego.

Zeitgeist ma `rd_conqueror_enabled`, `rd_conqueror_chosen_span_10_year`, `rd_conqueror_chosen_weight_military_strength`, `rd_conqueror_situation_rd_downfall_enabled`. Autor opisuje regionalne epoki i pomniejszych zdobywców. Nie ustalono aktualnej fazy regionu Szwabii ani wybranego zdobywcy. Nie utożsamiać tego systemu ze zmianą posiadacza odziedziczonych ziem Burkharda.

## 7. Ważne rozstrzygnięcie: Ora et Labora pochodzi z oficjalnej mechaniki

Paradox w **By God Alone #1** wskazuje, że **Ora et Labora nadaje Gardener**. Spełnienie duchowe jest osobistą miarą zgodności życia z wiarą, odrębną od pobożności, na skali −100 do +100.

Save Burkharda ma równocześnie:

```text
playable_data.tenets = { tenet_ora_et_labora }
playable_data.current_spiritual_fulfillment = 10
traits: lifestyle_gardener
```

**Silny wniosek:** pojawienie się ogrodnika najprawdopodobniej wynika z przyjęcia tej osobistej zasady. Nie odczytano dziennika kliknięć, więc nie ustanawiam daty ani przebiegu wyboru poza przedziałem między zapisami. Wartość 10 nie oznacza 10 punktów pobożności, poziomu świętości ani opinii kapelana. Nie jest dowodem konwersji całego władztwa. Źródło: [oficjalny dziennik Paradox, publikacja z 28.04.2026](https://store.steampowered.com/news/posts/?appids=1158310&enddate=1779192003&feed=steam_community_announcements).

## 8. Inne mody: czego nie przypisywać im automatycznie

Councillor’s experience trait rozwija kompetencję na stanowisku. Autor opisuje trzy poziomy i specjalizację w jednym zawodzie, a późniejsze uwagi wydaniowe przejście na pasek XP. Nie traktować starszego opisu miesięcznych szans jako zweryfikowanej formuły tej instalacji. W odczytanych listach cech obecnych głównych doradców nie ma `lifestyle_chancellor`, `lifestyle_marshal`, `lifestyle_steward` ani `lifestyle_spymaster`; nie przypisano im modowych premii za staż.

Additional Lifestyles oferuje m.in. drzewko Founder w zarządzaniu. Burkhard ma `stewardship_wealth_focus` i zapisane zero doświadczenia stylów życia. Nie potwierdza to odblokowania dodatkowych perków ani nowych działań sukcesyjnych.

Historical Accuracy według autora ingeruje również w AI małżeństw, płodność, mobilizację i cooldown koncentracji. Nie sprowadzać go do herbów. Immersive Mercs & Raiders rozbudowuje kontakty z najemnikami i najazdy; obecność na liście nie dowodzi zawarcia kontraktu lub przeprowadzenia chevauchée.

VIET ma `VIET_balanced_events`, `VIET_normal_universe_events`, `VIET_historical_context_on` i domyślne ustawienia częstotliwości oraz zasobów. Medieval Arts ma `MA_monuments_all`, `MA_ahistorical_monuments_yes`, `MA_creator_pack_yes`. Ustawienie historycznego kontekstu VIET nie sprawia, że każda scena jest źródłem historycznym; ahistoryczne monumenty MA nie są dowodem rzeczywistej architektury XI wieku.

## 9. Dostępność plików źródłowych i granice odczytu

Znaleziono [publiczne repozytorium autora VIET](https://github.com/cybrxkhan/VIET-Events-for-CK3) i odczytano [deskryptor moda](https://github.com/cybrxkhan/VIET-Events-for-CK3/blob/master/VIET%20Events.mod), który deklaruje `supported_version="1.20.*"`. Numer deskryptora nie jest potwierdzeniem wydania użytego w save’ie. Repozytorium ostrzega, że gałąź master jest robocza. Nie odczytano kompletnego katalogu skryptów z tej gałęzi ani plików lokalnej instalacji.

Nie uzyskano definicji cech MPD, lokalizacji praw i skryptów przeliczających ludność WoC z egzemplarzy użytych przez użytkownika. Do ścisłego odczytu potrzebne są przede wszystkim: `common/traits`, `common/laws`, `common/court_positions`, `common/script_values`, `common/scripted_effects`, `common/scripted_triggers`, `events` oraz `localization` właściwych modów i ich deskryptory. Bez nich zachowujemy surowe klucze i zaznaczamy wnioski.

Pozostały nierozpoznane pochodzenie flag `pam_great_schism_decision_taken` i `FSB_is_loaded` oraz nazwa ID 3790487196. Sam prefiks nie wystarcza do przypisania autora. Flaga schizmy nie jest dowodem osobistej decyzji Burkharda.

## 10. Standard dalszej analizy kampanii

1. Odczytać postać po ID, pełną listę cech i tablicę XP; ostrożnie ustalić natężenie.
2. Rozdzielić radę od dodatkowych urzędów lokalnych możnych oraz ustalić ich rodziny i wsparcie.
3. Czytać prawa jako konkretne klucze; nazwy i premie tylko z właściwej lokalizacji i kodu.
4. Rozdzielać populacje terytoriów, demografię postaci, zasoby manpower i faktyczną liczebność wojska.
5. Sprawdzać włączenie modułów w regułach, nie tylko obecność moda.
6. Porównywać stany przed i po. Obecność mechaniki nie dowodzi jej uruchomienia przez gracza.
7. Oddzielać oficjalne nowe mechaniki religii od modów.
8. Utrzymywać kanon użytkownika: odziedziczone ziemie, początek rządów w sierpniu, Konrad jako ojciec i Ludwig jako dziadek.

Towarzyszący plik **Mody-Hohenzollern-dane-1066-09-20.json** zachowuje odczytane tablice modów, wszystkie reguły, zmienne globalne, stan Burkharda, tytuły i urzędy oraz surowe cechy/XP otoczenia. Rozdział opisowy zawiera hipotezy; JSON pozostawia dane bez przekładu efektów.
