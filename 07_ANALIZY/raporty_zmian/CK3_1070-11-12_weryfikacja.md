# Weryfikacja zapisu CK3 — 12 listopada 1070

**Status:** ODCZYT ŹRÓDŁA / OCZEKUJE NA AKCEPTACJĘ DO KANONU  
**Data analizy:** 14 października 2026  
**Źródło:** `von_Hohenzollern(10).ck3`  
**Porównanie:** `von_Hohenzollern(9).ck3` z 2 VIII 1070  
**Nie przesuwa samodzielnie osi czasu i nie zatwierdza nowych wydarzeń.**

## 1. Kontrola techniczna

| Pole | Nowy save |
|---|---|
| Data świata | **12 XI 1070** |
| Poprzednia data | 2 VIII 1070 |
| Różnica | 102 dni gry |
| Wersja CK3 | 1.20.1 |
| Metadane postaci gracza | „Hrabia Burkhard” |
| Metadane tytułu | „Hrabstwo Zollern” |
| Wielkość archiwum | 19 970 827 bajtów |
| `gamestate` rozpakowany | 112 632 961 bajtów |
| SHA-256 nowego pliku | `6bf7eeda89f32236668a2370ca1e9789445f65fb81486c11514c94337e2ab015` |
| SHA-256 poprzedniego pliku | `0f41b1b9910d62c306de126bd6d262dceb59030819fd379dad22b17c86efc813` |

Format Jomini: nagłówek `SAV01`, metadane i skompresowana sekcja ZIP `gamestate`. Data odczytana z kodowanego pola w metadanych, sprawdzona względem znanego zapisu 2 VIII 1070 (zmiana licznika odpowiada 102 dniom po 24 jednostki dziennie).

W obu plikach znajdują się ścieżki 19 tych samych modów (zestaw i kolejność wpisów nie uległy zmianie). Nie oznacza to automatycznie identyczności kodu modów lub ich wersji w grze. Wersja CK3 w obu zapisach to 1.20.1.

## 2. Rodzina władcy

**Bezpośrednio odczytane rekordy żyjących postaci:**

| ID | Postać | Relacja | 2 VIII 1070 | 12 XI 1070 |
|---|---|---|---|---|
| 66952 | Burkhard von Hohenzollern | hrabia Zollern | żyje | żyje |
| 41150 | Hedwig | żona | żyje | żyje |
| 79306 | Burkhard | syn, ur. 27 XII 1068 | żyje | żyje |
| 81336 | Leopold | syn, ur. 21 IV 1070 | żyje | żyje |

W rekordach obojga rodziców lista dzieci pozostaje `[79306,81336]`. Nie zidentyfikowano dodatkowego dziecka pary **w tej konkretnej liście**. Małżeństwo Burkharda i Hedwig pozostaje zapisane.

W rekordzie Burkharda nadal znajdują się nazwy praw:
- `confederate_partition_succession_law` — podział konfederacyjny;
- `male_preference_law` — preferencja męska;
- `crown_authority_0` — oznaczenie poziomu autorytetu w zapisie.

Nie utożsamiać tego z pełną analizą bieżącej kolejności sukcesji dla wszystkich tytułów.

## 3. Tytuły, Szwabia, Cesarstwo

W obu zapisach **identyczny posiadacz** widnieje dla następujących odczytanych tytułów:

| Tytuł techniczny | ID posiadacza | Postać |
|---|---|---|
| `c_zollern` | 66952 | Burkhard |
| `b_zollern` | 66952 | Burkhard |
| `d_swabia` | 35525 | Rudolf |
| `k_swabia_herzog` | 35525 | Rudolf |
| `c_ulm` | 35525 | Rudolf |
| `c_urach` | 61022 | Matthias |
| `c_hohenberg` | 31878 | Adelheid |
| `e_hre` | 41198 | Heinrich |

Dla `c_zollern`, `b_zollern`, `d_swabia`, `k_swabia_herzog`, `c_ulm`, `c_urach` i `c_hohenberg` porównane pełne rekordy tytułów są identyczne bajtowo. Rekord `e_hre` zawiera nowy dodatkowy znacznik daty o nieustalonej semantyce; brak podstaw do opisywania go jako wydarzenia politycznego. Odrębnego tokenu `k_swabia_herzog` nie należy nazywać nowo utworzonym królestwem bez interpretacji modów.

Wśród żyjących w nowym zapisie pozostają także ważne dla Szwabii postacie: Hupold 32545, Friedrich 40600, Hermann 40599, Adalbert 35185, Berthold 41146 i Berthold 43117. Ich obecność w rejestrze żyjących **nie** dowodzi pełnej stabilności wszystkich posiadłości, urzędów i relacji.

## 4. Najbliższe otoczenie

W obu zapisach jako żyjący występują:

| Postać | ID | Kontekst wcześniejszych materiałów |
|---|---:|---|
| Radbot | 66953 | wcześniej kanclerz, następnie w osi nazwany marszałkiem |
| Walpurga | 66954 | mistrzyni szpiegów w źródle z 1067 |
| Amalie | 66955 | małżeństwo z Radbotem zatwierdzone 1 VI 1070 |
| Meinhard | 69353 | kapelan, wiadomości religijne oraz zadanie fabrykowania roszczenia |
| Inga | 69354 | osobisty medyk w źródłach z 1066/1067 |
| Gerlach | 72054 | rycerz we wcześniejszym przekroju |
| Bertha z Rheinfelden | 43664 | przyjęta do wychowania 2 VIII 1069 |

