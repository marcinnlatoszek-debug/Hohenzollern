# CK3 — zasady odczytywania charakteru postaci dla kroniki Hohenzollernów

**Status:** ZATWIERDZONA METODA INTERPRETACJI — polecenie użytkownika 14 października 2026: „zapisz do kanonu, sprawdz informacje o mechanikach ck3 o tym jak odczytywac charakter itd”.  
**Zastosowanie:** wszystkie karty postaci, plany powieści i opowiadania Astry.  
**Wersja bazowej analizy mechanik:** Crusader Kings III 1.20.1. **Uzupełnienie:** 19 X 2026, po audycie save’a 1.20.1.1 z datą gry 6 X 1080. W archiwalnym playsecie zapisano 19 wpisów modów, ale ich źródła i dokładne wersje pozostają niepotwierdzone; mody mogą zmieniać zachowanie AI, wydarzenia i efekty.  
**Najnowszy zatwierdzony punkt cech:** save z **6 X 1080**; porównywalny stan archiwalny obejmuje pełny save z 18 X 1073 i wcześniejsze przekroje. [Audyt cech i osi osobowości 6 X 1080](../campaign/Kanon_charakterow_1080-10-06.md); [raport 18 X 1073](../07_ANALIZY/raporty_zmian/CK3_1073-10-18_weryfikacja.md).  
**Archiwalny kanon cech:** [12 XI 1070](../campaign/Kanon_charakterow_1070-11-12.md).  
**Powiązany zapis terytorialny:** [Szwabia — porównanie 6 III 1067 i 6 X 1080](../03_TERYTORIA/KSIESTWA/d_swabia/karta.md).

## 1. Hierarchia dowodów: cztery różne poziomy

1. **FAKT GRY / KANON:** datowany zapis, rzeczywiście odczytany kod cechy, historia zdarzeń, widoczne w grze parametry postaci lub wyraźne potwierdzenie gracza. Zapisuj ID, datę świata, nazwę pliku/screena i status. Daty pozbawione jednoznacznego uzasadnienia oznaczaj jako nieustalone.
2. **MECHANIKA CK3:** znaczenie kategorii cech, stresu, edukacji, statystyk, wskaźników AI i relacji, zweryfikowane w definicjach gry i encyklopedii. Jest to **zasada czytania** kanonu, a nie wydarzenie z konkretnej kampanii.
3. **WNIOSKOWANIE FABULARNE:** możliwy temperament, styl mówienia, preferencje i wewnętrzne napięcia. Zapisuj wyraźnie jako interpretację dla Astry, nie jako potwierdzone czyny, tajne plany i nowe zdarzenia.
4. **FIKCJA ŁĄCZNIKOWA:** dialogi, codzienność, służba, podróż bez zmian o charakterze strategicznym, tło obyczajowe. Nie mogą zmieniać ustalonych w grze rezultatów. Nowe fakty fabularne mogą wejść do kanonu dopiero po **osobnym zatwierdzeniu użytkownika**.

**Zasada nadrzędna:** postać `sadistic` nie musiała nikogo torturować; `deceitful` nie dowodzi faktycznego kłamstwa w określonej sprawie; `ambitious` nie dowodzi buntu; `lustful` nie dowodzi romansu, zdrady ani wykorzystania seksualnego; `brave` nie dowodzi udziału w bitwie.

## 2. Jak czytać kategorie danych postaci

