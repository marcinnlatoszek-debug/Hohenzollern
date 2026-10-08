# Baza żyjącego świata Hohenzollernów

**GRA DAJE FAKT, KRONIKA DAJE ŻYCIE.** Ta baza porządkuje ludzi, pokrewieństwa, stany kart i źródła, a następnie służy do prowadzenia ciągłych scen. Nadrzędny kanon: [Historia-Hohenzollern.md](../Historia-Hohenzollern.md). Dane: [swiat.json](swiat.json).

Stan początkowy z 7 października 2026: **69 osób, 48 relacji, 6 drzew dynastii, 67 zapisów stanu, 25 odczytów screenów, 16 historycznych wpisów chronologii i 4 wnioski z podanymi przesłankami**. Rejestr źródeł obejmuje 51 fotografii kampanii oraz fotografię klawiatury wyłączoną z kanonu. Majowe oryginały nie zostały ponownie otwarte; wykorzystano ich zapis z sekcji 17. Dane nie oznaczają 69 pełnych kart ani 69 osób żyjących na najnowszą datę.

## Priorytet natywnego save’a — od 8 października 2026

**Najnowszy natywny plik .ck3 jest źródłem bieżącej prawdy mechanicznej i ma pierwszeństwo przed screenshotami.** Wyraźne rzadkie poprawki autora, jak **Friedrich Hohenberg / dynastia Hohenberg**, są nadrzędne dla nazwy i tożsamości kanonicznej, ale nie zmieniają ID mechanicznych. Każdy kolejny save wpisywać niezwłocznie do [kanonu](../Historia-Hohenzollern.md) i `swiat.json`, zachowując historyczne migawki. **Aktualny save: 24 września 1070**, atlas księstwa: [Szwabia-1070-09-24.md](Szwabia-1070-09-24.md). Narrator może wykrywać zagrożenia i zapowiadać możliwe skutki, lecz nie dopisuje jako faktów przyszłych wojen, zdrad ani sukcesji.

## Polityczne otoczenie księstwa

Wczytano regionalny atlas oparty na save’ie z **24 września 1070**: [Sąsiedzi Szwabii — wojny, frakcje, sukcesje](Sasiedzi-Szwabii-1070-09-24.md). Dane strukturalne: `swiat.json:neighboring_regions_current_state`. Obejmuje 14 istotnych księstw i rozbieżności zwierzchnictwa de iure/de facto; uwzględnia m.in. trwającą wojnę o Nordgau oraz frakcję przeciw księciu Annonowi. Nie przenosić tajnych informacji z save’a do wiedzy postaci bez uzasadnionego zdarzenia.

## Jak czytać bazę

| Część | Zawartość |
|---|---|
| `people` | Stała tożsamość osoby, warianty imienia, kotwica wieku, biografia i karta życia |
| `relationships` | Osobno rodzic–dziecko, małżeństwo, rodzeństwo, zależność wasalna i sojusz; data obserwacji i źródło |
| `snapshots` | Datowane i niedatowane stany urzędów, opinii, cech, umiejętności, domu i dynastii |
| `dynasties` | Nazwa dynastii oraz datowany licznik i renoma; lista osób nie jest pełnym spisem dynastii |
| `sources`, `observations` | Pochodzenie informacji, nazwa pliku, identyfikator zdjęcia, odczyt i granica pewności |
| `chronology` | Historyczne wpisy z kanonu; zachowane sformułowania dat, bez automatycznego przypisywania lat |
| `inferences` | Wnioski logiczne z odsyłaczami do relacji będących przesłankami |
| `narrative_events` | Pamięć rozegranych scen; obecnie pusta, bo wcześniejszych opowiadań nie odzyskano w całości |
| `future_checks`, `conflicts` | Terminy do sprawdzenia i konkretne rozbieżności wymagające danych |

`null` oznacza NIEUSTALONE. Puste wspomnienia nie oznaczają amnezji bohatera: nie mamy jeszcze utrwalonego tekstu scen. Znane wydarzenia biograficzne pozostają w kanonie i polu ciągłości. Dom i dynastia są osobnymi informacjami. P01–P22 zachowują wcześniejsze identyfikatory; kolejnych nie renumerować.

## Przyjęcie każdego nowego screena

