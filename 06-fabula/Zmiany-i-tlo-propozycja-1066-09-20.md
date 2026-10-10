# Burkhard — zmiany między 18 a 20 września 1066
Źródła: „von_Hohenzollern(1).ck3” i „von_Hohenzollern(2).ck3”. Najnowszy stan: **20.09.1066**, wersja 1.20.0.4. Oba zapisy odczytano i porównano lokalnie. Starszy „von_Hohenzollern.ck3” służy wyłącznie do ustalenia, które zmiany wojskowe zaszły wcześniej.

**Ustalenie użytkownika obowiązujące w narracji:** Burkhard odziedziczył całe władztwo i rozpoczął rządy w sierpniu 1066. Ojciec: Konrad. Dziadek: Ludwig. Techniczne daty początku rządów oraz wpisy revoked nie zastępują tego przebiegu kampanii.

## 1. Najważniejsza zmiana: własny kierunek rządów
Dnia 20 września Burkhard wybiera **stewardship_wealth_focus**, koncentrację na bogactwie w ramach zarządzania. W poprzednim rekordzie brak pola focus. W nowym widnieją date=1066.9.20, changes=1 i progress=0. Doświadczenie wszystkich stylów życia nadal wynosi 0 w odczytanych polach.

**Fakt:** wybrano koncentrację.
**Wniosek:** Burkhard nadaje rządom kierunek gospodarczy.
**Nieustalone:** nie wybrano na tej podstawie całego drzewa umiejętności; nie potwierdzono wykupionych perków, nowego prawa podatkowego, wymuszenia danin lub udzielonej pożyczki.

W zestawieniu z ambicją, pracowitością, cierpliwością i edukacją zarządzania wybór jest charakterologicznie spójny. Nie musi oznaczać chciwości: cecha greedy nie pojawia się u Burkharda. Bogactwo może służyć bezpieczeństwu odziedziczonego domu, a nie wyłącznie osobistemu gromadzeniu pieniędzy.

## 2. Nowa cecha ogrodnika
Do listy cech dochodzi **lifestyle_gardener**. Pozostałe cechy osobowości, inteligencja i edukacja są takie same. To osobna cecha stylu życia; nie zastępuje cierpliwości ani pracowitości i nie oznacza nowej edukacji.

Nie odczytano tekstu wydarzenia, wyboru, nauczyciela ani dnia nabycia cechy w osobnym dzienniku. Jest obecna 20 września, a brakowało jej w poprzednim save’ie. **Uzupełnienie po sprawdzeniu dokumentacji:** oficjalna mechanika By God Alone nadaje ogrodnika po przyjęciu osobistego Ora et Labora. Ponieważ oba wpisy pojawiają się razem, jest to najbardziej prawdopodobne wyjaśnienie. Nie twierdzę, że Burkhard w dwa dni nauczył się całego ogrodnictwa albo zbudował rozległy ogród.

**Interpretacja fabularna:** zainteresowanie ziemią i cierpliwą pracą można osadzić w jego wcześniejszym wychowaniu. Gra teraz wyróżnia to zainteresowanie cechą. W poniższej scenie zajmuje się istniejącymi grządkami, co jest autorskim dopowiedzeniem, a nie potwierdzonym nowym budynkiem.

Nie podaję dokładnych premii tej cechy bez definicji zgodnych z modami kampanii.

## 3. Dochód rośnie, skarbiec jeszcze nie
| Pole | 18.09 | 20.09 | Różnica |
|---|---:|---:|---:|
| income Burkharda | 5,87996 | 6,81698 | +0,93702, około 15,94% |
| Złoto | 94 | 94 | 0 |
| Dochód posiadłości, prowincja 2763 | 3,16801 | 3,34320 | +0,17519 |
| Dochód posiadłości, prowincja 2759 | 2,71195 | 2,85406 | +0,14211 |

Nie utożsamiamy pola income z dochodem netto. Dwa dni nie uzasadniają opowieści o zgromadzonym nowym majątku. Wzrost pasuje do wyboru gospodarczego kierunku i przeliczenia modyfikatorów, ale nie dowodzi, że dokładnie jeden efekt odpowiada za całą różnicę.

Listy budynków w porównanych posiadłościach są identyczne. Nie powstała potwierdzona nowa inwestycja. W prozie nie opisuję ukończenia nowego młyna, przebudowy zamku ani zasadzenia wielkiego sadu.

Złoto 94, prestiż 600, pobożność 50, wpływ 60 i legitymizacja 200 pozostają takie same. Nie nastąpił udokumentowany skok zasobów osobistych.

## 4. Wojsko: ważne rozróżnienie decyzji i przeliczenia
| Pole całkowitej siły | 18.09 | 20.09 |
|---|---:|---:|
| current_strength | 945 | 835 |
| strength | 1455 | 1135 |
| levy | 333 | 333 |
| strength_for_liege | 20 | 20 |

