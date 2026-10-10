# Hartmann — CK3 ID 37503

## Uzupełnienie ekranowe — Hartmann z Zurychu, 20 X 1066 według nazwy portretu

**POTWIERDZONE_SCREEN:** `Zrzut ekranu 2026-10-10 211516.png` (załącznik `file_00000000c1e081f48259db0f193b5552`) i `Barbershop_Count_Burkhard_of_Hohenberg_1066_10_20_0007.png` (załącznik `file_00000000afc08210a13a127293868a59`). Przedstawiony w obu plikach jest **Count Hartmann of Zürich**, lat **21**, dom **Hupolding**. Zgodność imienia, wieku, tytułu, domu i twarzy pozwala przypisać obrazy do istniejącego **CK3 ID 37503**, nie do Burkharda. Data 20 X 1066 pochodzi z nazwy eksportu, nie z widocznego kalendarza gry.

- **POTWIERDZONE_SAVE, stan 18 IX 1066:** `deceitful`, `shy`, `diligent`, `education_diplomacy_2`; bazowy `skill=[4,5,8,6,10,9]`.
- **POTWIERDZONE_SCREEN:** zbiorczy profil **Knave**, oddzielny od indywidualnych traitów; wartości efektywne DIP / MAR / STE / INT / LEA / PRO = **10 / 7 / 13 / 9 / 14 / 9**. Kultura **Swabian**, obrządek **Roman Rite**. Status polityczny **Fellow Vassal**, **County of Zürich**, **Feudal Realm Vassal**.
- **Zasoby i panel:** złoto **72**, prestiż **354**, pobożność **51**, wojsko **273**, jednostki **1/5**, tytuły **1**, **1 Claim**, **Family 4**, **Courtiers 7**, **Subjects 1**, **Children 0**, **Siblings 1**. Liczby należą do czasu obserwacji na ekranie, nie aktualizują wstecz save’a.
- **Rozbieżność datowana:** save 18 IX nie zawierał odczytanego własnego wpisu `alive_data/claim`, natomiast screen pokazuje **1 Claim**. Cel roszczenia i przyczyna zmiany NIEUSTALONE, nie dopisywać konkretnego tytułu.
- **Relacje:** ojciec [Hupold III 30344](../30344/karta.md) potwierdzony w save; drugi rodzic ID **33049**, małżonka w save `primary_spouse=38255`. Portret małżonki, rodzeństwa i `Primary Heir` na ekranie bez osobnych kart nie stanowi niezależnej identyfikacji. Wartości opinii **−16**, **−26**, **−100** wymagają tooltipów do interpretacji.

**Materiały redakcyjne:** [wzorzec wyglądu](wyglad.md), [profil psychologiczny do narracji](profil_narracyjny.md), [źródła i zastrzeżenia](zrodla.md), [indeks screenów](../../06_MATERIALY_ZRODLOWE/indeks_screenow.md).

**Status plików:** portret i zrzut pozostają binarnymi załącznikami rozmowy; do GitHuba zapisano ich nazwy, identyfikatory i opisy, nie obrazy.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/37503`; imię `Hartmann`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1045.1.1`.

**OBLICZONE:** wiek **21** na 18 IX 1066, z daty urodzenia.

- Dom: ID **10608**, nazwa/klucz `house_hupoldinger`; dynastia ID **4225**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `40`, `culture_template=swabian`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[4, 5, 8, 6, 10, 9]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `deceitful` [indeks 61], `shy` [indeks 65], `diligent` [indeks 54], `education_diplomacy_2` [indeks 6].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `c_zurich 1193` — nazwa zapisana: Zürich; `b_zurich 1194` — nazwa zapisana: Zürich; `b_basel 1197` — nazwa zapisana: Basel.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Kontrakt **9262**: wasal [Hartmann 37503](../37503/karta.md) → senior [Rudolf 33226](../33226/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Lista `playable_data/knights`: ID 45247 — własny rekord poza zakresem, ID 53575 — własny rekord poza zakresem.
- Pierwsze wpisy `landed_data/succession`: ID 38612 — własny rekord poza zakresem, [Hupold 30344](../30344/karta.md), ID 37340 — własny rekord poza zakresem, ID 41347 — własny rekord poza zakresem, ID 38133 — własny rekord poza zakresem, ID 32893 — własny rekord poza zakresem, ID 37963 — własny rekord poza zakresem, ID 39675 — własny rekord poza zakresem. Łącznie 53 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=70`, `income=1.9404`; `current_strength=287`, `strength=287`, `levy=185`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice rozpoznani przez odwrotne powiązanie `family_data/child` w rejestrach żywych i zmarłych: [Hupold 30344](../30344/karta.md), ID 33049 — własny rekord poza zakresem. Nie zgadywano drugiego rodzica przy jednym wpisie.
- `primary_spouse`: ID 38255 — własny rekord poza zakresem. Pole zachowuje się także w niektórych rekordach zmarłych; nie oznacza trwającego dziś małżeństwa osoby zmarłej.
- Wszystkie powtarzane wpisy `spouse` (mogą obejmować zmarłych): ID 38255 — własny rekord poza zakresem.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)
