# Hupold — CK3 ID 30344

## Aktualizacja źródeł ekranowych — Hupold III, hrabia Nördlingen

**POTWIERDZONE_SCREEN:** `Zrzut ekranu 2026-10-10 210529.png` (załącznik `file_000000008aec8246976ec7a8f75b9532`), portret `Barbershop_Count_Burkhard_of_Hohenberg_1066_10_20_0004.png` (załącznik `file_00000000d12082468341a9de938635e7`). Oba przedstawiają **Count Hupold III of Nördlingen**, 57 lat, herb domu **Hupolding**. To ta sama postać co `living/30344` w bazowym save, potwierdzona imieniem, wiekiem, tytułem i urzędem u Rudolfa. Nazwa pliku Barber Shop zawiera Burkharda jako kontekst rozgrywki, nie przedstawioną postać.

**Data z nazwy eksportu Barber Shop:** 20 X 1066. Na samej karcie postaci datownik gry nie jest widoczny.

- **Urząd na ekranie:** `Duke Rudolf's Marshal`; hrabstwo Nördlingen; `Feudal Realm Vassal`. To sąsiednie otoczenie polityczne Burkharda, **nie** członek jego własnej rady.
- **POTWIERDZONE_SCREEN:** profil osobowości **Rational Villain**, odrębny od traitów. Cechy z save 18 IX: `sadistic`, `honest`, `just`, `education_martial_2`, `overseer`, `reaver`; nie zgadywano ich z ikon.
- **Kultura i obrządek z ekranu:** **Swabian**, **Roman Rite**. Kultura nie była wyraźnie zmapowana w istniejącym własnym rekordzie save.
- **Efektywne umiejętności ekranowe** DIP / MAR / STE / INT / LEA / PRO: **7 / 17 / 11 / 2 / 9 / 14**. Nie nadpisują bazowych umiejętności `[4,9,4,4,8,6]` w save 18 IX.
- **Liczby z panelu:** 74 złota, 900 prestiżu, 502 pobożności, 397 wojska, licznik 3/5, 1 tytuł, Family 4, Courtiers 7, Subjects 1, Children 2, Siblings 0; widoczna małżonka. Save 18 IX: `primary_spouse=33049`, potomstwo `37503` i `38612`. Z samego portretu nie ustalamy tożsamości małżonki ani kolejności dzieci.
- **Wskaźniki przy portretach:** widoczne −26 oraz −100 przy seniorze z dodatkową ikoną i −16 przy dziedzicu; bez tooltipów nie wyjaśniono dokładnej semantyki tych liczb.
- **Kolejność źródeł:** stan save 18 IX 1066, portret nazwany datą 20 X 1066; nie zakładać, że ekranowe liczby były prawdziwe już we wrześniu.

**Pakiet redakcyjny:** [wygląd](wyglad.md), [cechy i profil do narracji](profil_narracyjny.md), [ewidencja screenów](zrodla.md). Oryginalne PNG zachowano jako załączniki rozmowy, nie wgrano ich binarnie do repozytorium. Dawne określenie „wygląd NIEUSTALONY” poniżej dotyczy wcześniejszego etapu rozpoznania.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/30344`; imię `Hupold`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1009.1.1`.

**OBLICZONE:** wiek **57** na 18 IX 1066, z daty urodzenia.

- Dom: ID **10608**, nazwa/klucz `house_hupoldinger`; dynastia ID **4225**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `NIEUSTALONE / brak pola`, `culture_template=NIEUSTALONE / brak pola`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[4, 9, 4, 4, 8, 6]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `sadistic` [indeks 77], `honest` [indeks 62], `just` [indeks 70], `education_martial_2` [indeks 16], `overseer` [indeks 32], `reaver` [indeks 246].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `c_nordlingen 1157` — nazwa zapisana: Nördlingen; `b_nordlingen 1158` — nazwa zapisana: Nordlingen.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Kontrakt **7912**: wasal [Hupold 30344](../30344/karta.md) → senior [Rudolf 33226](../33226/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Marszałek u [Rudolf 33226](../33226/karta.md); zadanie **9880**, `task_organize_levies`; potwierdzenie w `council_task_manager/database`.
- Lista `playable_data/knights`: ID 45239 — własny rekord poza zakresem, ID 51253 — własny rekord poza zakresem.
- Pierwsze wpisy `landed_data/succession`: [Hartmann 37503](../37503/karta.md), ID 38612 — własny rekord poza zakresem, ID 37340 — własny rekord poza zakresem, ID 41347 — własny rekord poza zakresem, ID 38133 — własny rekord poza zakresem, ID 32893 — własny rekord poza zakresem, ID 37963 — własny rekord poza zakresem, ID 39675 — własny rekord poza zakresem. Łącznie 53 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=72`, `income=2.00508`; `current_strength=413`, `strength=413`, `levy=211`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice rozpoznani przez odwrotne powiązanie `family_data/child` w rejestrach żywych i zmarłych: ID 23800 — własny rekord poza zakresem. Nie zgadywano drugiego rodzica przy jednym wpisie.
- `primary_spouse`: ID 33049 — własny rekord poza zakresem. Pole zachowuje się także w niektórych rekordach zmarłych; nie oznacza trwającego dziś małżeństwa osoby zmarłej.
- Wszystkie powtarzane wpisy `spouse` (mogą obejmować zmarłych): ID 33049 — własny rekord poza zakresem.
- `child`: [Hartmann 37503](../37503/karta.md), ID 38612 — własny rekord poza zakresem.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)
