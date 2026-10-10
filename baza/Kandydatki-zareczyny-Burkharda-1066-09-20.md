# Rozpoznanie polityki matrymonialnej Burkharda — 20 IX 1066

**TO JEST ROZPOZNANIE, NIE NARZECZEŃSTWO.** Burkhard (62698, ur. 1050-01-09, 16 lat) nie ma żony ani dzieci. Awaryjnym dziedzicem dwóch hrabstw pozostaje książę Rudolf (33322). Potencjalne związki w CK3 wymagają interfejsowego sprawdzenia: czy postać jest już zaręczona, czy AI zgadza się na propozycję, czy dzieci należą do dynastii Burkharda, czy wyznanie/organizacja/klan nie blokują ślubu, jakie przynoszą sojusze i ich trwałość. Dane save'a **nie** podają aktualnego wyniku żądania małżeństwa.

## Konkretne osoby z dworów Szwabii — POTWIERDZONE ZAPISY POSTACI
Źródło: [szwabia-save-1066-09-20.json](dane/szwabia-save-1066-09-20.json), sekcja `context_people`. `family_data` bez `spouse` oznacza **brak wpisu małżonka**, ale nie niezależne potwierdzenie braku zaręczyn.

| Osoba | Wiek | Dwór, ojciec i dom | Stan mechaniczny / implikacja |
|---|---:|---|---|
| **Irmengard, 38207** | **18** | Eberhard 30931, Nellenburg (trzy hrabstwa i zarządca Rudolfa), dom 10593 | `female=yes`, `family_data=[]`; generous, content, compassionate, education_diplomacy_2. **Hipoteza**: powiązanie z ważnym zarządcą i rodem rozległego terytorium; akceptacja nieznana. |
| **Hedwig, 38745** | **16** | Hupold 30408, Dillingen (marszałek Rudolfa, ojciec Hartmanna Kyrburg), dom Hupoldinger 10590 | `female=yes`, `family_data=[]`; trusting, arbitrary, fickle, education_intrigue_3. **Hipoteza**: kanał do marszałka seniora i rodzinnego zaplecza Szwabii; akceptacja nieznana. |
| **Beatrix, 38744** | **16** | Rudolf 31630, Urach, dom 4234 | Brak małżonka, ALE cecha `devoted` oraz `organization=13`; najpewniej osoba zakonna. **Nie umieszczać na liście dostępnych narzeczonych**, chyba że warunki religijne i gra wykażą inaczej. |
| **Richinza, 39311** | **12** | Berthold 31948, książę Karyntii i posiadacz Breisgau, dom Zähringen 10589 | Dziecko; `family_data=[]`. Może być jedynie bardzo dalekim projektem dynastycznym, a nie małżeństwem zapewniającym szybkie rozwiązanie sukcesji. Nie tworzyć zawartych zaręczyn bez decyzji gracza. |

**Dodatkowe, niekoniecznie praktyczne powiązania:** książę Rudolf ma w save’ie małoletnie córki Adelheid (39952, ur. 1058), Agnes (40997, ur. 1063), Bertha (41185, ur. 1064). Nie rozwiążą szybko problemu braku następcy i nie są potwierdzonymi narzeczonymi. Ich obecność nie dowodzi zgody ojca na negocjacje. Dwie Berthy: księżniczka z tego domu nie jest królową Bertą Sabaudzką, historycznie poślubioną Henrykowi IV.

## Kandydatki obecne na dworze Burkharda (z kart 18 IX)
- **Ulrike 66607**, lat 20, córka kupca/zarządcy Sigismunda 66605, nie ma zapisanego małżonka; zarządzanie 12 i education_stewardship_3. Hipoteza: wzmocnienie wewnętrznej administracji i relacji z bogatym urzędnikiem. **Brak automatycznego sojuszu z obcym hrabią; prywatne złoto ojca nie staje się posagiem bez dowodu.**
- **Elisabeth Tschudi 66610**, lat 24, głowa domu i dworska urzędniczka, bez zapisanego małżonka; education_intrigue_3, odrębne cechy `bastard_founder` i `fornicator`. Hipoteza: niezależne małe zaplecze dworskie; brak udokumentowanego międzynarodowego sojuszu.
- **Irmeltrud 62701**, lat 31, bez małżonka w karcie 18 IX; brak zewnętrznego tytułu / potwierdzonego sojuszu. Starszy odczyt nie stanowi gwarancji aktualnej dostępności.
- **Wykluczenia**: Cecilie von Genf 66578 ma męża Matthiasa 66581; Beatrix 66594 ma męża Wolframa 66593; Klara 66591 ma męża Wenzla 66586; Berchte 66585 ma męża Liudolfa 66588. Nie proponować tych małżeństw jako wolnych.
- Dzieci von Landau i kupca Sigismunda (np. Benedicta 13, Beatrix 12, Hildegard 12) mają inny horyzont czasowy; nie są dorosłymi kandydatkami.

## Kanały poszukiwania poza Szwabią — NIE LISTA DOSTĘPNYCH OSÓB
1. **Zähringen/Karyntia**: wpływy Bertholda po obu stronach Schwarzwaldu, jego dotychczasowy spór o pozycję w Szwabii i odrębność od Rudolfa. Dostępność Richinzy, zgoda Bertholda i realna korzyść nieustalone.
2. **Górny Ren, Alzacja, Burgundia i Lotaryngia**: rody sąsiednich hrabstw jako weryfikowalny kierunek, bez wymyślania imion córek i gwarantowanych sojuszy.
3. **Welfowie / Bawaria**: rozważenie relacji przez Welfa 34907 i księcia Bawarii (historycznie Otto z Northeim w 1066), lecz **żadnej potwierdzonej wolnej dorosłej kandydatki nie znaleziono w dotychczasowym fragmencie danych**.
4. **Dom Rudolfa z Rheinfelden**: ścisły związek z seniorem mógłby być politycznie ważny, ale córki w obecnym wyciągu są dziećmi; propozycja nie usuwa automatycznie roszczeń Anselma ani sukcesyjnego ryzyka.
5. **Nellenburg i Hupoldinger**: najbardziej konkretne dwie dorosłe, bez zapisanych małżonków osoby w obecnym materiale — Irmengard i Hedwig. Ich ojcowie mają urzędy bezpośrednio przy Rudolfie.

## Test przed podjęciem jakiejkolwiek decyzji
Sprawdzić panel aranżacji małżeństwa dla **38207 Irmengard, 38745 Hedwig** oraz ewentualnie **66607 Ulrike, 66610 Elisabeth**. Zachować wynik akceptacji, rodzaj małżeństwa, przewidzianą dynastię potomków, bliskie pokrewieństwo, domniemanego sojusznika, opinie i ograniczenia religijne; opcjonalnie dane o dziedziczeniu cech zgodnie z modami. **Dopóki użytkownik nie podejmie decyzji w grze, żadna z tych postaci nie jest narzeczoną Burkharda.**

### Realia i tło powieściowe
Zaręczyny są przedmiotem negocjacji między domami i urzędami, o które zabiegają posłańcy. Można pokazać rozważanie propozycji i rozmowy o konsekwencjach, ale nie utrwalać przyrzeczenia, małżeństwa, posagu czy sojuszu bez save'a, ekranu wydarzenia lub decyzji gracza. Nie tworzyć emocjonalnej lub intymnej fabuły z dziećmi.
