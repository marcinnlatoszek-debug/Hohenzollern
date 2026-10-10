# Hohenberg — charaktery i materiał do fabuły

Stan **18 IX 1066**, CK3 **1.20.0.4**. Źródło: `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; alias (1) jest identyczny. Analiza 10 X 2026.

## Zakres i sposób użycia

**Dziewięć osób:** Burkhard, siedem osób z employer=62634 oraz Konrad z Rottweil, jego wasal i zarządca. Ponowny skan powiązań w living nie ujawnił dodatkowej osoby z jawnym polem wskazującym Burkharda; w court_positions i diarchies nie znaleziono dalszego powiązanego urzędu. To pełny rozpoznany krąg, nie spis nieodczytanych mieszkańców hrabstwa.

**POTWIERDZONE_SAVE** dotyczy tożsamości, cech i danych. **OBLICZONE** dotyczy wieku. Wszystkie profile, napięcia, sposoby mówienia i zastosowania sceniczne poniżej są **WNIOSEK / PROPOZYCJA DO FABUŁY**. Nie stanowią pamięci scen ani potwierdzenia myśli lub działań. Pakiet służy autorowi; nie jest gotowym rozdziałem.

Nie odczytano pełnych opinii i stresu. Relations/active_relations nie ma wpisu dotyczącego żadnej z dziewięciu osób. Nie ustanowiono przyjaźni, rywalizacji lub lojalności. Siedmioro dworzan ma join_court_date=1066.9.15; sama ta data nie rozstrzyga, czy znali się wcześniej. Konrad pozostaje odrębnym wasalem, bez employer=62634.

## Natężenie cech i mody

More Personality Depth jest rozpoznanym i zatwierdzonym modem. Aktualny opis autora rozróżnia Mild, Normal, Intense oraz podaje XP 50 dla Normal i 100 dla Intense. To potwierdzenie ogólnego modelu moda, nie identyfikacja jego zainstalowanej wersji ani kolejności torów trait_xp_amounts w tym save. [Opis autora, sprawdzony 10 X 2026](https://steamcommunity.com/sharedfiles/filedetails/?id=3717989134).

Zachowano surowe XP. Bez definicji torów nie przypisano każdej liczby do cechy i nie nadano polskich nazw stopni. Tablice mieszane zawierają także inne traity. Dlatego określenia osobowości w tabeli oznaczają kierunek, a natężenie reakcji pozostaje otwarte. Nie pisać skrajnej wersji charakteru na podstawie samego klucza.

| Osoba | Wiek | Rola | Osobowość — roboczy przekład kluczy | Edukacja i cechy odrębne |
|---|---:|---|---|---|
| [Burkhard 62634](../../02_POSTACIE/62634/karta.md) | 16 | Hrabia Hohenbergu | ambitny, pracowity, cierpliwy | zarządzanie 3/4; intellect_good_2 |
| [Ezzo 65691](../../02_POSTACIE/65691/karta.md) | 27 | Kanclerz; employer=62634 | chwiejny, niecierpliwy, nieśmiały | dyplomacja 2/4 |
| [Konrad 45254](../../02_POSTACIE/45254/karta.md) | 24 | Zarządca; republikański posiadacz Rottweil | nieczuły, towarzyski, wyniosły | nauka 3/4 |
| [Gerhard 62635](../../02_POSTACIE/62635/karta.md) | 33 | Marszałek i rycerz; employer=62634 | zadowolony, wyniosły, umiarkowany | wojskowość 3/4; open_terrain_expert |
| [Gunzelin 65692](../../02_POSTACIE/65692/karta.md) | 32 | Mistrz intryg i rycerz; employer=62634 | leniwy, arbitralny, nieczuły | intryga 4/4; giant |
| [Helferich 58415](../../02_POSTACIE/58415/karta.md) | 51 | Duchowny w radzie; employer=62634 | niecierpliwy, towarzyski, sprawiedliwy | nauka 4/4; zapisany język łaciński |
| [Notker 62636](../../02_POSTACIE/62636/karta.md) | 29 | Dworzanin; zadanie kanclerskie w obserwacji 16 IX | wybaczający, gorliwy, lękliwy | nauka 4/4 |
| [Amalie 62637](../../02_POSTACIE/62637/karta.md) | 25 | Dworzanina; employer=62634 | chciwa, ufna, cierpliwa | zarządzanie 3/4 |
| [Emma 62638](../../02_POSTACIE/62638/karta.md) | 26 | Dworzanina; employer=62634 | mściwa, lękliwa, uczciwa | wojskowość 4/4; aggressive_attacker; depressed_genetic |

## Kompetencje — zapis bazowy

| Osoba | DIP | MAR | STE | INT | LEA | PRO | trait_xp_amounts |
|---|---:|---:|---:|---:|---:|---:|---|
| Burkhard 62634 | 3 | 5 | 4 | 5 | 0 | 8 | `[1, 1, 1]` |
| Ezzo 65691 | 5 | 9 | 4 | 6 | 4 | 2 | `[50, 50, 1]` |
| Konrad 45254 | 6 | 0 | 8 | 9 | 3 | 6 | `[1, 50, 1]` |
| Gerhard 62635 | 2 | 9 | 6 | 8 | 4 | 10 | `[1, 50, 1, 0]` |
| Gunzelin 65692 | 1 | 4 | 6 | 4 | 4 | 3 | `[1, 1, 50]` |
| Helferich 58415 | 6 | 3 | 10 | 2 | 6 | 0 | `[1, 1, 1]` |
| Notker 62636 | 5 | 9 | 2 | 3 | 5 | 7 | `[50, 1, 100]` |
| Amalie 62637 | 6 | 10 | 6 | 3 | 9 | 2 | `[50, 1, 50]` |
| Emma 62638 | 1 | 1 | 10 | 6 | 2 | 8 | `[1, 1, 1, 0]` |

Statystyki nie są końcowymi wartościami interfejsu. Edukacja, moralność, osobiste męstwo i specjalizacja dowódcza są oddzielnymi warstwami. Przekład education_X_N podaje dziedzinę i numer wariantu; nie dorabia historii ukończonej szkoły.

## 62634 Burkhard

**POTWIERDZONE_SAVE:** urodzenie `1050.7.27`, rola: Hrabia Hohenbergu. **OBLICZONE:** 16 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `ambitious`, `diligent`, `patient`, `education_stewardship_3`, `intellect_good_2`.

### Profil i napięcie wewnętrzne — WNIOSEK

Ambicja nadaje kierunek, pracowitość dostarcza sposobu działania, a cierpliwość może wydłużać horyzont. Ten zestaw uzasadnia młodego człowieka, który wraca do spraw i chce rozumieć, jak osiągnąć więcej. Może godzić się na zwłokę, jeśli dostrzega postęp. Najciekawszy punkt napięcia to różnica między długim zamiarem a krótkim doświadczeniem: ma szesnaście lat i nie znamy historii jego wychowania ani wcześniejszych obowiązków.

Cecha intellect_good_2 jest odrębną przesłanką zdolności intelektualnych. Nie zapewnia wszechwiedzy, erudycji ani dojrzałości emocjonalnej. Surowe LEA=0 nie odbiera mu inteligencji; inteligencja, wiedza i bazowa statystyka są różnymi warstwami. STE=4 nie unieważnia edukacji zarządczej. W prozie warto pozwolić mu dobrze uchwycić zależność, a następnie pytać o rzecz, której jeszcze nie zna.

### Kompetencje i konkretna sytuacja

Potwierdzono stewardship_wealth_focus od 16 IX oraz rozpoczęty tego dnia sway wobec Helfericha. To dwa rzeczywiste kierunki działania: sprawy majątkowe i zabieganie o stosunek duchownego. Pierwszy wskazany następca Hohenbergu to Rudolf. Nie ustala to, czy Burkhard już rozumie cały problem sukcesji i jak go przeżywa. Gracz zachowuje wybór działań; traits nie zastępują jego decyzji.

### Wskazówki do fabuły — propozycje

Można pokazywać go przy powracaniu do niewyjaśnionej kwestii, porównywaniu dwóch wyliczeń, spokojnym wysłuchaniu fachowca i późniejszym sprawdzeniu wyniku. Hipotetyczny rytm wypowiedzi: pytania konkretne, niekoniecznie elokwentne; ciekawość i chęć sprawdzenia odpowiedzi. Przy długiej zwłoce może pytać, jaki krok wykonano, zamiast natychmiast grozić.

**Warunkowy punkt nacisku:** jeżeli wysiłek nie przynosi żadnego uznania lub ktoś trwale blokuje awans, ambicja i pracowitość mogą wejść w konflikt z cierpliwością. Zmęczenie po ciężkiej pracy jest możliwym szczegółem sceny, nie potwierdzonym przepracowaniem. Nie dodawać obsesji na punkcie dynastii, chłodnego geniuszu, gotowego programu reform ani wymyślonej rodziny.

## 65691 Ezzo

**POTWIERDZONE_SAVE:** urodzenie `1039.5.2`, rola: Kanclerz; employer=62634. **OBLICZONE:** 27 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `fickle`, `impatient`, `shy`, `education_diplomacy_2`.

### Profil i napięcie wewnętrzne — WNIOSEK

Fickle opisuje skłonność do zmiany nastawienia, impatient potrzebę szybszego przebiegu spraw, shy trudność w ekspozycji społecznej. Może więc chcieć szybko zakończyć rozmowę, choć obowiązek wymaga cierpliwego uzgodnienia stanowisk. Nieśmiałość może dotyczyć sytuacji publicznej silniej niż znanej rozmowy we dwoje. Nie musi mówić mało w każdych okolicznościach.

Zmiana zdania nie dowodzi kłamstwa ani zdrady. Może oznaczać reagowanie na kolejne argumenty, wahanie wobec nacisku albo uleganie chwilowemu rozwiązaniu. Najlepszy profil nie sprowadza go do komicznie nieudolnego posła: ma edukację dyplomatyczną i powierzono mu konkretne zadanie.

### Kompetencje i konkretna sytuacja

DIP=5 i edukacja_diplomacy_2 wspierają przedstawienie przygotowania do kontaktów; nie pozwalają ustalić końcowej skuteczności w interfejsie. MAR=9 jest wyższe od DIP w surowym polu, co nie oznacza automatycznie kariery wojskowej. Jego dom jest zapisany jako dynn_Aargau, ID 12844; nie ustalono pozycji majątkowej tego rodu ani wcześniejszej służby. Kanclerzem jest Ezzo 65691, a nie Ezzo 45250 z Helfensteinu.

### Wskazówki do fabuły — propozycje

Dobrze nadaje się do scen, w których musi przekazać stanowisko hrabiego, rozpoznać cudzy zamiar albo uporządkować zbyt długą wymianę zdań. Możliwe środki: przygotowane sformułowanie, pytanie o jednoznaczny termin, większa swoboda po opuszczeniu licznego zgromadzenia. Takie zachowania pozostają propozycjami, a jąkanie, lęk społeczny jako diagnoza i napady paniki nie wynikają z shy.

**Warunkowy punkt nacisku:** niespodziewane pytanie publiczne, przeciągające się uzgodnienie albo dwa kolejno przekonujące stanowiska. Cierpliwy Burkhard może potrzebować, by Ezzo utrzymał ustaloną linię rozmowy. To potencjalna różnica stylu pracy, nie potwierdzony konflikt. Nie przedstawiać jego szybkiej decyzji jako świadomego sabotażu.

## 45254 Konrad

**POTWIERDZONE_SAVE:** urodzenie `1042.6.22`, rola: Zarządca; republikański posiadacz Rottweil. **OBLICZONE:** 24 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `callous`, `gregarious`, `arrogant`, `education_learning_3`.

### Profil i napięcie wewnętrzne — WNIOSEK

Towarzyskość może oznaczać łatwość nawiązywania kontaktów i potrzebę udziału w rozmowie. W połączeniu z wyniosłością może zwiększać znaczenie uznania, a nieczułość pozwala rozważać słabszą wrażliwość na cudzy koszt. Powstaje wiarygodny człowiek administracji, który umie być obecny między ludźmi, a zarazem może stawiać wynik lub rangę ponad prośbą o litość.

Gregarious nie jest dowodem szczerej serdeczności, callous nie jest dowodem sadystycznej przyjemności. Nie ustalono oszustwa. Warto dać mu rzeczowe argumenty i własną ocenę porządku, zamiast każde uprzejme zachowanie objaśniać jako maskę zbrodniarza.

### Kompetencje i konkretna sytuacja

STE=8, INT=9 i DIP=6 wskazują mocniejszy zapis bazowy w administracji, rozeznaniu i kontaktach niż MAR=0. Edukacja dotyczy nauki (3/4), a nie zarządzania; nie dopisywać kariery rachmistrza wyłącznie na jej podstawie. Jest posiadaczem Rottweil z republic_government i wasalem Burkharda, obecnie zarządcą. W obserwacji 16 IX miał zadanie rozbijania spisków. Zmiana zadania jest potwierdzona, jej motywacja nie.

Nie ma employer=62634 i zapis lokalizacji różni się od zapisów dworzan. Nie oznacza to, że nie bywa przy hrabim, ale wymaga ostrożności przy przedstawianiu stałej obecności w każdej scenie. Nie przyznano mu bez dowodu tytułu feudalnego barona ani stałego miejsca przy stole hrabiego.

### Wskazówki do fabuły — propozycje

Może przedstawiać interes miasta, podlegać hrabiemu i jednocześnie potrzebować zachowania własnej powagi. Dobre sytuacje: porównanie zobowiązań i możliwości płatnika, uzasadnienie odmowy, spotkanie z kilkoma stronami administracyjnej sprawy. Język można budować z uporządkowanych argumentów i świadomego adresowania ludzi.

**Warunkowy punkt nacisku:** publiczne pominięcie jego wiedzy, naruszenie uznawanej rangi lub prośba o ulgę, która utrudnia zadanie. Napięcie z Helferichem może wynikać z różnej wagi zasad i kosztu ludzkiego, lecz ich faktyczna rywalizacja pozostaje nieustalona.

## 62635 Gerhard

**POTWIERDZONE_SAVE:** urodzenie `1033.3.1`, rola: Marszałek i rycerz; employer=62634. **OBLICZONE:** 33 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `content`, `arrogant`, `temperate`, `education_martial_3`, `open_terrain_expert`.

### Profil i napięcie wewnętrzne — WNIOSEK

Content może wspierać akceptację własnego położenia, arrogant potrzebę szacunku, a temperate powściągliwość w korzystaniu z przyjemności. Zestaw pozwala zbudować człowieka zadowolonego z odpowiedzialnej funkcji, który nie potrzebuje wyższego tytułu, ale źle przyjmuje lekceważenie umiejętności. Zadowolenie i wyniosłość mogą współistnieć: pierwsze dotyczy osiągniętej pozycji, drugie sposobu jej uznawania.

Umiarkowanie nie oznacza automatycznie spokojnego temperamentu w każdej sprawie. Content nie gwarantuje lojalności wobec konkretnego pana. Wysoka sprawność nie ustanawia odwagi, a w zapisanym zestawie nie ma brave.

### Kompetencje i konkretna sytuacja

MAR=9, PRO=10, wojskowa edukacja 3/4 oraz open_terrain_expert wspierają profil człowieka przydatnego w wojskowej codzienności. Specjalizacja dotyczy otwartego terenu; nie dowodzi wygranej bitwy ani doświadczenia w konkretnej kampanii. Jest marszałkiem i ma knight=yes. Na 16 IX wykonywał zadanie podatkowe, a na 18 IX organizuje wojska. Nie dopowiedziano przyczyny przeniesienia ani awansu w osobistej hierarchii.

### Wskazówki do fabuły — propozycje

Najbardziej użyteczny przy sprawdzaniu wyposażenia, wysłuchaniu raportu, rozdzieleniu obowiązków i ocenie warunków działania — o ile scena nie tworzy nowej wyprawy lub mobilizacji. Możliwy rytm wypowiedzi: krótki, konkretny, pewny w obrębie zadania. DIP=2 pozwala ostrożnie zakładać mniej finezyjny styl perswazji, lecz nie dowodzi grubiaństwa.

**Warunkowy punkt nacisku:** żądanie wojskowego działania bez uwzględnienia fachowej uwagi albo publiczne traktowanie go jak wymiennego sługi. Relacja z szesnastoletnim Burkhardem może opierać się na uznaniu kompetencji; ojcostwo zastępcze, przyjaźń i staż służby są nieustalone. Nie dopisywać ran, dawnej bitwy ani przysięgi osobistej tylko dla nadania mu charakteru weterana.

## 65692 Gunzelin

**POTWIERDZONE_SAVE:** urodzenie `1034.3.10`, rola: Mistrz intryg i rycerz; employer=62634. **OBLICZONE:** 32 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `lazy`, `arbitrary`, `callous`, `education_intrigue_4`, `giant`.

### Profil i napięcie wewnętrzne — WNIOSEK

Lazy może oznaczać unikanie nadmiernego wysiłku, arbitrary większą gotowość do własnego uznania niż jednolitej reguły, callous słabszą wrażliwość na cudze cierpienie. Zestaw uzasadnia człowieka szukającego wygodnego i skutecznego sposobu działania. Nie musi odrzucać każdego obowiązku: może wykonywać to, co uważa za najważniejsze, a pomijać żmudny szczegół.

Lenistwo i wysoka edukacja intrygancka nie wykluczają się. Rozróżnienie przygotowania i sumienności daje bardziej użyteczny profil niż etykieta genialnego szpiega. Nieczułość nie dowodzi zamiaru mordu, a arbitralność nie ustala jego stosunku do wszystkich przysiąg.

### Kompetencje i konkretna sytuacja

Jest mistrzem intryg, prowadzi task_disrupt_schemes i figuruje jako rycerz. Edukacja intrygancka ma wariant 4/4, ale bazowe INT=4; końcowej wartości nie odczytano. PRO=3 mimo giant wymaga osobnego traktowania cechy cielesnej i sprawności. Giant jest potwierdzonym traitem, nie pomiarem wzrostu, siły ani gwarancją dominacji w walce. Dom dynn_Nordgau 12845 nie dowodzi wpływowej sieci rodzinnej.

### Wskazówki do fabuły — propozycje

Może wnosić do scen bezpieczeństwa pytanie o praktyczny wynik, zgłaszać wątpliwość wobec nadmiaru procedur lub wybierać mniejszy zakres sprawdzenia. Z punktu widzenia Burkharda ważne jest ustalenie, co Gunzelin rzeczywiście sprawdził. To dobry temat kontroli obowiązków bez tworzenia spisku, którego zapis nie potwierdza.

**Warunkowy punkt nacisku:** długie zadanie bez wyraźnego wyniku, żądanie identycznego potraktowania każdej sprawy albo apel o dodatkowy wysiłek wyłącznie z troski o cudze uczucia. Możliwe napięcie z pracowitym hrabią i sprawiedliwym Helferichem nie oznacza już istniejącej wrogości. Nie uczynić go domyślnym zdrajcą lub katem całego dworu.

## 58415 Helferich

**POTWIERDZONE_SAVE:** urodzenie `1015.4.11`, rola: Duchowny w radzie; employer=62634. **OBLICZONE:** 51 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `impatient`, `gregarious`, `just`, `education_learning_4`.

### Profil i napięcie wewnętrzne — WNIOSEK

Just daje podstawę przywiązania do zasad i równej miary; gregarious sprzyja kontakcie z ludźmi; impatient może skracać cierpliwość do przeciągania spraw. Może być więc duchownym, który chce spór nazwać, wysłuchać strony i doprowadzić do rozstrzygnięcia. Sprawiedliwość może prowadzić zarówno do surowego zastosowania reguły, jak i sprzeciwu wobec wybiórczej pobłażliwości.

Nie ma potwierdzonej cechy zealous. Rola duchowna, katolicki obrządek i edukacja nie wystarczają do przypisania fanatyzmu. Just nie gwarantuje łagodności, a towarzyskość nie sprawia, że zawsze będzie skłonny ustąpić hrabiemu.

### Kompetencje i konkretna sytuacja

Ma 51 lat; jest najstarszy w tej dziewięcioosobowej grupie. Zapisano edukację w nauce 4/4, LEA=6, STE=10 i DIP=6. Wśród języków ma wysokoniemiecki i łacinę; łaciny nie dopisano pozostałym wyłącznie z racji edukacji. Wykonuje task_religious_relations, a Burkhard prowadzi wobec niego sway od 16 IX. Nie odczytano końcowej opinii ani skutku tego działania.

### Wskazówki do fabuły — propozycje

Może łączyć funkcję religijną z udziałem w sprawach, które wymagają uporządkowania reguł i odpowiedzialności. Dobre sytuacje: wysłuchanie petycji, nazwanie sprzeczności w argumentach, ustalenie jednakowej miary dla dwóch osób. Nie wpisywać mu samodzielnie urzędu nauczyciela, spowiednika Burkharda ani opiekuna z dzieciństwa.

**Warunkowy punkt nacisku:** jawne zastosowanie dwóch różnych zasad do podobnych spraw lub unikanie odpowiedzi przez władzę. W stosunku do młodego hrabiego można rozważać zderzenie wieku i formalnej rangi, jednak osobisty autorytet oraz szacunek Burkharda muszą zostać pokazane lub potwierdzone. Nie znać mu automatycznie cudzych sekretów, tylko dlatego że jest duchownym.

## 62636 Notker

**POTWIERDZONE_SAVE:** urodzenie `1037.9.15`, rola: Dworzanin; zadanie kanclerskie w obserwacji 16 IX. **OBLICZONE:** 29 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `forgiving`, `zealous`, `craven`, `education_learning_4`.

### Profil i napięcie wewnętrzne — WNIOSEK

Forgiving pozwala rozważać większą gotowość do odpuszczenia osobistej urazy; zealous silniejsze znaczenie wiary; craven ostrożność wobec zagrożenia. Może przebaczać człowiekowi, nie aprobując jego działania, oraz bronić zasad, gdy bezpośrednie ryzyko nie spoczywa na nim. W sytuacji zagrożenia może szukać bezpiecznego sposobu dochowania przekonania.

Lękliwość nie czyni go pozbawionym rozumu ani nie odbiera każdej formy odwagi moralnej. Gorliwość nie ustanawia konkretnego programu prześladowań, a wybaczanie nie oznacza zaniknięcia różnic religijnych. Napięcie należy prowadzić przez wybór kosztu i sposobu działania.

### Kompetencje i konkretna sytuacja

Ma 29 lat i wariant edukacji w nauce 4/4, przy bazowym LEA=5. MAR=9 nie dowodzi gotowości do osobistego wejścia w walkę. Jest dworzaninem, na 16 IX wykonywał task_foreign_affairs; na 18 IX wykonawcą jest Ezzo. Nie zapisano przyczyny zmiany, a Notker pozostał employer=62634. Nie wolno ustanowić jego upokorzenia, zazdrości ani przebaczenia decyzji, której znaczenia dla niego nie odczytano.

### Wskazówki do fabuły — propozycje

Może być użyteczny przy zastrzeżeniu sumienia, wskazaniu bezpieczniejszego wariantu czynności albo poparciu pojednania w osobistej sprawie. Możliwy sposób mówienia: odwołanie do zasady i dopiero potem pytanie o odpowiedzialność lub ryzyko. Nie robić z każdej jego wypowiedzi kazania.

**Warunkowy punkt nacisku:** obowiązek stawienia czoła groźbie osobiście, przy jednoczesnym przekonaniu, że ustąpienie byłoby moralnie niewłaściwe. Z Helferichem może dzielić sprawy religijne, lecz Helferich kieruje się także zapisaną sprawiedliwością i kontaktem społecznym. Nie ustalono ich przyjaźni, rywalizacji o urząd ani zgodności poglądów. Wysokiego XP w tablicy nie nazwano bez mapowania natężeniem konkretnej cechy.

## 62637 Amalie

**POTWIERDZONE_SAVE:** urodzenie `1040.11.19`, rola: Dworzanina; employer=62634. **OBLICZONE:** 25 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `greedy`, `trusting`, `patient`, `education_stewardship_3`.

### Profil i napięcie wewnętrzne — WNIOSEK

Greedy nadaje znaczenie korzyściom i posiadaniu, trusting pozwala rozważać łatwiejsze przyjmowanie zapewnień, patient wydłuża tolerancję oczekiwania. Możliwy jest zatem człowiek zainteresowany zdobywaniem zasobów, lecz niewymuszający natychmiastowej zapłaty i skłonny zaufać obietnicy. Chciwość nie musi wyrażać się gwałtownym żądaniem; może dotyczyć długiego trzymania się korzystnego zamiaru.

Ufność i interesowność mogą współistnieć. Nie czynią jej automatycznie naiwnej ani pozbawionej własnego interesu. Z takiego profilu wynika możliwość przecenienia wiarygodności obietnicy, a nie pewny los ofiary oszustwa.

### Kompetencje i konkretna sytuacja

Ma 25 lat, jest dworzaniną bez potwierdzonego aktualnego urzędu rady. Edukacja dotyczy zarządzania 3/4; zapis STE=6, LEA=9, MAR=10 i PRO=2. MAR=10 jest istotnym parametrem, lecz nie potwierdza dowodzenia, służby rycerskiej ani przebytej wojny. PRO=2 przypomina o odrębności kierowania działaniem i osobistej sprawności. Nie zapisano jej domeny, małżonka ani własnego dochodu; brak nie rozstrzyga pełnej biografii.

### Wskazówki do fabuły — propozycje

Może uczestniczyć w scenach oceny korzyści, cierpliwego oczekiwania na spełnienie zapewnienia lub sporu o to, komu uwierzyć. Jest to potencjał postaci, a nie przyznanie jej bez źródła opieki nad spiżarnią, skarbcem lub gospodarstwem. Cierpliwość zbliża ją jakościowo do Burkharda, ale cele i rodzaj oceny obietnic mogą się różnić.

**Warunkowy punkt nacisku:** długotrwałe pozbawienie obiecanej korzyści albo konieczność odrzucenia słowa osoby, której ufa. Możliwa różnica z Gunzelinem dotyczy jego arbitralności i jej ufności; nie tworzyć romansu, przyjaźni lub planu wykorzystania. Odczytano sexuality=ho, lecz w tej analizie zachowano kod bez ustalania partnera lub powszechnej wiedzy dworu o orientacji.

## 62638 Emma

**POTWIERDZONE_SAVE:** urodzenie `1040.6.8`, rola: Dworzanina; employer=62634. **OBLICZONE:** 26 lat na 18 IX. Kultura swabian; obrządek roman_rite związany z catholic.

**Zapisane traity:** `vengeful`, `craven`, `honest`, `education_martial_4`, `aggressive_attacker`, `depressed_genetic`.

### Profil i napięcie wewnętrzne — WNIOSEK

Honest pozwala rozważać znaczenie prawdy, vengeful pamiętanie krzywdy i potrzebę odpowiedzi, craven ostrożność wobec osobistego ryzyka. Może długo pamiętać doznaną niesprawiedliwość i otwarcie nazwać fakt, a jednocześnie unikać sytuacji, w której odpowiedź grozi jej bezpośrednio. Uczciwość nie jest synonimem łagodności; pamiętanie urazy nie oznacza, że dopuści się kłamstwa.

Warto rozdzielić pamięć krzywdy od konkretnego czynu zemsty. Przywrócenie prawdy, odmowa zaufania lub domaganie się uznania szkody są propozycjami możliwych reakcji. Nie znamy żadnej zapisanej krzywdy ani osoby, wobec której Emma żywiłaby urazę.

### Kompetencje i konkretna sytuacja

Ma 26 lat; jest dworzaniną bez odczytanego urzędu. Wojskowa edukacja 4/4 i aggressive_attacker należą do warstwy przygotowania i specjalizacji, nie do odwagi lub moralności. Bazowe MAR=1 wyraźnie różni się od wysokiego poziomu edukacji, natomiast STE=10 i INT=6 pokazują inne zapisane mocniejsze dziedziny. Nie dopowiedziano powodu tego zestawu ani niespełnionej kariery wojskowej.

Zapisany depressed_genetic jest cechą depresji w wariancie o takim kluczu. Nie ustala bieżącego natężenia cierpienia, jego przyczyny, stałej niezdolności do działania ani konkretnych objawów. Nie wyprowadzono diagnozy współczesnej, traumatycznej przeszłości lub myśli samobójczych. Cecha pozostaje jedną z warstw postaci, razem z jej kompetencjami i wyborami.

### Wskazówki do fabuły — propozycje

Przydatna przy odmowie potwierdzenia nieprawdziwej wersji sprawy, rozróżnieniu wybaczenia i pamięci lub ostrożnym domaganiu się naprawienia krzywdy. Można rozważać wypowiedź precyzyjną i pamiętanie wcześniejszych słów, jeśli zostaną ustanowione w scenach. Nie nadawać jej rozpoznawalnego smutku w każdym kadrze.

**Warunkowy punkt nacisku:** nacisk na kłamstwo w sprawie, która jej dotyczy, albo wymóg osobistej konfrontacji z silniejszą stroną. Notker może stanowić kontrapunkt w podejściu do przebaczenia; brak dowodu ich konfliktu. Nie przedstawiać Emmy jako agresywnej wojowniczki wyłącznie na podstawie nazwy specjalizacji.

## Zespół jako układ różnych interesów — WNIOSEK

Dwór może być interesujący dzięki odmiennej ocenie tej samej zwykłej sprawy. Każdej osobie dawać cel czynności, zakres wiedzy i możliwość zmiany stanowiska pod wpływem sytuacji. Nie wszyscy muszą jednocześnie zabierać głos, a wspólna obecność wymaga uzasadnienia.

| Para / układ | Potwierdzona podstawa | Możliwe napięcie lub współpraca | Co pozostaje nieustalone |
|---|---|---|---|
| Burkhard – Gerhard | Hrabia / marszałek; ambicja i pracowitość / zadowolenie i wyniosłość | Kierunek wyznaczany przez młodego pana i potrzeba uznania fachowej uwagi | Zaufanie, wcześniejsza służba, zastępcze ojcostwo |
| Burkhard – Gunzelin | Hrabia / mistrz intryg; diligent / lazy | Dokładność i wysiłek przeciw sposobowi skracania pracy | Zaniedbanie lub osobista wrogość |
| Burkhard – Ezzo | Hrabia / kanclerz; patient / impatient i fickle | Utrzymywanie celu podczas zmieniających się propozycji i nacisków | Skutek konkretnej rozmowy, lojalność |
| Konrad – Helferich | Zarządca / duchowny; callous i arrogant / just | Koszt zadania, reguła traktowania stron i prawo do uznania | Spór podatkowy, rywalizacja, wspólne decyzje |
| Notker – Helferich | Dworzanin / duchowny; zealous i forgiving / just i impatient | Zgodność w części kwestii religijnych przy różnym stosunku do przebaczenia i terminu rozstrzygnięcia | Poglądy doktrynalne, przyjaźń, konflikt o urząd |
| Notker – Emma | forgiving / vengeful; oboje craven | Odpuszczenie osobistej urazy i pamięć szkody, przy szukaniu bezpiecznej reakcji | Faktyczna krzywda i ich relacja |
| Amalie – Konrad | trusting, greedy, patient / gregarious, callous, arrogant | Ocena zapewnienia i korzyści wobec osoby umiejącej prowadzić kontakty | Wykorzystanie, oszustwo, finansowy układ |

Te pary są narzędziem kompozycji, nie listą sojuszy i wrogów. Postacie mogą współpracować mimo różnic; różnice nie muszą za każdym razem prowadzić do konfliktu.

## Materiał do scen bez dopisywania wydarzeń

1. **Sprawdzenie zwykłej sprawy administracyjnej:** Burkhard pyta o podstawę, Konrad porządkuje interesy, Helferich może pytać o jednakową miarę. Konkretna petycja, decyzja i rezultat są do ustanowienia przez źródło lub autora jako oznaczona narracja.
2. **Obowiązek wojskowy w codzienności:** Gerhard wnosi fachową uwagę, hrabia słucha i wybiera. Nie tworzyć bitwy, wyprawy, nowych oddziałów lub mobilizacji bez potwierdzenia.
3. **Uzgadnianie stanowiska do kontaktów:** Ezzo pracuje nad formą przekazu; Burkhard może pilnować stałości celu. Nie wymyślać cesarskiego poselstwa ani udanego sojuszu.
4. **Rozmowa po zmianie zadania Notkera:** zmianę między zapisami można odnotować, lecz jego emocje i jej przyczynę trzeba dopiero wiarygodnie ustanowić w narracji. Zazdrość nie jest domyślna.
5. **Przekazanie trudnej wiadomości:** różne podejście do prawdy, urazy i odpowiedzialności pozwala włączyć Emmę, Notkera lub Gunzelina. Sama wiadomość i zakres jej znajomości muszą mieć podstawę.

Są to konteksty użycia postaci, nie napisane sceny. Właściwe opowiadanie pozostaje pracą dla modelu wskazanego w zasadach projektu.

## Ograniczenia i dane dodatkowe

- Aktualny stres: nie znaleziono jawnej wartości w odczytanych alive_data; nie zapisano zera, traumy ani załamania.
- Nie ustalono wyglądu z portretów w tej analizie. Ethnicity, mass i DNA nie służą do tworzenia opisu twarzy. Giant i depressed_genetic są traitami, a nie wizualną oceną osoby.
- Orientacja: Amalie i Konrad mają jawne sexuality=ho. Zachowano kod; brak pola u pozostałych nie uprawnia do ustanowienia orientacji domyślnej. Nie ustalono partnerów, romansów, ujawnienia lub sekretu. Interpretację kodu potwierdzić w panelu przy opracowaniu wątku uczuciowego.
- Burkhard ma memory 4377 typu ascended_throne_memory z creation_date=1066.9.16. Rekord zawiera również reason=revoked i flavor_character=38610. Nie przekształcono tych pól w opowieść o odebraniu ziem lub usunięciu poprzednika bez pełnej interpretacji kontekstu.
- Postacie mają zapisany język language_high_german; Helferich także language_latin. Z tego nie wyprowadzono stylu pisma, umiejętności czytania, wykształcenia w konkretnej instytucji lub jednolitego akcentu.
- Nazwy traits i bazowe liczby nie są diagnozą ani niezmiennym scenariuszem. Przy każdej nowej obserwacji można zaktualizować interpretację, zachowując wcześniejszą datę.

[Transkrypcja nowych pól, pamięci i schematu](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/charaktery_hohenberg_1066-09-18.json) · [Metoda](../../baza/mechaniki/Metoda-charakterow.md) · [Dwór](../../04_OTOCZENIE_WLADCY/indeks_dworu.md).