Spadek wynosi 110 w bieżącej i 320 w docelowej sile. Nie jest dowodem przegranej bitwy ani strat w wojnie.

**Regimenty w save’ach (1) i (2) są takie same:**

| Regiment | Stan obecny | Stan maksymalny | Przypisane origin |
|---|---:|---:|---|
| Lekka piechota | 100 | 200 | Brak |
| Piechota pancerna | 200 | 400 | 2763 |
| Pikinierzy | 200 | 200, zapis size | 2759 |
| Mangonele, wcześniejszy regiment ID 16796406 | Brak aktywnego regimentu | — | — |

Wartość size=200 u pikinierów różni się formatem od chunks; nie przedstawiam jej jako nowego powiększenia.

**Chronologia:** w pierwszym, pierwotnym save’ie były mangonele 10/20 oraz pikinierzy 300/500. Już w „von_Hohenzollern(1).ck3” mangonele mają wpis none, pikinierzy size=200, a piechota pancerna i pikinierzy mają origin. Najnowszy save nie pokazuje ponownego rozwiązywania tych samych oddziałów.

Dlatego najbardziej spójne wyjaśnienie spadku sumarycznej siły między (1) a (2) to **aktualizacja sum po wcześniejszej redukcji**. To wniosek z zgodności danych regimentów, nie odczyt kodu przeliczającego.

Łącznie aktywne regimenty zawierają 500 i mają 800 w pojemności zapisanej. Dodanie levy=333 daje 833/1133; pola zbiorcze wynoszą 835/1135. Różnicy 2 nie ukrywam i nie przypisuję jej na pewno konkretnej kategorii. Dwaj rycerze pozostają ci sami: Humbert von Breisgau i Humbert von Venis.

**Znaczenie fabularne wcześniejszej redukcji:** hrabia ogranicza przygotowanie do kosztownej wyprawy oblężniczej, a zachowuje rdzeń ludzi pod bronią. Można pisać o wyborze oszczędności i porządku we własnej domenie. Nie oznacza to gwarantowanego bezpieczeństwa ani rezygnacji ze wszystkich przyszłych wojen.

## 5. Nowe pola duchowego rozwoju
W playable_data dochodzą:
- tenets={ tenet_ora_et_labora };
- current_spiritual_fulfillment=10.

Rozpoznano mechanikę **By God Alone**: osobiste spełnienie duchowe jest odrębne od pobożności. Wartość 10 nie potwierdza konwersji, reformy całej wiary ani złożenia ślubów. Dokumentacja i ograniczenia: „Mody-Hohenzollern-1066-09-20.md”.

Nazwa ora et labora daje czytelny motyw modlitwy i pracy, dobrze pasujący do gospodarczego zainteresowania i ogrodnictwa. Jest to interpretacja literacka, nie wyliczenie premii.

## 6. Ciągłość rady, rodu i otoczenia
Rada jest identyczna jak po reorganizacji z 18 września:
- Sieghard von Genf — kanclerz;
- Sigismund 66605 — zarządca;
- Humbert von Venis — marszałek;
- Stefan — mistrz intryg;
- Sigismund 58283 — kapelan;
- Nikolaus — dodatkowy członek o nieustalonej funkcji.

Nie zmienili się posiadacze czterech tytułów domeny, lista praw, głowa domu i lista sukcesji. Nie odczytano nowej żony lub dziecka Burkharda. Rudolf pozostaje awaryjnym dziedzicem; to nadal ważne otwarte zagadnienie.

W analizowanym otoczeniu nie przybył nowy radny i nie zmieniły się listy cech pozostałych wyodrębnionych postaci. Drobne zmiany liczników cooldown nie są samodzielnymi wydarzeniami fabularnymi. Nie potwierdzono nowego romansu, sojuszu, buntu ani spisku.

## 7. Tło fabularne — „Rachunek i ziemia”
**Poniższa scena jest autorską prozą opartą na nowych cechach i kierunku gospodarczym.** Spotkanie, słowa, istniejące grządki i reakcje osób nie są osobnymi faktami odczytanymi z gry.

Od sierpnia Burkhard przyzwyczajał się do ludzi, którzy przychodzili po rozstrzygnięcie tak, jak dawniej przychodzili do jego ojca. Niektórzy kończyli wyjaśnienie, zanim zdążył zadać pytanie. Inni zostawali dłużej, jakby czekali, aż odpowie im ktoś starszy.

Reorganizacja rady nie usunęła tego ciężaru. Zmieniła tylko nazwiska ludzi, którym hrabia mógł powierzyć część pracy.

Rankiem dwudziestego września Sigismund przyniósł rachunki. Nie mówił o wielkich zyskach. Pokazał, co powinno wpływać, jakie obowiązki wymagają sprawdzenia i gdzie zapis nie pozwalał jeszcze oczekiwać wykonania.

