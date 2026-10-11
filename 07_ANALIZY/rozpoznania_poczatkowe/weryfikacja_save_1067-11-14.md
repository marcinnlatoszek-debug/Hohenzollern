# Kontrola nadrzędnego źródła — save CK3 z 14 XI 1067

**POTWIERDZONE_SAVE — oryginalny binarny zapis:** `von_Hohenzollern(20261011-173838).ck3`, SHA-256 `a64b8551e487aef4fc3df4edc4d1909f51af590829ff4afe6c8e3d5370b66d6b`, 1.20.0.4, `meta_date=1067-11-14` (`53154528` w surowym Jomini). Kontener `SAV0103`; `gamestate` **82 755 991 B**; ZIP CRC poprawne. Plik `von_Hohenzollern(20261011-175242).ck3` ma **identyczny SHA-256**, więc jest bajtowym aliasem, nie osobną migawką. Odczyt selektywny struktury binarnej, nie interpretacja widoku mapy.

**Priorytet kanonu:** aktualny save rozstrzyga *stan mechaniczny na 14 XI*. Screen z innego dnia rozstrzyga tylko to, co wówczas było na nim widoczne; starszych obserwacji nie należy kasować, ale konflikty dat i stanu opisuje się jawnie. Raport nie zastępuje pełnego audytu każdej postaci, tytułu i historii wszystkich państw.

## Bezpośrednia weryfikacja dat (Jomini)

Dekodowanie daty binarnej według formatu Jomini: `days=(number/24)%(365)`, `year=(number/24)/365−5000` i kalendarz 365-dniowy, bez 29 lutego. Dzięki temu odczytano **14 XI 1067** dla nowego save’a.

**Ważna korekta wcześniejszej transkrypcji:** ponownie sprawdzony plik `von_Hohenzollern(9).ck3`, SHA-256 `adf79a1b8cecc8909850356c1df81d24a2c04cacd4528f33e16ed10129d8d991`, zawiera binarne `meta_date=53147688`, czyli **2 II 1067**, a nie 29 I 1067. Wcześniejszą datę 29 I należy oznaczyć jako błędną interpretację odczytu, nie jako niezależny fakt. Między save’em (9) i nowym upłynęło **285 dni gry** (OBLICZONE).

## Wojna 36 o Szwabię — AKTYWNA 14 XI 1067

**POTWIERDZONE_SAVE:** `wars/active_wars/36` istnieje; `start_date=1067.4.28`, `type=claim_cb`, `targeted_titles=[1216]`, attacker=31865 (Berthold), defender=33226 (Rudolf), claimant=38078 (Hermann). Wojna **nadal trwa**. Nie ma podstaw do wpisania pokoju ani zmiany posiadacza księstwa tylko na podstawie mapy.

### Uczestnicy z własnymi datami zapisu

| Strona | CK3 ID | Osoba | Data w rekordzie uczestnictwa (SAVE) |
|---|---:|---|---|
| Atak | 31865 | Berthold | **28 IV 1067** |
| Atak | 38078 | Hermann | **21 VI 1067** |
| Obrona | 33226 | Rudolf | **28 IV 1067** |
| Obrona | 31145 | Ludwig | **11 V 1067** |
| Obrona | 62634 | Burkhard | **15 V 1067** |
| Obrona | 37502 | Egino II z Zollern | **28 X 1067** |
| Obrona | 31271 | Eberhard VI z Nellenburgu | **7 XI 1067** |
| Obrona | 34995 | Kuno | **13 XI 1067** |

**KOREKTA poprzedniej osi, oparta na save:** Egino, Eberhard i Hermann mają w wewnętrznych rekordach wojny daty **o pięć dni wcześniejsze** niż ekranowe powiadomienia z datami odpowiednio **2 XI**, **12 XI** i **26 VI**. Powiadomienia były rzeczywiście widoczne na screenach. **Nie wolno utożsamiać bez dalszego źródła daty udziału w rekordzie z datą komunikatu na ekranie ani dopisywać powodu pięciodniowej różnicy.** Do datowania mechanicznego udziału używać save’a, a daty ekranowe zachować jako osobne zdarzenia interfejsu.

**Nowa postać w obronie:** Kuno **ID 34995** figuruje z datą **13 XI**. Nie utożsamiać automatycznie tego uczestnictwa z obecnością jego armii w konkretnej prowincji.

### Potwierdzenie bitwy pod Hohenbergiem

W obrębie wojny 36 zapisany jest **rekord starcia** łączący **Hermanna 38078** i **Burkharda 62634** z liczebnościami wejściowymi **463** i **745**, oraz identyfikatorem miejsca **2759**. Jest to zgodne z ekranami `Battle of Hohenberg` z lipca–sierpnia. Rekord zawiera także surowe wartości numeryczne i logiczne, dla których w tym odczycie **nie wykonano dostatecznej weryfikacji znaczenia wszystkich kluczy**. Z tego powodu **nie ogłaszamy jeszcze ostatecznego wyniku bitwy, dokładnych strat ani listy zabitych** na podstawie samych nieopisanych flag. Zapis dowodzi natomiast, że wojna 36 istnieje nadal na 14 XI.

## Rodzina i osoby najbliższe Burkhardowi

