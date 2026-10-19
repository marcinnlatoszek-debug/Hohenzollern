# Kanon polityczny Cesarstwa i Szwabii — 6 III 1067 – 18 X 1073

**Status: ZATWIERDZONE do kanonu przez użytkownika 15 X 2026 („dodaj zmiany i informacje do kanonu i do wglądu dla astry”).**
**Granica faktów fabularnych: 18 października 1073.** Zatwierdzony pełny zapis: `von_Hohenzollern(20261014-200855).ck3`, CK3 1.20.1. Porównanie: `von_Hohenzollern(10).ck3` z 12 XI 1070. Późniejszy `von_Hohenzollern(20261015-182245).ck3` ma datę **4 II 1075** i **nie jest** podstawą przenoszenia stanu politycznego 1075 do 1073.

**Podstawa:** zakończony raport Deep Research „Raport dla Astry — Cesarstwo, Szwabia i Hohenzollernowie do 18 października 1073” (15 X 2026), obejmujący odczyt struktur binarnego `gamestate`, porównanie zapisów oraz [wcześniejszy zatwierdzony raport 1073](../07_ANALIZY/raporty_zmian/CK3_1073-10-18_weryfikacja.md). To kanoniczna rejestracja **odczytanych danych**, nie dowód zdarzeń, których save nie zachował. Dla wydarzeń wcześniej potwierdzonych screenami obowiązuje również [oś 1070–1073](Os_czasu_Zollern_1070-1073.md).

## Zasada interpretacji źródeł

- **[SAVE]**: odczyt rekordu binarnego lub porównanie pól dwóch zapisów; podano ID i klucze, gdzie dostępne.
- **[SCREEN/KANON]**: wcześniej zatwierdzony ekran lub dokument projektu.
- **[WNIOSKOWANIE]**: interpretacja polityczna, nie osobny fakt gry.
- **[NIEUSTALONE]**: brak dostatecznego źródła; nie dopisywać rozstrzygnięcia.
- Pamięć postaci o wojnie lub bitwie **nie jest** automatycznie pełnym dziennikiem wszystkich konfliktów świata. Wojna zwycięska nie oznacza automatycznie, że zwycięzca osobiście otrzymał sporny tytuł.
- W kampanii aktywnych jest 19 modów; mechaniki i prawdziwa historia XI wieku nie mogą zastępować odczytu gry.

## 1. Wojny cesarza Heinricha (ID 41198) — zachowane w jego pamięciach

| Data rozpoczęcia | Data zakończenia | Strony i cel | Casus belli | Wynik i dowód |
|---|---|---|---|---|
| **19 XII 1067** | **2 VI 1068** | Heinrich 41198 przeciw Domenicowi 32313; tytuł `d_istria` (ID 7413) | `war_memory_cb_fallback`: dokładna podstawa prawna **NIEUSTALONA** | **Zwycięstwo Heinricha**; [SAVE] `memory 15686` (`offensive_war`), `memory 18200` (`war_won`) |
| **12 VIII 1070** | **1 VI 1073** | Heinrich 41198 przeciw Svendowi 33989; cel `c_stormarn` (ID 1889) | `war_memory_cb_de_jure`; `war_liege=199` (`e_hre`) | **Zwycięstwo Heinricha**; [SAVE] `memory 29684` (`offensive_war`), `memory 42081` (`war_won`) |

To **dwie ofensywne wojny zachowane w pamięciach Heinricha** do 18 X 1073. Brak rozpoznanej pamięci o jego wojnie defensywnej nie dowodzi, że nigdy nie uczestniczył pomocniczo w innych konfliktach. **Nie utożsamiać** z osobnymi wojnami Rudolfa przeciw Einhardowi, o Marchię Nordgau, wojną Czech o Nordgau, wojną Bawarii o Salzburg ani wojną Burkharda o Hohenberg.

**[NIEUSTALONE]**: dokładne żądania i warunki pokoju w Istrii; sojusznicy i skład wojsk obu stron; szczegółowy pokój w Stormarn; przyczyny konkretnych zmian posiadaczy po wojnie.

### Bitwy związane z Heinrichem

