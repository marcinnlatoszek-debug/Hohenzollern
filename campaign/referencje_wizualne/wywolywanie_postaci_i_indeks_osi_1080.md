# Kanoniczne wywoływanie postaci CK3 — stan 2 października 1080

**Projekt:** Nobilis gens von Hohenzollern. **Aktualizacja redakcyjna:** 19 października 2026. **Status:** identyfikacja z dostarczonych oryginalnych screenów CK3, zatwierdzona przez użytkownika; nie tworzy nowych wydarzeń w grze.  
**Główna baza:** Supabase `aieqqyglilxgyjnbfzws`, schemat `chronicle`. GitHub jest kopią dokumentacyjną.  
**Wzorce fizyczne:** [46 oryginalnych PNG / 12 postaci](indeks_portretow_zrodlowych_1080.md), [opis rysów](wzorce_postaci_1080-10-02.md), [zasady akceptacji](protokol_zatwierdzania_grafik.md), [herb](herb_hohenzollern.md), [oś wydarzeń 1078–1080](../Os_czasu_Zollern_1078-1080.md).

## Reguła identyfikacji po imieniu

Każda nazwa przywołuje **jedną kartę o niezmiennym ID CK3 lub kluczu archiwalnym**. Dokładnego wyglądu trzeba szukać w przypisanym katalogu oryginałów z Biblioteki `/Hohenzollern/CK3_wzorce_1080/`. Wygenerowana ilustracja nie zastępuje oryginału. Przywołanie `Burkhard` bez kwalifikatora w kontekście władcy = hrabia `66952`; `Burkhard młodszy` lub `syn Burkharda` = `79306`. Dla `Adelheid` wymagane jest sprawdzenie kontekstu (córka hrabiego / dawna władczyni Hohenbergu / Adelheid z Bellingam); bez niego nie wolno domyślnie mieszać twarzy.

| Wywołanie / aliasy | Tożsamość trwała | Wiek przekazany dla 1080 | Rola i relacja | Jednoznaczny wzorzec — Biblioteka |
|---|---|---:|---|---|
| `Burkhard`, `hrabia Burkhard`, `Burkhard von Hohenzollern`, `Burkhard starszy` | CK3 **66952** | **30** | Hrabia Zollern i Hohenbergu; mąż Hedwig, ojciec czworga dzieci | `burkhard-hrabia/`; jasny blond zaczesany w tył, krótki jasny zarost, mocna szczęka, czarny płaszcz z czerwonym pasmem |
| `Hedwig`, `hrabina Hedwig`, `Hedwig von Hohenzollern` | CK3 **41150** | **30** | Żona hrabiego; matka Burkharda młodszego, Martina, Adelheid i Ulricha | `hedwig/`; długie ciemnobrązowe włosy i siatka, owalna twarz, złote kolczyki |
| `Burkhard młodszy`, `mały Burkhard`, `Burkhard syn` | CK3 **79306** | **11** | Starszy syn hrabiego i Hedwig; **nie ojciec** | `burkhard-mlodszy/`; krótkie ciemne włosy, gładka chłopięca twarz, czerwień i czerń stroju |
| `Martin`, `Martin von Hohenzollern` | `martin-son-of-burkhard` | **5 wg ostatniego oświadczenia użytkownika** | Syn hrabiego i Hedwig | `martin/`; krótkie ciemne włosy, przystrzyżone boki, zaokrąglona twarz. **Konflikt:** data urodzenia 1073-11-02 w save/bazie daje 6 lat na 2 X 1080. Daty urodzenia nie korygowano. |
| `Adelheid córka`, `Adelheid von Hohenzollern` | `adelheid-daughter-of-burkhard` | **3** | Córka hrabiego i Hedwig; odrębna od Adelheid **31878** i Adelheid z Bellingam | `adelheid-corka/`; włosy jasny blond do żuchwy, zaokrąglona twarz, niebieska sukienka na późniejszym ujęciu 6 X. |
| `Ulrich`, `Urlich`, `Ulrich von Hohenzollern` | `ulrich-son-of-burkhard` | **2** | Najmłodszy syn hrabiego i Hedwig | `ulrich/`; bardzo krótkie blond włosy, okrągła twarz, czerwona dziecięca szata |
| `Siegmund`, `kanclerz Siegmund` | CK3 **76331** | **48** | Rycerz i **kanclerz** hrabiego | `siegmund/`; ciemne włosy, broda i wąsy, kolczuga |
| `Gerlach`, `zarządca Gerlach` | CK3 **72054** | **37** | Rycerz, **zarządca i wielki łowczy**, nie kanclerz; mąż Luitgard, ojciec Gautselina | `gerlach/`; krótkie ciemne loki, ogolone boki, bez pełnej brody, futrzany płaszcz |
| `Radbot`, `marszałek Radbot` | CK3 **66953** | **35** | Rycerz i marszałek | `radbot/`; blond uniesiony do tyłu, jasna gładka twarz, kolczuga |
| `Meinhard`, `kapelan Meinhard`, `biskup Meinhard` | CK3 **69353** | **41** | Kapelan dworu Burkharda, w interfejsie **biskup sufragan** | `meinhard/`; brązowe włosy i zarost, tonsura/przerzedzenie na czubku, wzorzysta szata kościelna |
| `Reinhard`, `dowódca Reinhard` | `reinhard-knight-of-zollern` | **52** | Rycerz, dowódca wojsk Hohenzollern w wojnie 1075–1080 | `reinhard/`; dojrzała, krępa sylwetka, jasnobrązowo-ciemnoblond włosy zaczesane w tył, broda/zarost; nie podmieniać twarzą Radbota ani Meinharda |
| `Walpurga`, `mistrzyni szpiegów Walpurga` | CK3 **66954** | **41 — ostatnia wypowiedź użytkownika** | Mistrzyni szpiegów hrabiego | `walpurga/`; kasztanoworude upięte włosy, piegowata jasna twarz, czarna szata z zielono-złotymi obszyciami. **Konflikt:** wcześniejsze przekazanie wieku **40** w 1080; oba oświadczenia zachowano z datami. |

