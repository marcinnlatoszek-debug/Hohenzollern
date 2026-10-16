## 16 października 2026 — punktowe uzupełnienie osi i briefu save’em z 2 X 1080

**Decyzja użytkownika:** „Zapisz dopiski”, następnie „Zapisz w githube”.

- Do [osi 1078–1080](../campaign/Os_czasu_Zollern_1078-1080.md) i [briefu dla Astry](../campaign/Brief_dla_Astry_fabula_1078-1080.md) dodano punkt z `von_Hohenzollern(20261016-154350).ck3` (CK3 1.20.1): stan Burkharda i jego ziem, dzieci, kolejność sukcesji, zaręczyny Adelheid, śmierć Leopolda oraz wartość stresu.
- Zaktualizowano [stan kampanii](stan_aktualny.md) i [indeks save’ów](../06_MATERIALY_ZRODLOWE/indeks_saveow.md), odnotowując, że jest to punktowe uzupełnienie, nie pełny audyt wszystkich pól save’a.
- Save zapisuje `last_war_finish_date=1 VI 1080`. Zachowano osobno wcześniejsze rozstrzygnięcie użytkownika: **18 V 1080 jako narracyjną datę zamknięcia wojny**. Nie utożsamiono tych dat; warunki pokoju i końcowy raport bitwy pozostają nieustalone.

# Rejestr zatwierdzonych zmian kampanii

## 15 października 2026 — zatwierdzenie polityki Cesarstwa i briefu dla Astry

**Decyzja użytkownika:** „dodaj zmiany i informacje do kanonu i do wglądu dla astry” po ukończeniu raportu Deep Research.

- Dodano [kanon polityki Cesarstwa i Szwabii 1067–1073](../campaign/Kanon_polityki_Cesarstwa_1067-1073.md) i [aktualny brief dla Astry](../campaign/Brief_dla_Astry_Cesarstwo_i_Szwabia_do_1073-10-18.md).
- Włączono do chronologii dwie wojny Heinricha z zachowanych pamięci save'a: Istria **19 XII 1067–2 VI 1068** i Stormarn **12 VIII 1070–1 VI 1073**; dwie przegrane bitwy strony cesarskiej pod Auch i Lugues; siedmiu elektorów i frakcję populistyczną przeciw Heinrichowi na 18 X 1073.
- Odnotowano wybrane zmiany tytułów poza Szwabią **bez przypisywania nieznanych przyczyn**. Zachowano nieustalony koniec regencji Rudolfa, szczegóły cesarskich pokojów, skład frakcji i globalny ranking bitew.
- Uaktualniono główny kanon, oś 1070–1073, stan kampanii, indeks save'ów i oznaczono poprzedni brief Astry jako **archiwalny w zakresie stanu wiedzy**.
- Nowszy `von_Hohenzollern(20261015-182245).ck3` ma datę **4 II 1075**; **nie** zatwierdzono przesunięcia kanonu z **18 X 1073** na 1075. Nie dopisano nowych zdarzeń literackich jako faktów gry.

## 14 października 2026 — zatwierdzenie pełnego save'a 18 X 1073

**Decyzja użytkownika:** „zatwierdzam” po pogłębionej analizie porównawczej dwóch identycznych nowszych plików save z punktem 12 XI 1070.

- **Nowy zatwierdzony punkt:** **18 X 1073**, `von_Hohenzollern(20261014-200855).ck3` (duplikat `von_Hohenzollern(20261014-201208).ck3`, ten sam SHA-256); CK3 1.20.1, te same 19 modów i 10 DLC. **Poprzedni punkt:** 12 XI 1070, różnica 1070 dni gry.
- **7 VII 1071:** zgon Leopolda (81336), przyczyna NIEUSTALONA.
- **7 V 1072:** zwycięstwo Burkharda (66952) w bitwie przeciw Adelheid (31878).
- **17 I 1073:** zwycięstwo Burkharda w wojnie roszczeniowej i przejęcie `c_hohenberg` od Adelheid. Burkhard nadal jest wasalem Rudolfa; Rudolf nadal księciem Szwabii, Heinrich cesarzem.
- **18 X 1073:** Hedwig (41150) w ciąży, syn Burkhard (79306) ma `curious`; brak potwierdzonego nowego porodu. Radbot (66953) wykonuje `task_increase_control`. Lokalna zmiana `b_rottweil` została odnotowana bez daty i bez łączenia z podbojem Burkharda.
- **Zachowane ograniczenia:** nieustalone przyczyna zgonu, dowódcy, frakcje, opinie UI, aktualny kapelan i medyk, stan regencji 18 X i wynik ciąży. Archiwalne screeny do 1 X 1073 zachowują własne daty i odrębne źródła.
- Dodano [raport 18 X 1073](../07_ANALIZY/raporty_zmian/CK3_1073-10-18_weryfikacja.md), [oś 1070–1073](../campaign/Os_czasu_Zollern_1070-1073.md) i [kartę Hohenbergu](../03_TERYTORIA/HRABSTWA/c_hohenberg/karta.md); zaktualizowano stan kampanii, indeks save'ów, karty postaci i terytoriów. Żadnych nowych fikcyjnych wydarzeń nie wpisano.


## 14 października 2026 — kanon charakterów i źródła mechanik CK3

**Decyzja użytkownika:** „zapisz do kanonu, sprawdz informacje o mechanikach ck3 o tym jak odczytywac charakter itd”.