| Kategoria | Co daje gra | Co wolno z niej wnosić | Czego NIE wolno zakładać |
|---|---|---|---|
| **Trzy cechy osobowości** (`personality`) | Preferencje, skłonności AI, wpływ na opinię i stres, modyfikatory | Wartości, pokusy, reakcje pod presją; postacie nie są jednowymiarowe | Dokonanej zdrady, zbrodni, miłości, zamiaru wojny |
| **Wykształcenie** (`education_...`) | Kierunek oraz jakość szkolenia; premia do umiejętności i rozwoju stylu życia | Zasób kompetencji wyuczonych | Wierności, szlachetności, temperamentu, inteligencji potocznej |
| **Umiejętności** (dyplomacja/wojskowość/zarządzanie/intryga/nauka/waleczność) | Liczbowa skuteczność w określonej domenie | Co postać może dobrze wykonać | Jak postać zamierza użyć talentu i czy już go użyła |
| **Cechy stylu życia, dowodzenia i zdrowia** | Specjalizacja, doświadczenie, możliwości i ograniczenia | Zainteresowania, dziedziny kompetencji, podatności zdrowotne | Konkretnej bitwy, marszu, choroby o nieustalonym przebiegu, daty śmierci |
| **Cechy dziedziczne/fizyczne** | Właściwości postaci, czasem możliwe do odziedziczenia | Opis wyglądu i dyspozycji, jeśli potwierdzony | Oceny moralnej, automatycznych losów potomstwa |
| **Opinia o innej postaci** | Wskaźnik kierunkowy i sytuacyjny (np. +56, −7); może się zmieniać | Chwilowe usposobienie wobec wskazanej osoby | Dowodu miłości, dożywotniej lojalności lub spisku |
| **Wiara, kultura, cnoty i grzechy** | Kontekst społeczny i religijny; ocena cech zależy od obrządku i doktryn | Możliwe normy i napięcia ze środowiskiem | Rzeczywistej prywatnej wiary z samej etykiety AI |
| **AI osobowości i opis z interfejsu** | Parametry i złożony archetyp (np. „Zdradziecki nikczemnik”, „Bezduszny ateista”) | Skrót preferencji modelu AI; trop literacki | Dodatkowego, ukrytego traitu o takiej nazwie ani potwierdzonego czynu |

### Hierarchia nazw i wartości

- **Najwyższa precyzja nazwy:** oryginalny identyfikator `trait` z aktualnego save'a, rozpoznany przez jego własną tablicę `traits_lookup`, oraz odpowiedni tooltip z obecnej instalacji.
- **Screena odczytuj jako stan wynikowy UI.** Statystyka postaci (np. zarządzanie 21) jest sumą wielu źródeł; tablica liczb bazowych w save nie jest jej zamiennikiem.
- **Cechy oraz statusy mogą zmieniać się w czasie.** W starszej scenie nie używaj automatycznie cechy, urzędu, opinii ani umiejętności z 12 XI 1070, jeśli stan tej sceny nie jest udokumentowany.
- **Numery indeksów cech** są lokalne dla danego zapisu i konfiguracji modów. Nie traktuj indeksu 67 itd. jako globalnego kodu CK3. Trwałym odniesieniem jest angielski identyfikator cechy.
- **Opis osobowości generowany przez UI** to złożona etykieta, nie wiążące dosłowne rozpoznanie psychologiczne ani automatycznie lista traitów. Gdy opis brzmi „Zadowolona idiotka”, „Zdradziecki nikczemnik” lub „Bezduszny ateista”, nie dopisuj bez źródła cechy „idiota”, wykonanego czynu zdrady czy porzucenia wiary.

## 3. Stres i konflikt z osobowością

- W CK3 działania sprzeczne z cechami osobowości **mogą zwiększać stres**. Stres przyrasta także w różnych sytuacjach życiowych; posiadanie określonej cechy nie oznacza, że postać ma już wysoki stres.
- Co 100 punktów stresu pojawia się kolejny jego poziom, zwykle od 0 do 3; od poziomu 1 możliwe są wydarzenia typu `Mental Break`, a wyższe poziomy wpływają na zdrowie i płodność.
- Przykład referencyjny z definicji CK3: `ambitious` ma +25% przyrostu stresu, a `diligent` −50% tempa jego redukcji; to różne modyfikatory. Burkhard ma obie cechy. **Nie ustalono jego faktycznego aktualnego poziomu stresu na podstawie samej listy cech**.
- W pisarstwie naciskaj na **koszt sprzecznej decyzji**, nie na automatyczny dramat psychiczny. Wewnętrzny konflikt może pojawić się w scenie łącznikowej, ale załamanie nerwowe lub uzyskanie cechy stresowej to wydarzenie mechaniczne i wymaga dowodu.
- Wartości mechaniczne z ogólnodostępnych definicji dotyczą bazowego CK3; **19 aktywnych modów może modyfikować efekty**. Bez tooltipa gry albo plików konkretnego moda nie zapisuj procentów jako potwierdzonych wynikowych modyfikatorów tej kampanii.

