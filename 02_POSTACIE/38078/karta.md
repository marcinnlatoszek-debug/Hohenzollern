# Hermann — CK3 ID 38078

## Wojna o Szwabię — 1067

**POTWIERDZONE_SAVE (7 VI 1067):** roszczenie Hermanna do `d_swabia` jest przedmiotem wojny `claim_cb` rozpoczętej **28 IV 1067** przez jego ojca Bertholda 31865 przeciw Rudolfowi 33226. W stanie 7 VI Hermann figuruje jako `claimant`, bez własnego wpisu uczestnika w odczytanym wykazie.

**POTWIERDZONE_SCREEN (1 VII 1067):** powiadomienie datowane **26 VI** `Enemy Ally Joins War: Count Hermann` stwierdza, że hrabia Hermann dołączył do strony wrogiej graczowi. Ta data **nie jest datą rozpoczęcia wojny ani nabycia roszczenia**; nie dowodzi też, gdzie osobiście przebywał podczas walk.

[Źródła wojny i chronologii](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/wojna_szwabska_1067_lipiec_listopad.md).


## Potwierdzenie — 7 VI 1067

**POTWIERDZONE_SAVE:** `von_Hohenzollern(10).ck3`, SHA-256 `07c6a99a994f118ea5e9aa469f2493a7d767bc608d81a2092b4acab8197922d4`, CK3 1.20.0.4, **7 VI 1067**. Claimant w wojnie 36 Bertholda przeciw Rudolfowi o Szwabię, rozpoczętej 28 IV 1067. Berthold 31865 ma go w family_data/child. Wykaz uczestników ataku wskazuje Bertholda; nie utożsamiać roli roszczącego z osobnym zapisanym uczestnikiem lub dowódcą. [Raport](../../07_ANALIZY/rozpoznania_poczatkowe/zmiany_1067-01-29_do_1067-06-07.md).


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/38078`; imię `Hermann`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1048.1.1`.

**OBLICZONE:** wiek **18** na 18 IX 1066, z daty urodzenia.

- Dom: ID **10607**, nazwa/klucz `house_zahringen`; dynastia ID **4225**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `NIEUSTALONE / brak pola`, `culture_template=NIEUSTALONE / brak pola`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[7, 8, 6, 4, 3, 10]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `gluttonous` [indeks 49], `arbitrary` [indeks 69], `diligent` [indeks 54], `education_martial_2` [indeks 16], `forder` [indeks 242].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `c_breisgau 1203` — nazwa zapisana: Breisgau; `b_freiburg 1204` — nazwa zapisana: Freiburg; `b_sankt_blasien 1205` — nazwa zapisana: Sankt Blasien.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Kontrakt **9066**: wasal [Hermann 38078](../38078/karta.md) → senior [Berthold 31865](../31865/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Zarządca u [Berthold 31865](../31865/karta.md); zadanie **7949**, `task_collect_taxes`; potwierdzenie w `council_task_manager/database`.
- Lista `playable_data/knights`: ID 53112 — własny rekord poza zakresem, ID 32841 — własny rekord poza zakresem, ID 53115 — własny rekord poza zakresem.
- Pierwsze wpisy `landed_data/succession`: [Berthold 38608](../38608/karta.md), [Gebhard 38908](../38908/karta.md), [Luitgard 38251](../38251/karta.md), [Richinza 39172](../39172/karta.md), [Berthold 31865](../31865/karta.md), ID 33048 — własny rekord poza zakresem, ID 40317 — własny rekord poza zakresem, ID 41033 — własny rekord poza zakresem. Łącznie 110 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=94.36276`, `income=2.659`; `current_strength=472`, `strength=472`, `levy=269`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice rozpoznani przez odwrotne powiązanie `family_data/child` w rejestrach żywych i zmarłych: [Richwara 34471](../34471/karta.md), [Berthold 31865](../31865/karta.md). Nie zgadywano drugiego rodzica przy jednym wpisie.
- `primary_spouse`: [Judith 37969](../37969/karta.md). Pole zachowuje się także w niektórych rekordach zmarłych; nie oznacza trwającego dziś małżeństwa osoby zmarłej.
- Wszystkie powtarzane wpisy `spouse` (mogą obejmować zmarłych): [Judith 37969](../37969/karta.md).

## Roszczenia

- `alive_data/claim/title`: `d_swabia 1216`; `pressed=NIEUSTALONE / brak pola`. Brak jawnego pressed=yes; nie dopowiedziano wartości domyślnej.
- `alive_data/claim/title`: `d_piedmonte 2311`; `pressed=NIEUSTALONE / brak pola`. Brak jawnego pressed=yes; nie dopowiedziano wartości domyślnej.
- `alive_data/claim/title`: `c_turin 2316`; `pressed=NIEUSTALONE / brak pola`. Brak jawnego pressed=yes; nie dopowiedziano wartości domyślnej.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)

Pierwotnie założono tę kartę jako odniesienie ID z rejestru rodzin. Własny rekord odczytano w obecnym rozszerzeniu; wcześniejsze oznaczenie wszystkich danych osobowych jako NIEUSTALONE zostało zastąpione powyższą obserwacją. [Pierwotna transkrypcja rodziny](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/rodziny_1066-09-18.md).

## Późniejsze uczestnictwo — 26 VI 1067

POTWIERDZONE_SCREEN: powiadomienie Enemy Ally Joins War: Count Hermann z datą 26 Jun, na ekranie 1 VII 1067. Hermann dołączył do strony przeciwnej; wcześniej na 7 VI był wskazany jako claimant. [Źródło](../../07_ANALIZY/rozpoznania_poczatkowe/zmiany_1067-01-29_do_1067-06-07.md). Nie ustalono, czy sam dowodzi armią Breisgau; jej tooltip wskazuje Ernsta.