| Data | Zdarzenie | Źródło | Granica |
|---|---|---|---|
| **4 III 1071** | Przegrana strony Heinricha z Ottone (33368) pod `b_auch` (ID lokalizacji 17060) | [SAVE] `battle_lost_memory 16810558`, `ruler=41198` | Nieustalone liczebność, straty i przypisanie do konkretnej wojny |
| **15 XI 1072** | Przegrana strony Heinricha z Gottfriedem (31670) pod `b_lugues` (ID lokalizacji 16761) | [SAVE] `battle_lost_memory 39785`, `ruler=41198` | Nieustalone liczebność, straty i przypisanie do konkretnej wojny |
| **19 IV–7 V 1072** | Bitwa Burkharda przeciw Adelheid pod Hohenbergiem; zwycięstwo Burkharda **7 V** | [SCREEN/KANON] 750 przeciw 252 żołnierzom na ekranie 19 IV, 4 rycerzy przeciw 2; [SAVE] pamięć zwycięstwa | **1002** żołnierzy na ekranie; nie ustalono dokładnych strat ani dowódców |

**Największa bitwa:** Hohenberg jest największym **liczbowo udokumentowanym** starciem w dostępnych materiałach projektu, ale **NIE** jest udowodnioną największą bitwą całej kampanii/Cesarstwa. Nie ma globalnego rankingu liczebności.

## 2. Elektorzy i ustrój Cesarstwa

[SAVE] Lista `hre_elector_list` zawiera **te same siedem tytułów i tych samych posiadaczy** 12 XI 1070 i 18 X 1073:

| Tytuł elektorski | ID tytułu | Elektor 18 X 1073 | ID postaci |
|---|---:|---|---:|
| Kolonia `c_cologne` | 2360 | Anno | 30719 |
| Moguncja `c_mainz` | 2994 | Siegfried | 36441 |
| Trewir `c_trier` | 2250 | Udo | 36944 |
| Czechy `d_bohemia` | 9915 | Vratislav | 36642 |
| Wschodnia Frankonia `d_east_franconia` | 3095 | **Heinrich** | 41198 |
| Ostmark `d_ostmark` | 9060 | Kasper | 35857 |
| Angria `d_angria` | 1641 | Ordulf | 34660 |

Heinrich jest jednocześnie cesarzem i elektorem. [SCREEN/KANON] W 1067 Rudolf pojawia się jako kandydat do cesarskiej sukcesji; **nie potwierdzono**, że nadal figuruje jako kandydat 18 X 1073. **[NIEUSTALONE]**: aktualne głosy, preferencje elektorów, ich opinie o Heinrichu i szczegółowa kolejność sukcesji.

## 3. Frakcje i relacje polityczne

[SAVE] **12 XI 1070:** nie odczytano aktywnej frakcji z `target=41198` (Heinrich) ani `target=35525` (Rudolf).

[SAVE] **18 X 1073:** aktywna **frakcja populistyczna** `id=16777365`, `type=populist_faction`, `target=41198`, `faith=80`, `culture=237`. Nie odczytano aktywnej frakcji z Rudolfem jako celem. Nazwy wiary i kultury, skład, przywódca, liczebność i data powstania frakcji **NIEUSTALONE**. Frakcja pojawiła się w nieustalonym momencie między oboma punktami.

[SCREEN/KANON] **17 XII 1071**, opinie o Rudolfie: Hupold III **−55**, Adalbert **−42**, Louis **−23**, Berengar **+7**. To nie dowodzi wspólnej frakcji ani spisku.

[SCREEN/KANON] **6 III 1067**: między Rudolfem a Heinrichem widoczny był modyfikator **−20** związany ze zwolnieniem z rady cesarskiej; **kierunek opinii niejednoznaczny** w starszych źródłach. Hierarchia **Burkhard → Rudolf → Heinrich** pozostaje potwierdzona 18 X 1073; brak dowodu wojny między Rudolfem a Heinrichem.

**[NIEUSTALONE]**: pełne małżeństwa polityczne i sojusze Cesarstwa, opinie Heinricha o wszystkich książętach, bieżąca siła frakcji, pełna sieć powiązań. Nie dopisywać historycznych sojuszy na podstawie rzeczywistego XI wieku.

## 4. Regencja i polityka Szwabii

[SCREEN/KANON] **16 XI 1070** Burkhard występuje jako regent (według gracza czwarty miesiąc), ale **osoba objęta tą regencją NIEUSTALONA**. Nie utożsamiać automatycznie z Rudolfem.

[SCREEN/KANON] **3 VIII 1073** Burkhard rozpoczyna **odrębną, potwierdzoną regencję nad Rudolfem**. Powiadomienie z 2 VIII i ekran decyzji z 3 VIII odnoszą się do tej samej sekwencji. **Czy regencja trwała 18 X 1073 i kiedy się zakończyła — NIEUSTALONE.** Powiadomienie wskazujące 27 IX jako możliwy koniec nie jest dowodem faktycznego zakończenia.