## 4. AI, charakter i interpretacja działań

Cechy oraz inne modyfikatory wpływają na różne składowe zachowań AI: `ai_boldness`, `ai_compassion`, `ai_greed`, `ai_honor`, `ai_rationality`, `ai_energy`, `ai_sociability`, `ai_vengefulness`, `ai_zeal`. Skrypty wykorzystują te wartości między innymi przy ważeniu działań.

**To skłonności i wagi, a nie nieuchronne decyzje.** Na zachowania AI wpływają także okoliczności, interakcje, cele, siła zbrojna, prawo, mechanika danego wydarzenia i mody. Sam opis archetypu nie dowodzi spisku. Postać gracza podejmuje decyzje zgodne z realną rozgrywką użytkownika, nie z założoną strategią AI.

Dla dworzan i postaci AI najlepiej stosować zasadę: **cecha → prawdopodobna preferencja → możliwa reakcja w scenie → potwierdzony wybór gry ma pierwszeństwo przed literackim przewidywaniem**.

## 5. Edukacja, umiejętności, dwór i relacje

- `education_stewardship_3` Burkharda oznacza rozwinięte wykształcenie w zarządzaniu, nie dowodzi automatycznie prowadzenia handlu, zwiększenia podatków ani zainicjowania konkretnej budowy.
- `intellect_good_2` Burkharda to dziedziczna cecha „inteligentny” (gra odróżnia ją od wykształcenia). Nie utożsamiaj jej z przewidywaniem, że będzie podejmował wyłącznie rozsądne decyzje.
- `military_engineer` Siegmunda i Radbota oznacza zdolności specjalistyczne; nie dowodzi osobistego udziału w oblężeniu.
- `open_terrain_expert` Gerlacha jest kompetencją dowódczą; nie dowodzi, że uczestniczył w kampanii na otwartym terenie.
- `faltering_heart` Hupolda III i `sickly` Leopolda są potwierdzonymi cechami zdrowia. **Leopold zmarł 7 VII 1071** według nowszego save'a; **przyczyna zgonu jest nieustalona** i nie wynika automatycznie z `sickly`. Nie przewidywać dalszych losów Hupolda z samych cech zdrowia.
- Aktualna opinia +56 między Burkhardem i Hedwig nie jest tożsama z wydarzeniem „miłość”; −7 Radbota nie potwierdza zdrady; +79 Siegmunda nie jest przysięgą dozgonnej wierności. Rodzinne uczucia i konflikt literacki wymagają oddzielnego traktowania.
- Zadanie kapelana, aktualny urząd, obecność na dworze i bycie w rejestrze żyjących to różne typy danych. Nie łącz ich bez źródła.

## 6. Praktyczne wzory psychologiczne dla Astry (INTERPRETACJE, NIE FAKTY HISTORYCZNE)

