# Ezzo — CK3 ID 45250

**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/45250`; imię `Ezzo`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1050.7.22`.

**OBLICZONE:** wiek **16** na 18 IX 1066, z daty urodzenia.

- Dom: ID **12154**, nazwa/klucz `dynn_Lichtenberg`; dynastia ID **11550**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `40`, `culture_template=swabian`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[3, 10, 4, 5, 1, 10]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `shy` [indeks 65], `stubborn` [indeks 78], `forgiving` [indeks 82], `education_learning_3` [indeks 22], `beauty_good_1` [indeks 145].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `b_helfenstein 1220` — nazwa zapisana: Helfenstein.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Kontrakt **16787023**: wasal [Ezzo 45250](../45250/karta.md) → senior [Rudolf 33226](../33226/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Pierwsze wpisy `landed_data/succession`: [Rudolf 33226](../33226/karta.md). Łącznie 1 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=14.3744`, `income=0.416`; `current_strength=142`, `strength=142`, `levy=142`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice: nie znaleziono powiązania z wybranym ID w odczytanych tablicach dzieci; genealogii nie dopowiedziano.
- Brak własnych wpisów `family_data`; nie dowodzi stanu wolnego ani bezdzietności.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)

<details>
<summary>Wcześniejsze obserwacje i etap rozpoznania — zachowane historycznie</summary>

# Ezzo — CK3 ID 45250

**Status:** pierwsze rozpoznanie 1066-09-18; wyłącznie fakty odczytane z nowego zapisu. Pozostałe pola: NIEUSTALONE.

## Tożsamość, tytuły i relacje
Potwierdzony numer postaci, imię i tytuł. Nie przypisywać tej osoby do rodziny, rady lub dworu Burkharda bez odrębnego dowodu.

## Cechy, rodzina, portret i wydarzenia
NIEUSTALONE. Brak zatwierdzonego portretu.

## Obserwacja aktualizacyjna — 1066-09-18
**Źródło:** `von_Hohenzollern.ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941` (wersja 1.20.0.4). Wcześniejszy stan z 1066-09-16 pozostaje historycznym źródłem.

**POTWIERDZONE_SAVE:** Rekord ID **45250**, imię **Ezzo**; właściciel tytułu w rekordach: `b_helfenstein 1220`. Surowy ID domu w polu `0x2e5e`: **12154**. Pole datowe `0x27e9`: **53002848** (znaczenie biograficzne NIEUSTALONE). Surowe liczby z `0x29a5`: **[3,10,4,5,1,10]** (niezweryfikowana kolejność umiejętności).

**NIEUSTALONE:** dokładna data urodzenia, rodzice, małżeństwa, dzieci, kultura, wiara, obrządek, przyporządkowanie umiejętności, cechy/traits, urzędy, relacje, roszczenia i wygląd. Potrzebne: aktualny screen karty postaci, Family/Relations, tooltipy cech i osobna referencja Barber Shop. Tytuł nie dowodzi przebywania na dworze Burkharda.

## Nowy odczyt cech z 18 IX 1066

Źródło: `von_Hohenzollern(1).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`. Każdy trait wynika z tablicy numerycznej postaci połączonej z 419-elementowym słownikiem `traits_lookup` **tego samego save'a**.
- Data urodzenia ze struktury Jomini: **1050-07-22**.
- ID kultury: **40** (nazwa NIEUSTALONA); ID domu dynastycznego: **12154**.
- Sześć bazowych zapisanych wartości `skill` w kolejności dyplomacja, wojskowość, zarządzanie, intryga, nauka, sprawność: **3 / 10 / 4 / 5 / 1 / 10**.
- Rozszyfrowane cechy: `shy` [65], `stubborn` [78], `forgiving` [82], `education_learning_3` [22], `beauty_good_1` [145].
- Efektywne wartości po modyfikatorach, szczegóły religii i portret: **NIEUSTALONE**.
- Kontrola tożsamości: ID **45250**; szczególnie nie utożsamiać Ezzo **65691** (kanclerz 18 IX) z Ezzo **45250** (baron Helfensteinu).

</details>