[SAVE] Między 12 XI 1070 a 18 X 1073 spośród **31 bezpośrednich hrabstw Szwabii** zmienił się posiadacz tylko **`c_hohenberg`: Adelheid 31878 → Burkhard 66952**, 17 I 1073. Burkhard nadal nie jest księciem ani niezależnym władcą. Zmiana `b_rottweil`: Lothar 48230 → Wenzel 44447, bez daty i potwierdzonej przyczyny.

## 5. Wybrane zmiany tytułów poza Szwabią — porównanie 1070–1073

**Uwaga:** zmiana posiadacza to fakt porównawczy, **nie automatycznie wynik wojny**. Przyczyny zmian poniżej są NIEUSTALONE, o ile nie podano inaczej.

| Tytuł | 12 XI 1070 (ID posiadacza) | 18 X 1073 (ID posiadacza) |
|---|---:|---:|
| `e_hre` | Heinrich 41198 | Heinrich 41198 |
| `d_istria` | brak odczytanego posiadacza | brak odczytanego posiadacza |
| `c_stormarn` | 38985 | 16823767 |
| `d_nordgau` | 35710 | 78703 |
| `d_salzburg` | 36051 | brak odczytanego posiadacza |
| `d_osterreich` | 37607 | 40914 |
| `c_vienna` | 37607 | 40914 |
| `c_holstein` | 38985 | 81855 |
| `c_ditmarschen` | 38985 | 81855 |
| `c_brunswick` | 40799 | 34660 |

Wojna de iure o Stormarn zakończyła się zwycięstwem Heinricha, ale posiadacz `c_stormarn` w 1073 **nie jest Heinrichem**; nie wolno utożsamiać zwycięstwa z osobistym objęciem tytułu.

## 6. Otoczenie Hohenzollernów — potwierdzony kontekst

- **Burkhard 66952:** hrabia Zollern i od 17 I 1073 Hohenbergu; żona Hedwig 41150; senior Rudolf 35525; nad nim Heinrich 41198.
- **Hedwig 41150:** córka Hupolda III 32545; 18 X 1073 jest w ciąży; wynik nieustalony.
- **Burkhard junior 79306:** żyje, cecha `curious` na 18 X 1073; dzień uzyskania cechy nieustalony.
- **Leopold 81336:** zmarł 7 VII 1071; przyczyna nieustalona.
- **Hupold III:** sojusznik Burkharda w wojnie o Hohenberg, jego armia oblega Ebingen 8 VI 1072; nie ma dowodu dowodzenia bitwą 7 V.
- **Rada:** Siegmund `task_foreign_affairs`, Gerlach `task_collect_taxes`, Radbot `task_increase_control` (wcześniej `task_organize_levies`), Walpurga `task_disrupt_schemes`. Aktualny kapelan i medyk 18 X 1073 NIEUSTALENI.
- **Sojusze i małżeństwa:** Burkhard–Hedwig potwierdzone; Radbot–Amalie 1 VI 1070 potwierdzone. Powinowactwo z Hupoldem nie dowodzi innych umów.

## 7. Granica późniejszych zapisów

[SAVE — metadane] `von_Hohenzollern(20261015-182245).ck3` wskazuje **4 II 1075**. Użytkownik zatwierdził tutaj **włączenie raportu o latach 1067–1073**, a **nie przesunięcie punktu świata na 1075**. Danych o stanie świata z 1075 nie wolno wykorzystywać jako stanu na 18 X 1073.

## 8. Materiały powiązane

- [Główna oś kanonu](Kanon_i_os_czasu_Zollern_1066.md)
- [Oś 1070–1073](Os_czasu_Zollern_1070-1073.md)
- [Brief dla Astry — Cesarstwo i Szwabia](Brief_dla_Astry_Cesarstwo_i_Szwabia_do_1073-10-18.md)
- [Raport pełnego save'a 18 X 1073](../07_ANALIZY/raporty_zmian/CK3_1073-10-18_weryfikacja.md)


## Aneks autorski — 19 X 2026

Autor zatwierdził historyczne tło konfliktu Henryka IV z Sasami (1073–1075) do wykorzystania literackiego. **Nie jest ono dodatkową wojną potwierdzoną w save'ie**; obowiązuje rozdział między historią rzeczywistą a stanem gry. Szczegóły i korekty raportu: [Tło historyczne Cesarstwa 1073–1075 — zatwierdzone](Tlo_historyczne_Cesarstwa_1073-1075_zatwierdzone.md). Zapis `von_Hohenzollern(20261019-041612).ck3` wymaga odrębnego odczytu; nie dopisano na jego podstawie nowych wojen ani frakcji.