| Para lub postać | Potwierdzone cechy | Uprawniony potencjał literacki | Czego nie dopisywać |
|---|---|---|---|
| Burkhard | ambitny, pracowity, cierpliwy; zarządzanie III, inteligentny | Długofalowe planowanie, pracowitość, wytrwałość, napięcie między aspiracją a ograniczonym hrabstwem | Buntu przeciw Rudolfowi, osobistego udziału w wojnie bez dowodu |
| Hedwig | niecierpliwa, arogancka, zadowolona | Chęć szybszego rozstrzygania spraw, duma rodowa, zadowolenie z obecnej pozycji | Potwierdzonej kłótni, zdrady czy własnych ukrytych planów |
| Burkhard–Hedwig | `ambitious`/ `content` i `patient`/ `impatient` (cechy przeciwstawne w systemie gry) | Różne tempo decyzji i stosunek do przyszłych zdobyczy; sceny rozmowy, nie schemat dobry–zły | Istniejącego konfliktu małżeńskiego z samej przeciwstawności cech |
| Rudolf | gniewny, wybaczający, sprawiedliwy | Wewnętrzne tarcie między impulsem gniewu a normą sprawiedliwości i zdolnością wybaczania | Nieudokumentowanych represji i decyzji wojennych |
| Hupold III | gniewny, lubieżny, kłamliwy, cechy zdrowotne | Ambiwalencja politycznej przydatności i osobistych słabości, widoczny ciężar zdrowia | Konkretnego kłamstwa, zdrady małżeńskiej ani rychłej śmierci |
| Radbot | zmienny, sadystyczny, niecierpliwy | Niebezpiecznie ostry sposób osądu wojny i dyscypliny; napięcie z dworzanami o innych wartościach | Faktycznej zdrady Burkharda lub dokonanego okrucieństwa |
| Walpurga | hojna, spokojna, cnotliwa; edukacja intrygi | Dyskretna profesjonalistka, odróżniająca metody wywiadowcze od prywatnego charakteru | Jakiegokolwiek wykonanego zamachu/spisku bez dowodu |
| Gerlach | odważny, lubieżny, towarzyski; ekspert otwartego terenu | Śmiałość i towarzyskość wśród rycerzy, ambiwalencja prywatna | Bitwy, romansu lub przemocy bez źródła |
| Meinhard | ambitny, sprawiedliwy, chciwy; duchowny | Napięcie między rolą religijną, zasadą sprawiedliwości i materialnymi ambicjami | Apostazji z samej etykiety „ateista”, uzyskania roszczenia bez powiadomienia |
| Inga | kłamliwa, wybaczająca, lubieżna; kompetencje medyczne | Dyskrecja medyczna, lojalność zawodowa lub napięcie między sekretem a współczuciem | Faktycznych romansów, fałszowania dokumentów, spisków |
| Siegmund | współczujący, uczciwy, zadowolony; lojalny, inżynier wojskowy | Powściągliwa dyplomacja, skłonność do łagodzenia sporów, fachowość | Gwarancji, że nigdy nie złamie przysięgi |

Powyższe **nie są zdarzeniami kampanii** i nie należą do osi czasu. Są zatwierdzonym **sposobem korzystania z mechaniki** podczas pisania.

## 7. Protokół każdej kolejnej karty postaci

1. **IDENTYFIKACJA:** imię, ID, data gry, źródło (save / screen / deklaracja użytkownika).
2. **TRWAŁE / DATOWANE CECHY:** osobowość 3+, edukacja, zdrowie, dowódcze, cechy dziedziczne; angielskie identyfikatory i polskie tłumaczenie opisowe.
3. **STAN W TEJ DACIE:** wynikowe umiejętności z interfejsu, stanowisko, senior, dwór, potomstwo, religia/kultura, opinie z określeniem kierunku, aktywne zadania.
4. **CO SIĘ ZMIENIŁO:** tylko porównanie stanu A i B; nie przypisuj momentu lub przyczyny zmian bez osobnego dowodu.
5. **MECHANIKA:** co oznaczają potwierdzone kody, jakie preferencje AI i stres są możliwe; nie zakładaj bazowych modyfikatorów jako pewnych dla moda.
6. **GŁOS LITERACKI (OPCJONALNIE):** styl dialogu, motywacje, wewnętrzne sprzeczności jako hipotezy twórcze, oddzielnie od wydarzeń.
7. **STATUS:** POTWIERDZONE / DO WERYFIKACJI / INTERPRETACJA / FIKCJA ŁĄCZNIKOWA. Każdy nowy kanoniczny fakt wymaga zatwierdzenia przez użytkownika.

## 8. Źródła mechaniczne i ograniczenie wersji

**CK3DB** jest nieoficjalnym indeksem wypisanym z plików gry i ich lokalizacji; część podstron odzwierciedla **1.20.0.4**, część już **1.20.1**. Nie przypisuj dokładnych efektów 1.20.0.4 modowanej kampanii 1.20.1 bez kontroli.

