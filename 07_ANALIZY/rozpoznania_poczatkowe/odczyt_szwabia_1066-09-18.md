# Szwabia — rozszerzenie kart postaci, zapis 1066-09-18

## Techniczna metryka
- Save: `von_Hohenzollern.ck3`; SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; CK3 1.20.0.4; ZIP / binarny `gamestate` 73 103 324 B.
- Pole czasu `0x3157` = 53144400 => data gry **1066-09-18** (poprzednio 53144352 = 1066-09-16; jednostki 24/dobę). Nowy zapis różni się od poprzedniego SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.
- 17 024 158 leksemów Jomini sprawdzonych składniowo, poprawna równowaga klamer. **Skan składni to nie odszyfrowanie wszystkich kluczy.**
- Rzeczywiste powiązanie: `0xdc` (klucz tytułu), `0x27d7` (posiadacz), `0x2755` (imię w rekordzie postaci), `0x2e5e` (ID domu — identyfikacja na podstawie wcześniejszej analizy).

## Osoby (imię i posiadanie potwierdzone)
| ID | Osoba | Tytuły | Surowy ID domu | Surowe liczby pola 0x29a5 | Surowe pole 0x27e9 |
|---:|---|---|---:|---|---:|
| 33226 | Rudolf | `d_swabia 1216; c_ulm 1217` | 4224 | [7,6,4,8,3,3] | 52787760 |
| 32172 | Friedrich | `c_grunningen 1222` | 4221 | [6,5,6,7,10,8] | 52735200 |
| 34995 | Kuno | `c_wurttemberg 1227` | 4220 | [10,2,5,10,8,5] | 52866600 |
| 31865 | Berthold | `c_baden 1231` | 10607 | [7,5,8,4,9,7] | 52726440 |
| 37502 | Egino | `c_zollern 1235; b_zollern 1236` | 4228 | [5,10,7,4,9,4] | 52954200 |
| 62634 | Burkhard | `c_hohenberg 1239; b_hohenberg 1240` | 12843 | [3,5,4,5,0,8] | 53002968 |
| 31271 | Eberhard | `c_furstenberg 1242` | 4138 | [6,2,5,5,0,7] | 52691400 |
| 45250 | Ezzo | `b_helfenstein 1220` | 12154 | [3,10,4,5,1,10] | 53002848 |
| 45251 | Ekbert | `b_sigmaringen 1224` | NIEUSTALONE | [4,10,5,10,6,10] | 52932048 |
| 45252 | Friedrich | `b_tubingen 1229` | NIEUSTALONE | [2,7,7,1,0,5] | 52831848 |
| 45253 | Bernhard | `b_reutlingen 1238` | NIEUSTALONE | [5,7,6,4,7,7] | 52844808 |
| 45254 | Konrad | `b_rottweil 1241` | NIEUSTALONE | [6,0,8,9,3,6] | 52932048 |

## Fakty i niewiadome
- **POTWIERDZONE_SAVE:** siedem hrabstw w strukturze `d_swabia` 1216, 12 rozpoznanych osób będących posiadaczami tytułów, ich zapisane imiona i ID. Rudolf 33226 utrzymuje księstwo oraz Ulm, Burkhard 62634 — Hohenberg.
- **WNIOSEK:** pole `0x27e9` prawdopodobnie oznacza datę urodzenia, jednak pełne potwierdzenie semantyki tego kodu wymaga słownika. Sześciu liczb pola `0x29a5` nie przypisano automatycznie do nazw statystyk.
- **NIEUSTALONE:** realne traits, edukacja, kultura, wiara/obrządek, stan zdrowia, rodzina, małżonkowie/dzieci, urzędy, przynależność dworska, sojusze i relacje osobiste, portrety. Żaden władca nie jest automatycznie członkiem dworu Burkharda tylko z powodu położenia tytułu.
- **Do zdobycia:** datowany screen pełnej karty każdej osoby, Family/Relations, tooltipy traits, panel Council księcia, listy dworów i rycerzy oraz referencje Barber Shop; opisy wyglądu tylko z zatwierdzonych portretów.