Burkhard kazał mu odróżnić należność od rzeczy, która już znalazła się w skrzyni. Słyszał ten sam nakaz od Konrada. Wtedy wydawał mu się niepotrzebnie surowy. Teraz wiedział, że na podstawie obietnicy można łatwo obiecać następnej osobie więcej, niż rzeczywiście się posiada.

Zarządca przyjął polecenie z widocznym zadowoleniem. Lubił granice, które można było sprawdzić. Hrabia nie pozwolił jednak, by przegląd rachunków zastąpił rozmowę o ludziach. Przy kilku zapisach poprosił również o wyjaśnienie Petera.

Nie było to odwrócenie nominacji. Peter znał część spraw, których Sigismund jeszcze nie zdążył poznać. Burkhard potrzebował obu rodzajów wiedzy i zaczynał rozumieć, że posiadanie urzędu nie daje wyłączności na prawdę.

Po południu wyszedł do miejsca, gdzie uprawiano rośliny dla domowych potrzeb. Nie polecił zakładać nowego ogrodu. Obejrzał to, co już tam rosło.

Przy jednej z grządek ziemia zaskorupiła się mocniej. Człowiek pracujący przy niej wskazał część wymagającą rozluźnienia. Hrabia przykucnął i spróbował palcami. Nie wiedział jeszcze, czy powodem była gleba, cień, czy sposób ostatniej pracy. Dopytywał, aż usłyszał odpowiedź dokładniejszą od pierwszej.

Tę samą cierpliwość, która bywała nieznośna przy rachunkach, tutaj przyjęto bez urazy. Ziemia nie obrażała się o pytania.

Burkhard pomógł przy krótkiej pracy, zanim zawołano go ponownie. Nie zrobił wiele. Dla niego ważne było, że można zobaczyć rezultat własnego ruchu: rozluźnioną ziemię, usuniętą przeszkodę, roślinę pozostawioną przy większej przestrzeni.

Przy decyzjach władcy rezultat przychodził wolniej. Człowiek mógł odpowiedzieć posłusznie, a potem wykonać rozkaz tak, jak sam uważał za słuszne. Niektóre sprawy trzeba było sprawdzać ponownie, inne pozostawić, aby nie zniszczyć ich nadmiernym naciskiem.

Kapelan zobaczył hrabiego, kiedy ten czyścił dłonie. Nie doszło do wielkiego pojednania. Duchowny zapytał o jedną z bieżących powinności, Burkhard odpowiedział i kazał przypomnieć mu o niej później.

A jednak dla młodego pana modlitwa i praca zaczynały mieścić się w tym samym dniu bez poczucia, że jedna musi usprawiedliwiać zaniedbanie drugiej. Nie zamierzał oddać domu spokojowi za cenę bezczynności. Chciał, aby odziedziczona władza mogła utrzymać ludzi, których zobowiązywała.

Wieczorem Humbert przedstawił sprawę pozostałych oddziałów. Burkhard wysłuchał go bez obietnicy szybkiej wyprawy. Wcześniejsze ograniczenie wojska nie usuwało potrzeby gotowości. Marszałek miał dopilnować tych, którzy pozostali, a hrabia — środków, dzięki którym ich służba nie będzie jedynie wymaganiem.

Na stole nadal leżały rachunki. Za oknem było miejsce, do którego Burkhard mógł wrócić następnego ranka.

Po raz pierwszy od objęcia rządów obie rzeczy wydawały mu się częścią tego samego obowiązku.

## 8. Jak rozwijać ten wątek
Najsilniejszy motyw to **odziedziczony dom prowadzony własną metodą**: Burkhard dobiera radę, kieruje uwagę ku gospodarce i znajduje osobistą praktykę cierpliwej pracy. Nie zmienia się nagle w człowieka pozbawionego ambicji.

Konflikty mogą wynikać z kosztu tego kierunku: zarządca chce kontroli, Peter przypomina o ludziach, marszałek o gotowości, a dawni radni o godności. Ich reakcje należy rozwijać jako możliwości, dopóki kolejne wydarzenia ich nie potwierdzą.

Dopełnienie życiorysu Burkharda: od 20 września jest ogrodnikiem i ma wybraną koncentrację na bogactwie. Jego sierpniowa sukcesja i ojcowskie dziedzictwo pozostają podstawą ciągłości.

### Źródła kontekstu
Odczyt zmian opiera się na trzech zapisach gry. Interpretacja cech stosuje „CK3-Metoda-analizy-charakterow-i-cech.md”.

Historyczne połączenie uprawy, codziennej pracy i życia duchowego ma oparcie w tradycji ogrodów klasztornych; nie dowodzi konkretnego kontaktu Burkharda z klasztorem. [Kloster Oberzell — dzieje ogrodów ziołowych](https://www.oberzell.de/kloster-oberzell/kraeutergarten/der-oberzeller-heilkraeutergarten-und-seine-urspruenge/), sprawdzono 10.10.2026. Nie wykorzystano późniejszej Hildegardy z Bingen jako nauczycielki postaci żyjącej w 1066.

