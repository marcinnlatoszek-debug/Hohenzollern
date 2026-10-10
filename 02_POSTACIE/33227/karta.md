# Otto — CK3 ID 33227

## Obserwacja ekranowa — Otto III von Kirchberg, hrabia Burgau

**POTWIERDZONE_SCREEN:** `Zrzut ekranu 2026-10-10 210756.png` (załącznik `file_00000000d51c820a8391999bb9013cc3`), portret `Barbershop_Count_Burkhard_of_Hohenberg_1066_10_20_0005.png` (załącznik `file_00000000e80081f4830bc68815405af4`). Na karcie widnieje **Count Otto III of Burgau**, 40 lat, dom **Kirchberg**, `Fellow Vassal`. Data **20 X 1066** pochodzi z nazwy eksportu Barbershop, nie z datownika gry. Powiązanie z ID **33227** ustalono na podstawie imienia, wieku, tytułu i rodu.

- **POTWIERDZONE_SAVE 18 IX:** `stubborn`, `gregarious`, `arbitrary`, `education_stewardship_1`; bazowe umiejętności `[7,3,8,10,0,8]`.
- **POTWIERDZONE_SCREEN:** profil zbiorczy **Knave** (nie nowy trait); końcowe umiejętności DIP/MAR/STE/INT/LEA/PRO: **9/3/15/12/0/8**; kultura **Swabian**, obrządek **Roman Rite**.
- **Zasoby i otoczenie ekranowe:** złoto **70**, prestiż **750**, pobożność **100**, wojsko **364**, licznik **1/5**, 1 tytuł, Family **2**, Children **2**, Courtiers **7**, Subjects **0**, Siblings **0**. Nie przepisywać wstecz do save 18 IX.
- **Rodzina:** zapis 18 IX zawiera dzieci ID **37887** i **38615**; miniaturowe portrety i `Primary Heir` nie pozwalają samodzielnie nadać tym twarzom identyfikatorów.
- **Wartości relacyjne:** przy postaci wyświetla się **−26**, a przy seniorze także czerwone **−100** z dodatkową ikoną. Ich konkretne znaczenie wymaga tooltipu; nie jest dowodem spisku ani wrogości.

**Nowe materiały:** [wygląd](wyglad.md), [profil do narracji](profil_narracyjny.md), [źródła screenów](zrodla.md), [indeks screenów](../../06_MATERIALY_ZRODLOWE/indeks_screenow.md). Wcześniejsze „brak portretu” odnosi się do starszego etapu rozpoznania; binarnych PNG nie przesłano do repozytorium.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/33227`; imię `Otto`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1026.1.1`.

**OBLICZONE:** wiek **40** na 18 IX 1066, z daty urodzenia.

- Dom: ID **4236**, nazwa/klucz `dynn_Kirchberg`; dynastia ID **4236**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `40`, `culture_template=swabian`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[7, 3, 8, 10, 0, 8]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `stubborn` [indeks 78], `gregarious` [indeks 66], `arbitrary` [indeks 69], `education_stewardship_1` [indeks 10].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `c_burgau 1000` — nazwa zapisana: Burgau; `b_burgau 1001` — nazwa zapisana: Burgau; `b_kirchberg 1002` — nazwa zapisana: Kirchenberg.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Kontrakt **9749**: wasal [Otto 33227](../33227/karta.md) → senior [Rudolf 33226](../33226/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Lista `playable_data/knights`: ID 38615 — własny rekord poza zakresem.
- Pierwsze wpisy `landed_data/succession`: ID 37887 — własny rekord poza zakresem, ID 38615 — własny rekord poza zakresem. Łącznie 2 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=68`, `income=1.881`; `current_strength=377`, `strength=377`, `levy=176`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice: nie znaleziono powiązania z wybranym ID w odczytanych tablicach dzieci; genealogii nie dopowiedziano.
- `child`: ID 37887 — własny rekord poza zakresem, ID 38615 — własny rekord poza zakresem.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)