1. Nadać źródłu trwały ID, zapisać nazwę i dokładny identyfikator pliku. Zaznaczyć, czy oryginał jest tylko poza repozytorium, czy został rzeczywiście zachowany w repozytorium. Obecnie obrazy nie są przechowywane w GitHubie; są tam odczyty i odsyłacze do źródeł.
2. Odczytać datę gry z interfejsu. Gdy jej brak, pozostawić `null`. Nie używać daty przesłania jako daty kampanii.
3. Dopasować osobę po imieniu, tytule, rodzinie i innych widocznych danych. Nowej osobie przydzielić następny wolny Pxx. Nie scalać imienników na podstawie samego imienia. Nierozpoznaną kartę zachować w `pending_inputs`.
4. Zapisać odczyt oraz jego osoby i źródła. Dodać nowy stan lub relację, zachowując starsze wartości. Różnica między dwoma datowanymi ekranami jest zmianą stanu; nie wyjaśnia automatycznie przyczyny.
5. Odczytać dokładnie pokrewieństwo z drzewa. Potem wyprowadzić relacje pośrednie: wuj, ciotka, kuzyn, powinowaty. Wniosek przechowuje przesłanki i zakres. Sojusz, sympatia i prawa sukcesyjne wymagają osobnych danych.
6. Rozbieżność bez rozstrzygającej daty lub tooltipu wpisać do `conflicts`; żadnego źródła nie usuwać jako niewygodnego.
7. Zaktualizować kanon i bazę w tej samej sesji. Przy zmianie ich treści opisać wspólny punkt gry i źródła w historii GitHuba. Kanon ma pierwszeństwo; wykrytą rozbieżność bazy poprawić przed sceną.
8. Przekazać graczowi krótko: nowe fakty, nowe koneksje rodzinne, istotne zmiany oraz spokojne wnioski logiczne. Prognozy polityczne pozostają analizą w tle zgodnie z kanonem.

## Karta wirtualnego życia

Każda postać ma `life.basis` łączące ją z jej relacjami, kartami i obserwacjami. To podstawa indywidualnego prowadzenia: nie ma wymogu pełnej karty, żeby postać wystąpiła, ale zakres narracji zależy od tego, co wiadomo. Krewny znany wyłącznie z drzewa otrzymuje ostrożne przedstawienie, bez wymyślania jego wieku, cech czy całej przeszłości.

Przy pierwszej scenie ustalić i zapisać **literacki głos, rytm dnia i bieżące dążenia** na podstawie znanych cech, wieku, rodziny i obowiązków. Oznaczyć je jako NARRACJA i później prowadzić konsekwentnie. Statystyka jest wskazówką zakresu kompetencji, nie gotową osobowością; profil UI nie zastępuje wszystkich cech. Cele narracyjne nie są nowymi decyzjami zapisanymi przez grę.

Przed kolejną sceną sprawdzić datę, etap życia, zdrowie z ostatniego źródła, rodzinę, obowiązki, miejsce i wiedzę. Postać może pamiętać obietnicę, upokorzenie, życzliwy gest czy wiadomość dopiero po utrwalonym zdarzeniu i wiarygodnym sposobie uzyskania informacji. Dialogi wynikają również z tych wspomnień, nie tylko z bieżącego ekranu.

Po każdej scenie dopisać do `narrative_events`: ID, datę i miejsce, uczestników, krótki przebieg, kto czego się dowiedział, obietnice, nierozstrzygnięte sprawy i koniec sceny. W `life` uczestników dopisać odsyłacze do wydarzenia, ich własne wspomnienia i zmiany literackich dążeń. Zachować różnice punktów widzenia. Nie nadawać wszystkim wiedzy narratora.

Przy przesunięciu czasu świat zachowuje ludzi poza kadrem: obowiązki, opiekę nad dziećmi, służbę, modlitwę, ćwiczenia, gospodarstwo i czas podróży. Rytm ten można przedstawiać literacko. Narodziny, zgon, małżeństwo, choroba, wojna, nowa mechaniczna relacja i ukończenie budowy wymagają faktu z gry albo jednoznacznego potwierdzenia gracza.

Wiek liczyć z potwierdzonej daty urodzenia. Przy wieku z datowanej karty używać przedziału; przy karcie niedatowanej zachować wiek przy źródle. Dzieci rozwijają się odpowiednio do etapu życia; nie pozostają wiecznie niemowlętami. Śmierć kończy oś życia, lecz osoba pozostaje w genealogii i pamięci innych.

## Już rozpoznane koneksje

| Wniosek | Podstawa | Granica |
|---|---|---|
| Rudolf i Adalbert są braćmi | Wspólny ojciec Kuno | Matki nieustalone |
| Hartmann z Zurychu jest wujem Ferdinanda | Brat Hedwig, matki Ferdinanda | Nie dowodzi opieki ani sojuszu |
| Hedwig jest ciotką syna Hartmanna | Rodzeństwo i potwierdzone ojcostwo | Nie dowodzi osobistej bliskości |
| Burkhard jest powinowatym Hartmanna | Małżeństwo z Hedwig | Nie zmienia dynastii Burkharda |

## Czas i wznowienie

Najnowszy zapisany punkt gry: **6 maja 1070**. Ostatni zgłoszony punkt kroniki: **1 maja 1070**. Przy wznowieniu czytać aktualny kanon i bazę, a następnie sprawdzić nowy screen. Upływ czasu w świecie wynika z kampanii i scen; upływ rzeczywistych godzin nie przesuwa gry.

Baza jest trwałą pamięcią i podstawą prowadzenia świata w kolejnych sesjach. Sama obecność danych na GitHubie nie uruchamia symulacji w tle. Właściwe opowiadania mają otrzymywać pakiet z faktami, czasem, ludźmi i pamięcią scen zgodnie z sekcją 16 kanonu.

Kontrola początkowa: unikalność ID, poprawne odsyłacze osób i źródeł, odsyłacze przesłanek wniosków oraz brak cyklu rodzic–dziecko. Przed publikacją porównano zapis z odczytem GitHuba.
