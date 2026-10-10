# Welf — CK3 ID 34799

## Uzupełnienie dokumentacji ekranowej — Welf IV, hrabia Ravensburga

**POTWIERDZONE_SCREEN:** `Zrzut ekranu 2026-10-10 211100.png` (załącznik `file_00000000a3f481f4aa508936abd55e57`) i portret `Barbershop_Count_Burkhard_of_Hohenberg_1066_10_20_0006.png` (załącznik `file_00000000b7448210979cd5eb08e8d127`). Screen przedstawia **Count Welf IV of Ravensburg**, wiek **31 lat**, dom **Welf**, status **Fellow Vassal**, profil interfejsu **Irrational Zealot**. Zgodność z własnym rekordem `living/34799`, `c_ravensburg`, wiekiem i rodem potwierdza przypisanie. **20 X 1066** to data z nazwy eksportu, nie z zegara gry.

- **POTWIERDZONE_SAVE (18 IX 1066):** `lustful`, `arrogant`, `zealous`, `education_martial_3`, `open_terrain_expert`, `disinherited`. Profil **Irrational Zealot** jest opisem zbiorczym, nie nowym traitem.
- **POTWIERDZONE_SCREEN:** kultura **Bavarian**, obrządek **Roman Rite**, `County of Ravensburg`, `Feudal Realm Vassal`. Umiejętności końcowe DIP/MAR/STE/INT/LEA/PRO **6/14/7/12/5/8**, w starszym zapisie bazowe `[5,4,5,8,4,8]`.
- **Panel zasobów z ekranu:** złoto **62**, prestiż **750**, pobożność **301**, wojska **262**, licznik zbrojnych **1/5**, tytuły **1**, roszczenia **4**, `Family 7`, `Courtiers 7`, `Subjects 0`, `Children (0)`, `Siblings (2)`. Dane nie są automatycznie stanem save 18 IX.
- **Rodzina:** na ekranie widoczna małżonka i miniatura `Primary Heir`; bez rozwinięcia kart nie wyznaczono ID z samych miniatur. Save 18 IX zawiera `primary_spouse=38657`. Posiadanie `disinherited` nie jest sprzeczne z wyświetlanym dziedzicem.
- **Opinie i wskaźniki:** widoczne przy portretach −37, −72, −76, −26, −100 i −56; bez właściwych tooltipów nie nadawać im nieudowodnionych znaczeń, nie tworzyć z nich zdarzeń.
- **Dodatkowe materiały:** [opis wyglądu](wyglad.md), [charakter i interpretacja](profil_narracyjny.md), [źródła ekranowe](zrodla.md), [indeks screenów](../../06_MATERIALY_ZRODLOWE/indeks_screenow.md). Oryginalne PNG są załącznikami rozmowy, **nie** kopią w GitHubie.

**Nota chronologiczna:** historyczny dopisek „wygląd NIEUSTALONY” poniżej dotyczy momentu sprzed otrzymania portretu. Nie usuwać starszej obserwacji, lecz czytać z datą jej źródła.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/34799`; imię `Welf`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1035.1.1`.

**OBLICZONE:** wiek **31** na 18 IX 1066, z daty urodzenia.

- Dom: ID **10543**, nazwa/klucz `house_welf`; dynastia ID **1626**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `41`, `culture_template=bavarian`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[5, 4, 5, 8, 4, 8]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `lustful` [indeks 47], `arrogant` [indeks 59], `zealous` [indeks 72], `education_martial_3` [indeks 17], `open_terrain_expert` [indeks 249], `disinherited` [indeks 230].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `c_ravensburg 997` — nazwa zapisana: Ravensburg; `b_ravensburg 998` — nazwa zapisana: Ravensburg.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Kontrakt **8642**: wasal [Welf 34799](../34799/karta.md) → senior [Rudolf 33226](../33226/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Lista `playable_data/knights`: ID 56430 — własny rekord poza zakresem, ID 56428 — własny rekord poza zakresem, ID 56429 — własny rekord poza zakresem.
- Pierwsze wpisy `landed_data/succession`: ID 39214 — własny rekord poza zakresem, ID 40060 — własny rekord poza zakresem, [Alberto-Azzo 30351](../30351/karta.md), ID 39215 — własny rekord poza zakresem, ID 39572 — własny rekord poza zakresem, ID 40059 — własny rekord poza zakresem, ID 39218 — własny rekord poza zakresem, ID 39068 — własny rekord poza zakresem. Łącznie 46 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=60`, `income=1.65825`; `current_strength=272`, `strength=272`, `levy=169`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice rozpoznani przez odwrotne powiązanie `family_data/child` w rejestrach żywych i zmarłych: ID 32223 — własny rekord poza zakresem, [Alberto-Azzo 30351](../30351/karta.md). Nie zgadywano drugiego rodzica przy jednym wpisie.
- `primary_spouse`: ID 38657 — własny rekord poza zakresem. Pole zachowuje się także w niektórych rekordach zmarłych; nie oznacza trwającego dziś małżeństwa osoby zmarłej.
- Wszystkie powtarzane wpisy `spouse` (mogą obejmować zmarłych): ID 38657 — własny rekord poza zakresem.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)