- [Encyklopedia CK3: education trait](https://ck3db.com/concepts/education_trait) — wykształcenie i szkolenie.
- [Encyklopedia CK3: stress level](https://ck3db.com/concepts/stress_level) — poziomy stresu i `Mental Break`.
- [Encyklopedia CK3: focus (1.20.1)](https://ck3db.com/concepts/focus) — premie i zdarzenia stylu życia.
- [Trait: ambitious](https://ck3db.com/traits/ambitious), [diligent](https://ck3db.com/traits/diligent), [patient](https://ck3db.com/traits/patient), [content](https://ck3db.com/traits/content), [sadistic](https://ck3db.com/traits/sadistic), [just](https://ck3db.com/traits/just) — źródła definicji i wybranych modyfikatorów.
- [Wykaz efektów stewardship](https://ck3db.com/effects/stewardship) — odróżnienie `education_stewardship_3` od bazowych punktów zarządzania.
- [Dokumentacja modowania cech](https://github.com/jesec/ck3-modding-wiki/blob/master/wiki_pages/Trait_modding.md) oraz [AI](https://github.com/jesec/ck3-modding-wiki/blob/master/wiki_pages/AI_modding.md) — sposób definiowania kategorii i parametrów, materiały referencyjne, miejscami starsze od wersji kampanii.

**Nadrzędny źródłowo jest odczyt własnego save'a wraz ze screenami aktualnej instalacji**; źródła zewnętrzne wyjaśniają zasady, a nie ustalają faktów tej alternatywnej kampanii. 


## 9. Uzupełnienie metody — źródła CK3 i pisanie fabuły (19 X 2026)

### 9.1. Co potwierdzają źródła o mechanice

- Encyklopedia [CK3 Wiki: Traits](https://ck3.paradoxwikis.com/Traits) opisuje cechy osobowości jako najbardziej charakterystyczne cechy postaci i wiąże je z tym, czy oraz w jakim stopniu działania sprzeczne z nimi generują stres. Jest to wiki społecznościowa, nie oficjalna dokumentacja Paradox; strona wyników wyszukiwania wskazywała weryfikację do wersji 1.19. Używamy jej do ogólnej orientacji, nie jako dowodu dokładnych efektów w save’ie 1.20.1.1.
- [CK3 Wiki: Attributes](https://ck3.paradoxwikis.com/Attributes) opisuje stres, jego poziomy i zdarzenia załamania. [CK3 Wiki: Character decisions](https://ck3.paradoxwikis.com/Character_decisions) pokazuje, że część decyzji i reakcji zależy od cech, ale dostępność i efekty trzeba sprawdzać w aktualnej grze.
- Oficjalny opis Paradox [Crusader Kings III — Character](https://www.paradoxinteractive.com/games/crusader-kings-iii/add-ons/crusader-kings-iii-pre-order) mówi, że cechy kierują działaniami, a postępowanie wbrew naturze postaci może przynosić stres. Jest to opis ogólnej koncepcji gry, nie dokumentacja wszystkich wartości liczbowych.
- Ogłoszenie Paradox o [By God Alone](https://www.paradoxinteractive.com/media/press-releases/paradox-interactive/keep-the-faith-in-upcoming-crusader-kings-iii-expansion) przedstawia dodatkowy związek cech, działań i tenetów z duchowością. Stosować tę warstwę wyłącznie wtedy, gdy obecność odpowiedniego DLC i mechaniki jest potwierdzona dla analizowanej rozgrywki.
- Źródła zewnętrzne tłumaczą mechanikę; fakty o konkretnej postaci nadal pochodzą z datowanego save’a, screenów i jednoznacznych potwierdzeń użytkownika. Efekty liczbowe należy weryfikować w definicjach wersji i tooltipach aktywnej instalacji, szczególnie przy modach.

### 9.2. Zasada czytania profilu

1. **Zacznij od daty i identyfikacji.** Ustal ID postaci, datę gry, źródło i wersję. Tych samych imion nie łącz bez ID lub potwierdzonej relacji.
2. **Oddziel kategorie.** Trzy cechy osobowości czytaj osobno od edukacji, umiejętności, cech stylu życia, dowodzenia, zdrowia, dziedziczności, mechanizmów radzenia sobie ze stresem i złożonego opisu AI z interfejsu. Żadna z tych kategorii nie zastępuje pozostałych.
3. **Czytaj zestaw, nie etykietę.** Dla każdej cechy zapisz możliwą preferencję lub wrażliwość; następnie sprawdź, jak pozostałe cechy ją wzmacniają albo ograniczają. Sprzeczne skłonności są użytecznym napięciem fabularnym, a nie dowodem hipokryzji czy konkretnego czynu.
4. **Porównuj wyłącznie datowane stany.** Zapisz cechy niezmienione, nowe lub nieobecne w starszym odczycie. Brak cechy na starszym screenie nie dowodzi dokładnej daty jej uzyskania. U dzieci zaznacz, że profil może się jeszcze kształtować.
5. **Nie diagnozuj.** Cechy CK3 są uproszczonymi etykietami mechaniki i nie są diagnozą psychologiczną ani pełnym historycznym opisem człowieka.
6. **Rozdziel skłonność od zdarzenia.** Cecha może podpowiedzieć prawdopodobny sposób reagowania; nie potwierdza, że postać tak postąpiła. Stres, załamanie, motyw, romans, kłamstwo, zdrada, okrucieństwo, wojna i sukcesja wymagają osobnego źródła, jeśli mają być faktem kanonicznym.

### 9.3. Przekład cech na scenę

Przy projektowaniu sceny dla Astry używaj krótkiego łańcucha:

**potwierdzona sytuacja → cechy istotne w tej sytuacji → możliwe napięcie lub preferowana reakcja → koszt / ograniczenie → wariant literacki oznaczony jako interpretacja.**

- Najpierw wybierz sytuację popartą kanonem: np. decyzję w sprawie ziemi, obowiązek wobec seniora, audiencję, rodzinny spór już potwierdzony albo trud wojny. Nie twórz zdarzenia tylko po to, by „zademonstrować” cechę.
- Pokaż cechę przez zachowanie, dobór słów, rytm decyzji lub to, co postać zauważa. Nie każ jej wypowiadać nazwy traitu ani sprowadzaj do jednej cechy.
- Konflikt cech może dać wewnętrzne wahanie, kompromis lub maskowanie preferencji. To literacka możliwość; nie zapisuj jej jako psychologicznego faktu.
- Jeśli ważna jest sprzeczność z cechą, można pokazać jej możliwy ciężar, ale konkretnego poziomu stresu, załamania i skutku zdrowotnego nie dopisuj bez potwierdzenia mechaniki lub źródła.
- Urząd, wiara, kultura, relacje i sytuacja polityczna ograniczają wybór. Cechy nie działają w próżni ani nie przesądzają wyniku.
- Przy każdej notatce dla fabuły oznacz: **FAKT GRY**, **WNIOSEK / INTERPRETACJA**, **FIKCJA ŁĄCZNIKOWA** albo **NIEUSTALONE**. Nowy fakt wydarzeniowy wymaga osobnego zatwierdzenia użytkownika.

### 9.4. Przykłady z kanonu 6 X 1080

- **Burkhard 66952 — ambitious, diligent, patient:** można pisać o cierpliwym, konsekwentnym dążeniu do celu. Sama triada nie dowodzi buntu przeciw Rudolfowi, konkretnego roszczenia ani tajnego planu.
- **Rudolf 35525 — wrathful, forgiving, just:** profil pozwala badać napięcie między gniewem, wybaczeniem i własnym standardem sprawiedliwości. Nie dowodzi represji ani tego, jak rozstrzygnął konkretny spór.
- Pełne cechy i osie najbliższego dworu oraz porównanie z wcześniejszymi snapshotami znajdują się w [kanonie cech 6 X 1080](../campaign/Kanon_charakterow_1080-10-06.md). Zmiany w ziemiach i interpretacyjne tło Szwabii są opisane osobno w [karcie terytorium](../03_TERYTORIA/KSIESTWA/d_swabia/karta.md); nie przenosić tła ani wniosków terytorialnych na osobiste motywy postaci.

**Status tego uzupełnienia:** metoda wykorzystania mechanik do interpretacji i pisania, nie nowe wydarzenie świata gry. Przegląd źródeł zewnętrznych: 19 X 2026; w razie zmiany wersji, DLC lub modów sprawdź je ponownie.