- Dodano [kanon charakterów i rady na 12 XI 1070](../campaign/Kanon_charakterow_1070-11-12.md), odwołując się do potwierdzonych cech z save'a i stanowisk z ekranów.
- Dodano [obowiązujące zasady interpretacji charakteru](../05_MECHANIKI_CK3/Zasady_interpretacji_charakteru.md): kategorie cech, stres, AI, wykształcenie, relacje i cztery poziomy wiarygodności.
- Zweryfikowano reguły CK3 z zewnętrznymi danymi opartymi o pliki `common/traits` i encyklopedię (CK3DB, częściowo 1.20.1, częściowo 1.20.0.4). Zewnętrzne reguły są **wiedzą o mechanice**, a nie wydarzeniami kampanii.
- Potwierdzono, że **19 aktywnych modów** może zmieniać efekty mechanik. Wskazówki dotyczące możliwych psychologicznych napięć pozostają opisanymi interpretacjami dla Astry, nie faktami o działaniach bohaterów.
- Nie przesuwano punktu świata poza 12 XI 1070 i nie dopisywano fikcyjnych czynów do osi.

## 14 października 2026 — rozpoznanie cech z binarnego zapisu 12 XI 1070

**Polecenie użytkownika:** odczytać cechy z plików gry i dodać je do kart postaci.

- Ponownie nadesłany plik `von_Hohenzollern(20261014-155345).ck3` ma ten sam SHA-256 co już zatwierdzony save `von_Hohenzollern(10).ck3`, więc **oś nie została przesunięta**.
- Zidentyfikowano tabelę **307 nazw cech** w `gamestate` oraz ich indeksy w rekordach (`traits`, token 1608).
- Uzupełniono osiem istniejących kart cechami Burkharda, Hedwig, Radbota, Walpurgi, Meinharda, Ingi, Hupolda III i Leopolda; powiązano Hupolda III z ID 32545.
- Utworzono karty Rudolfa (35525), Gerlacha (72054) i Siegmunda (76331).
- Zaktualizowano indeks postaci i raport źródłowy, w tym odróżnienie cech od automatycznych opisów charakteru i odrębnych pól save'a.
- Nie zatwierdzono żadnego nowego zdarzenia fabularnego ani przyszłego wyniku wojny, sukcesji czy choroby.

Dokument źródłowy: [rozpoznanie cech w raporcie](../07_ANALIZY/raporty_zmian/CK3_1070-11-12_weryfikacja.md#9-uzupełnienie-pełne-rozpoznanie-pola-cech-postaci-14-x-2026).

## 14 października 2026 — zatwierdzenie punktu 12 XI 1070

**Decyzja użytkownika:** „Tak” — akceptacja wcześniej przedstawionego pakietu odczytu `von_Hohenzollern(10).ck3`.

**Poprzedni zatwierdzony save:** 2 VIII 1070, `von_Hohenzollern(9).ck3`.  
**Nowy zatwierdzony save:** 12 XI 1070, `von_Hohenzollern(10).ck3`.  
**Różnica:** 102 dni w świecie gry.  
**Wersja gry:** CK3 1.20.1.

### Aktualizacje

- Zmieniono aktualny punkt stanu w `01_KAMPANIA/stan_aktualny.md` oraz metrykę starszego kanonu.
- Dodano wpis kontrolny w `campaign/Os_czasu_Zollern_1068-1070.md`, zachowując wcześniejsze datowane wydarzenia.
- Zmieniono `06_MATERIALY_ZRODLOWE/indeks_saveow.md` i status raportu `07_ANALIZY/raporty_zmian/CK3_1070-11-12_weryfikacja.md` z oczekującego na zatwierdzony.
- Dodano obserwacje na 12 XI w kartach Burkharda (66952), Hedwig (41150), ich synów (79306, 81336), hrabstwa Zollern i księstwa Szwabii.
- Założono dostępne karty dodatkowych osób z odczytu oraz zaktualizowano indeks. Karty nieobejmujące pełnego stanu postaci jawnie oznaczają braki.

### Wynik źródłowy

Żyją: Burkhard, Hedwig i obaj synowie; rodzina bez zmiany listy dzieci. Utrzymani posiadacze odczytanych tytułów: Burkhard — `c_zollern` i `b_zollern`, Rudolf — `d_swabia` i `c_ulm`, Heinrich — `e_hre`, Matthias — `c_urach`, Adelheid — `c_hohenberg`. W prawach Burkharda zachowany podział konfederacyjny i preferencja męska.

### Ograniczenia

Nie dopisano niepotwierdzonych bitew, wojen, wydarzeń religijnych, narodzin ani zmian w radzie. Statystyki z surowych tokenów binarnych nie są traktowane jako wartości interfejsu gry. Nie ustalono aktualnych zasobów, pełnego składu dworu, frakcji, armii, budynków ani sukcesji poszczególnych tytułów. Osobne karty Rudolfa (35525), Gerlacha (72054) i Matthiasa (61022) nie zostały utworzone w tej operacji; ich dane pozostają w raporcie źródłowym.

[Stan aktualny](stan_aktualny.md) · [Raport 12 XI 1070](../07_ANALIZY/raporty_zmian/CK3_1070-11-12_weryfikacja.md) · [Oś wydarzeń](../campaign/Os_czasu_Zollern_1068-1070.md)