Sam fakt obecności postaci oraz flagi `is_in_the_council` nie dowodzi, że pełnią one obecnie identyczne funkcje jak w starym przekroju. Funkcje i miejsce pobytu 12 XI wymagają pełnego rozpoznania powiązanych managerów lub potwierdzenia w interfejsie.

## 5. Liczby bazowe umiejętności — bez korekt UI

Poniższe sześć liczb pochodzi z jednego pola tablicowego rekordu postaci (token 10661). Zestawiono je w kolejności zapisu odpowiadającej typowemu zestawowi dyplomacja, wojskowość, zarządzanie, intryga, nauka, waleczność; **nie są to zweryfikowane wynikowe wartości panelu postaci z modyfikatorami**. Każda z tych tablic jest identyczna w obu zapisach.

| Postać (ID) | Dypl. | Wojsk. | Zarz. | Intryga | Nauka | Walecz. |
|---|---:|---:|---:|---:|---:|---:|
| Burkhard 66952 | 3 | 5 | 4 | 5 | 0 | 8 |
| Hedwig 41150 | 5 | 8 | 4 | 9 | 1 | 5 |
| Burkhard syn 79306 | 0 | 1 | 0 | 1 | 1 | 1 |
| Leopold 81336 | 0 | 0 | 0 | 0 | 0 | 0 |
| Rudolf 35525 | 7 | 6 | 4 | 8 | 3 | 4 |
| Heinrich 41198 | 5 | 5 | 4 | 8 | 5 | 6 |
| Hupold 32545 | 4 | 9 | 4 | 4 | 9 | 8 |
| Radbot 66953 | 8 | 9 | 0 | 4 | 3 | 8 |
| Walpurga 66954 | 7 | 10 | 4 | 9 | 10 | 3 |
| Amalie 66955 | 6 | 2 | 4 | 4 | 10 | 8 |
| Meinhard 69353 | 5 | 3 | 6 | 7 | 12 | 7 |
| Inga 69354 | 3 | 5 | 3 | 5 | 11 | 5 |
| Gerlach 72054 | 2 | 10 | 10 | 0 | 7 | 14 |
| Bertha 43664 | 3 | 2 | 1 | 1 | 3 | 2 |

## 6. Zmiany w rekordach bez przypisanej interpretacji

W rekordzie Burkharda część danych pomocniczych uległa zmianie (w szczególności surowe pola liczbowe i jedna lista identyfikatorów doktryn); nie można na tej podstawie ustalić nowego zdarzenia lub zmiany wiary. Rekordy Hedwig, Meinharda, Ingi i części innych postaci również zawierają zmiany surowych pól stanu. Nie należy interpretować ich przez analogię bez słownika tokenów.

Pełne zliczenie rekordów: pula zidentyfikowanych żyjących wzrosła z 43 970 do 44 102, a pula rekordów zmarłych z 33 288 do 33 361. Zmiany populacji technicznych pul **nie są bezpośrednią liczbą narodzin i zgonów**; nie wolno przypisywać im takich zdarzeń.

## 7. NIEUSTALONE / potrzebne dodatkowe źródła

- Bieżące wartości złota, prestiżu, pobożności, przychodu, kontroli i rozwoju.
- Pełna lista aktywnych radnych i dworzan, urzędy, wyjazdy, kontakty i opinie.
- Bieżący stan armii, oddziałów zbrojnych, oblężeń, aktywnych wojen i frakcji.
- Wszystkie budynki i kolejki inwestycyjne oraz ich stan 12 XI 1070.
- Czy fabrykowanie roszczenia przez Meinharda ukończono po 2 X 1070.
- Czy zrealizowano lub uruchomiono nowy spisek wobec Meinharda, opisany na wcześniejszym screenie jako planowany.
- Znaczenie niezmapowanych pól binarnych i dokładne wersje aktywnych modów.

Wymienionych nieustalonych elementów nie dopisywać jako faktów. Sprawdzone daty i tytuły z nowego save'a można przedłożyć użytkownikowi do zatwierdzenia jako kolejny punkt osi.

## 8. Proponowane dokumenty docelowe — po akceptacji użytkownika

1. `01_KAMPANIA/stan_aktualny.md` — nowy zatwierdzony punkt 12 XI 1070.
2. `campaign/Os_czasu_Zollern_1068-1070.md` — datowany punkt kontrolny, bez dopisywania wydarzeń nieodczytanych z gry.
3. Karty `02_POSTACIE/66952`, `41150`, `79306`, `81336` — nowa obserwacja, bez niszczenia poprzednich wpisów.
4. Karty `03_TERYTORIA/HRABSTWA/c_zollern` i `03_TERYTORIA/KSIESTWA/d_swabia` — utrzymanie właścicieli na nową datę.

**GRA DOSTARCZA FAKTÓW. KANON USTALA HISTORIĘ.** Żadna niezweryfikowana mechanika ani domniemane wydarzenie nie stają się faktem.