[Indeks postaci](../../02_POSTACIE/indeks_postaci.md) · [Księstwo Szwabii](../../03_TERYTORIA/KSIESTWA/1216/karta.md) · [Indeks save'ów](../../06_MATERIALY_ZRODLOWE/indeks_saveow.md)

## Rozszerzenie polityczne i rodzinne — 10 X 2026, stan gry 18 IX 1066

Źródło aktualne: von_Hohenzollern(2).ck3; SHA-256 341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941; 1066-09-18; CK3 1.20.0.4. To ta sama zawartość co wcześniejszy alias (1).

Dane pochodzą z odczytów tej rozmowy i aktualnych kart o tym samym hash. Środowisko parsowania jest teraz niedostępne: nie wykonano nowego skanu całego świata. Zestawienie obejmuje 20 rozpoznanych z imienia osób oraz 30 dodatkowych kart ID krewnych. Te 30 kart nie jest pełnym rozpoznaniem własnych rekordów.

### Zależność władzy i sukcesji

**POTWIERDZONE_SAVE:** Hohenberg 1239 ma de_facto_liege=1216 i de_jure_liege=1216. Szwabia 1216 ma de_facto_liege=199; e_hre 199 posiada Heinrich 38661. Powstaje łańcuch: Burkhard/Hohenberg → Rudolf/Szwabia → Heinrich/Cesarstwo. Rudolf posiada też c_ulm 1217. Rottweil 1241 posiada Konrad 45254 i podlega de facto Hohenbergowi.

Burkhard ma zapisane prawa confederate_partition_succession_law i male_preference_law, a succession oraz heir Hohenbergu wskazują Rudolfa 33226, typ fallback_default. **WNIOSEK:** obecny wynik sukcesji nie zabezpiecza kontynuacji władzy przez potomka Burkharda. Nie przesądza to przyszłego wyniku po małżeństwie, narodzinach czy zmianie prawa.

W tytule Szwabii heir ma uporządkowaną listę: 40517, 39814, 40849, 41034, 34032, 33042, 41244, 41245; typ inheritance_child_line. Nie interpretuję wszystkich ośmiu jako jednoczesnych odbiorców ziem. Pierwsze cztery ID występują w rejestrze dzieci Rudolfa; pełne prawo i rozdział tytułów wymagają własnych kart i panelu sukcesji.

**Ważne ograniczenie:** lista siedmiu hrabstw to de iure, nie automatycznie wykaz wszystkich faktycznych lenników. Karta Baden z 16 IX wskazuje różne powiązania nadrzędne 1060 i 1216; właściciel Berthold jest potwierdzony również 18 IX, ale nie wykonano tu ponownej weryfikacji jego całej relacji de facto. Nie nazywać go bezwarunkowo bezpośrednim lennikiem Rudolfa.

### Osoby i znaczenie polityczne — ocena, nie fakty o zamiarach

| Osoba | Wiek 18 IX | Potwierdzona pozycja | Wniosek do dalszego sprawdzenia |
|---|---:|---|---|
| Rudolf 33226 | 40 | Książę Szwabii, Ulm, senior i wskazany następca Burkharda | Najważniejsza zależność Burkharda łączy zwierzchność i sukcesję; wrathful/paranoid uzasadniają ostrożną analizę reakcji, nie pewny konflikt |
| Friedrich 32172 | 46 | Grüningen, sześcioro dzieci w rejestrze | Rozbudowana rodzina daje więcej powiązań do rozpoznania; nie ma jeszcze potwierdzonych sojuszy dzieci |
| Kuno 34995 | 31 | Württemberg, dwoje dzieci w rejestrze | Bazowe DIP=10 i INT=10 oraz patient mogą wspierać długotrwałe działania polityczne; nie dowodzą spisku |
| Berthold 31865 | 47 | Baden, pięcioro dzieci; odrębność de iure/de facto w obserwacji 16 IX | Najpierw ustalić rzeczywiste zwierzchnictwo i pozostałe tytuły; gallant/logistician nie dowodzą przewagi liczebnej |
| Egino 37502 | 21 | Zollern | Młody władca istotny dla regionalnych relacji; brak dowodu pokrewieństwa z Burkhardem, mimo nazwy Hohenzollern |
| Eberhard 31271 | 51 | Fürstenberg, siedmioro dzieci w rejestrze | Rozpoznać dziedziczenie i małżeństwa licznej rodziny; wiek nie dowodzi bliskiej śmierci |
| Burkhard 62634 | 16 | Hohenberg, własna rada, dynasty_house 12843 | Najpilniej rozpoznać sukcesję, rolę seniora oraz skutki rozpoczętego sway do Helfericha |
| Heinrich 38661 | 16 | Cesarz e_hre, elekcja książęca, primary_spouse=38109 | Sprawdzić kandydatów i głosy, relację z Rudolfem oraz małżonka; młody wiek nie dowodzi trwającej regencji |

### Czterej dodatkowi baronowie — pełniejsze rozpoznanie

Poniższe dane personalne i posiadanie są potwierdzone na 18 IX w raportach repozytorium o hash aktualnego save'a. Ułożenie baronii pod hrabstwem w poniższej tabeli jest katalogiem ziem opartym na indeksie z 16 IX; nie zastępuje ponownego odczytu kontraktów i zależności na 18 IX.

| Osoba | ID | Wiek | Posiadłość | Osobowość z traits |
|---|---:|---:|---|---|
| Ezzo z Helfensteinu | 45250 | 16 | b_helfenstein 1220, wykaz Ulm | shy, stubborn, forgiving |
| Ekbert z Sigmaringen | 45251 | 24 | b_sigmaringen 1224, wykaz Grüningen | paranoid, brave, honest |
| Friedrich z Tübingen | 45252 | 35 | b_tubingen 1229, wykaz Württembergu | impatient, forgiving, shy |
| Bernhard z Reutlingen | 45253 | 34 | b_reutlingen 1238, wykaz Zollern | callous, calm, arrogant |

Ezzo 45250 jest inną osobą niż kanclerz Ezzo 65691. Friedrich 45252 jest inną osobą niż hrabia Friedrich 32172. Nie dopisano ich do rady, rycerzy ani dworu Burkharda.

### Polityka wewnętrzna Hohenbergu

Konrad 45254 łączy posiadanie Rottweil z urzędem zarządcy i task_collect_taxes. **WNIOSEK:** jest lokalną postacią łączącą podległą posiadłość i administrację; nie ustalono skali jego wpływów ani lojalności. Gerhard i Gunzelin występują zarówno przy zadaniach rady, jak i na liście knights. To koncentracja kilku funkcji, nie dowód ich współpracy czy rywalizacji.

Helferich 58415 jest celem rozpoczętego sway Burkharda od 16 IX i wykonuje task_religious_relations. Potwierdzone jest działanie wobec duchownego, nie udana poprawa relacji ani sojusz z Kościołem.

### Rodziny i 30 dalszych osób

[Transkrypcja wydobytych pól family_data](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/rodziny_1066-09-18.md) zawiera 30 nowych odniesień osobowych, każde z własną kartą ID i linkiem do osoby powiązanej.

| Władca | Główny małżonek — ID | Były małżonek — ID | Dzieci w rejestrze — ID |
|---|---|---|---|
| Rudolf 33226 | 36941 | 37235 | 39814, 40517, 40849, 41034 |
| Heinrich 38661 | 38109 | NIEUSTALONE | NIEUSTALONE |
| Friedrich 32172 | 33433 | NIEUSTALONE | 38079, 38252, 38609, 38909, 39030, 39173 |
| Kuno 34995 | NIEUSTALONE | NIEUSTALONE | 40316, 41253 |
| Berthold 31865 | 36154 | 34471 | 38078, 38251, 38608, 38908, 39172 |
| Eberhard 31271 | NIEUSTALONE | NIEUSTALONE | 34580, 34997, 36645, 37227, 38082, 38789, 39031 |

Imiona, cechy, życie i tytuły tych 30 osób NIEUSTALONE. Brak pola małżonka nie dowodzi stanu wolnego; former_spouses nie dowodzi rozwodu ani śmierci.

### Zakres nieukończony

Nadal nie rozpoznano w pełni: rzeczywistych lenników wszystkich hrabiów, dworu i rady Rudolfa, małżeńskich sojuszy, roszczeń i frakcji, opinii, wojen, wojsk oraz własnych rekordów 30 krewnych. Przywrócenie odczytu save'a pozwoli przejść po wskazanych ID. Nie zastępować tych danych rzeczywistą historią Szwabii.