- **Burkhard 62634:** żyje; dom von Hohenzollern 12843, domena `[1239,1240]` (Hohenberg), `primary_spouse=38789` oraz `spouse=38789` nadal w rodzinie. Nie znaleziono wpisów `child` w sprawdzonym `family_data`; nie wnioskować stąd o przyszłych ciążach lub dzieciach.
- **Irmengard 38789:** żyje, `primary_spouse=62634`; `court_data/employer=62634`, `join_court_date=1067.1.3`. Data **3 I 1067** jest zatem dodatkowo potwierdzona jako dzień jej dołączenia na dwór męża i pozostaje zgodna z wcześniej podaną przez gracza datą ślubu. Pole dworu nie jest osobnym dowodem dokładnego przebiegu ceremonii.
- **Gunzelin 65692:** obecny w `living`, a więc **żyje 14 XI 1067**. Nadal ma `court_data/employer=62634` i `council_task=16782045` odpowiadające mistrzowi intryg Burkharda. W `traits` nie stwierdzono `wounded_1/2/3` w tej migawce; nie jest to dowód ustalonego przebiegu leczenia ani braku wszelkich innych efektów urazu. Komunikat o ranieniu go **23 VIII** pozostaje prawidłowym datowanym świadectwem wcześniejszej bitwy.
- **Gerhard 62635:** obecny w `living`, powiązany z `employer=62634` i `army=388`. **POTWIERDZONE_SAVE:** jest dowódcą armii Hohenbergu także 14 XI (nie tylko 7 VI).
- **Egino II 37502, Eberhard VI 31271 i Berthold 31865** obecni w `living`; ich strony wojny potwierdzono w `active_wars/36`.

## Sprawdzone dane wojska i gospodarki (14 XI 1067)

`landed_data` to zestawienie domeny; nie należy mylić `current_strength` ze stanem jednej konkretnej wystawionej armii na ekranie.

| Władca (ID) | `current_strength` | `strength` | `levy` |
|---|---:|---:|---:|
| **Burkhard 62634** | **745** | **750** | **147** |
| **Rudolf 33226** | **868** | **872** | **669** |
| **Berthold 31865** | **1190** | **1193** | **886** |
| **Hermann 38078** | **297** | **361** | **158** |
| **Egino 37502** | **210** | **210** | **7** |
| **Eberhard 31271** | **441** | **448** | **137** |

**Weryfikacja oddziałów w sekcji `armies`:**

- **Armia 388 Hohenbergu:** `commander=62635` (Gerhard), `unit=395`, zapisany identyfikator miejsca `2759`, supply 100. Nie należy utożsamiać ID miejsca z nazwą terenu bez weryfikacji mapowania.
- **Armia 355 Rudolfa:** `commander=33226`, `unit=359`, identyfikator miejsca `2768`, supply 100.
- **Armia 16777527 Bertholda:** `commander=31865`, `unit=16777533`, identyfikator miejsca `3099`, zaopatrzenie odczytane około 98,70.
- Dane wojsk na screenach 31 VII–13 XI są historią konkretnych dni, nie automatycznie stanem 14 XI. Zmiana liczebności nie dowodzi określonego starcia ani skutecznego dotarcia do celu marszu.

**Burkhard — własne sprawdzone zasoby (14 XI):** złoto **31.82844**, bieżąca pobożność **68.9125**, prestiż **950.91492**, XP zarządzania **525**. W porównaniu z udokumentowanym save’em z 7 VI (29.34111 / 61.75 / 925.7664 / 337.5) są to zmiany stanu, nie dowód konkretnych decyzji.

**Cechy i wiara:** bazowe skille Burkharda `[3,5,4,5,0,8]` i sześć zapisanych traitów: `ambitious`, `diligent`, `patient`, `education_stewardship_3`, `lifestyle_gardener`, `intellect_good_2`. `roman_rite`, indywidualne `tenet_ora_et_labora`, spełnienie duchowe **10** nadal obecne. Nie datować genezy osobistych przekonań bez osobnego dowodu.

## Zasady zastosowania do kroniki

1. **POTWIERDZONE_SAVE (14 XI):** aktualna wojna, lista uczestników i ich daty z pola `date`, żyjący Gunzelin, urzędy, małżeństwo, liczby i dowódcy.
2. **POTWIERDZONE_SCREEN (dawniejsze daty):** cztery migawki trwającej wówczas bitwy, Gunzelin ranny 23 VIII, ekranowe komunikaty o sojusznikach. To nie dowodzi późniejszego zgonu ani pełnego przebiegu wojny.
3. **KOREKTA_AUTORA:** historia Dietricha i Konrada, ślub 3 I, zasady charakterów i języka opowieści. Takie potwierdzenia nie są surowymi danymi Jomini.
4. **WNIOSEK / NIEUSTALONE:** szczegóły działań, motywacja sojuszników, wyniki bitew bez zweryfikowanego pola, wyniki oblężeń i wzajemne reakcje ludzi.

**Kolejność źródeł dla bieżącego stanu:** zweryfikowany save z datą gry > starszy save w jego własnej dacie; ekran zachowuje pierwszeństwo jako świadectwo tego, co naprawdę wyświetlił w jego dniu, ale **nie zastępuje nowszej migawki**. Pozostawić widoczne różnice pól, nie wygładzać ich literacko.

[Oś fabuły](../../01_KAMPANIA/os_fabuly.md) · [Kanon](../../01_KAMPANIA/stan_aktualny.md) · [Indeks źródeł](../../06_MATERIALY_ZRODLOWE/indeks_saveow.md) · [Rejestr wojsk i ekranów](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/wojna_szwabska_1067_lipiec_listopad.md)