## Osadzenie na osi czasu

- **2 X 1080 to data kanonicznego stanu porównawczego CK3**, nie data powstania wszystkich zdjęć ani nowe wydarzenie wojskowe czy rodzinne.
- Portrety mają w nazwach sesji daty **21/24 VII, 1/2/6 X 1080**. Są odmianami ujęć tych samych postaci, ale nazwa zrzutu nie dowodzi, że każde zdjęcie zrobiono w świecie gry właśnie 2 X.
- Wszystkie 12 tożsamości są przypięte w `chronicle` do checkpointu wizualnego `visual-checkpoint:1080-10-02:identity-index-2026-10-19` (wydarzenie ewidencyjne, nie zdarzenie fabularne) i do kart ze źródłami oraz ścieżkami portretów.
- Przy pisaniu scen 1066–1080 odmładzaj postaci zgodnie z wydarzeniem; **nie kopiuj wyglądu z wieku 1080 na wcześniejsze lata**. Przy późniejszych ujęciach starzenie naturalne i stopniowe, bez podmiany tożsamości.
- **Gerlach**: stan dworu 2 X 1080 (zarządca, wielki łowczy i rycerz) nie jest automatycznie funkcją pełnioną bez przerwy od 1066. **Radbot** w grudniu 1066 był kanclerzem; w 1080 jest marszałkiem. **Siegmund** w 1080 jest kanclerzem. Dat historycznych zmian urzędów nie wolno dopisywać bez źródła.
- **Wenzel/Wanzel** pozostaje poza tą dwunastką: brak ujęcia w archiwum 46 PNG; dla jego twarzy wymagany odrębny oryginał. Imię narracyjne „Wanzel” zgodnie z poprzednią korektą.
- Herby: tarcza czteropolowa z krzyżem złotym w polu czarnym (górnym lewym) i czarnym jednogłowym orłem w górnym prawym białym polu; pozostałe dolne białe (lewe), czarne (prawe).

## Audyt rozbieżności i zasada pierwszeństwa

1. **Martin**: zapis wieku 5 (użytkownik) kontra urodzenie 2 XI 1073 i wynik 6 w październiku 1080 — bez milczącej zmiany metryki.
2. **Walpurga**: najpóźniejsze jednoznaczne „41 lat w 1080” ma pierwszeństwo w etykiecie wywołania; wcześniejsze 40 lat pozostaje źródłowo udokumentowane i wymaga sprawdzenia w CK3/save.
3. **Adelheid**: data 18 X 1076 z save’a daje 3 lata na 2 X 1080, przy czym odrębne zapisy grupowych zdjęć pozostają w archiwum.
4. Katalogi w Bibliotece nie zostały skopiowane binarnie do repozytorium; odnośniki plikowe w indeksie nie są publicznymi URL-ami PNG.
5. Pojedyncze wygenerowane grafiki nie stają się portretami źródłowymi; każdą interpretację należy oddzielnie zatwierdzić zgodnie z protokołem.

**Historia:** 19 X 2026 — dodano jednolity indeks wywołań imion, powiązanie z osią czasu i jawne konflikty wieku, bez usuwania wcześniejszych referencji.
