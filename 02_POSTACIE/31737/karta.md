# Louis — CK3 ID 31737

## Nowa obserwacja wizualna i ekranowa — Louis, hrabia Sundgau

**POTWIERDZONE_SCREEN:** `Zrzut ekranu 2026-10-10 211801.png` (załącznik `file_00000000214c8210b7606b0216db9598`) i portret `Barbershop_Count_Burkhard_of_Hohenberg_1066_10_20_0008.png` (załącznik `file_00000000d7bc8210b3e64dba953ef4dc`). Postać na obu obrazach to **Count Louis of Sundgau**, wiek **47**, dom **Scarponnois**; zgodna tożsamość z rekordem CK3 **31737**. „Burkhard” w nazwie pliku portretu to kontekst kampanii, nie tożsamość przedstawionego hrabiego. Data **20 X 1066** pochodzi z nazwy eksportu, nie z widocznego zegara gry.

- **POTWIERDZONE_SAVE, stan 18 IX 1066:** `compassionate`, `just`, `humble`, `education_stewardship_1`, `architect`; wartości bazowe DIP/MAR/STE/INT/LEA/PRO = **[8,5,5,6,0,2]**.
- **POTWIERDZONE_SCREEN:** zbiorczy profil **Gracious Paragon** — nie jest dodatkowym traitem. Umiejętności efektywne z karty **12/5/17/0/2/2**. Kultura **French**, obrządek **Roman Rite**, `County of Sundgau`, `Feudal Realm Vassal`.
- **Urząd — rozbieżność chronologiczna:** nowsza karta określa Louisa jako **Duke Rudolf’s Chancellor**, podczas gdy potwierdzony save z **18 IX 1066** i [rejestr rad](../../04_OTOCZENIE_WLADCY/rada.md) wskazują na tym stanowisku [Kuno 34995](../34995/karta.md). Zmiany personalnej nie należy datować na wrzesień ani wymyślać przyczyny bez dowodu. Nie nadpisano starszej obsady rady.
- **Zasoby na ekranie:** złoto **71**, prestiż **479**, pobożność **401**, siły **372**, licznik **1/5**, tytuły **1**, **Family 11**, **Children 6**, **Siblings 1**, **Courtiers 8**, **Subjects 1**. Są to liczby późniejszej obserwacji, a nie nadpisanie save 18 IX.
- **Rodzina:** na karcie jest widoczna małżonka; w save `primary_spouse=31579`, [Sophia](../31579/karta.md). Sześcioro dzieci zapisanych w save ma ID **36154**, **36741**, **36942**, **37344**, **37604**, **37773**; zgodność licznika dzieci nie identyfikuje automatycznie miniaturowych portretów. Prawy panel zawiera `Primary Heir` z miniaturą, identyfikacji tej twarzy nie dokonano.
- **Relacje:** ekran pokazuje czerwone wskaźniki przy seniorze, małżonce i innych portretach; ich dokładne znaczenie i stronę opinii należy sprawdzać tooltipami. Nie wnioskować ze wskaźników o spisku, wojnie czy zgodzie rodzinnej.

**Dokumentacja dodatkowa:** [wygląd i ubiór](wyglad.md), [profil narracyjny](profil_narracyjny.md), [źródła i identyfikatory](zrodla.md), [indeks screenów](../../06_MATERIALY_ZRODLOWE/indeks_screenow.md). Wcześniejsze stwierdzenia w tej karcie o „wyglądzie NIEUSTALONYM” pochodzą ze stanu sprzed tego uzupełnienia; oryginalne PNG pozostały załącznikami rozmowy.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/31737`; imię `Louis`; płeć: mężczyzna (brak female=yes w rekordzie). Urodzenie: `1019.1.1`.

**OBLICZONE:** wiek **47** na 18 IX 1066, z daty urodzenia.

- Dom: ID **1447**, nazwa/klucz `dynn_Scarponnois`; dynastia ID **1447**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `72`, `culture_template=french`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[8, 5, 5, 6, 0, 2]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `compassionate` [indeks 75], `just` [indeks 70], `humble` [indeks 60], `education_stewardship_1` [indeks 10], `architect` [indeks 34].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): `c_sundgau 1211` — nazwa zapisana: Sundgau; `b_montbelliard 1212` — nazwa zapisana: Montbéliard; `b_porrentruy 1215` — nazwa zapisana: Porrentruy.
- Ustrój: `feudal_government`; prawa `landed_data/laws`: `crown_authority_0`, `partition_succession_law`, `male_preference_law`.
- Kontrakt **8257**: wasal [Louis 31737](../31737/karta.md) → senior [Rudolf 33226](../33226/karta.md), grupa `feudal_vassal`. Dokładne pola w [transkrypcji politycznej](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/polityka_1066-09-18.json).
- Lista `playable_data/knights`: ID 37604 — własny rekord poza zakresem, ID 45249 — własny rekord poza zakresem.
- Pierwsze wpisy `landed_data/succession`: ID 37344 — własny rekord poza zakresem, ID 37604 — własny rekord poza zakresem, ID 37773 — własny rekord poza zakresem, [Beatrice 36154](../36154/karta.md), ID 36741 — własny rekord poza zakresem, ID 36942 — własny rekord poza zakresem. Łącznie 6 wpisów; nie oznaczają jednoczesnych odbiorców wszystkich tytułów. Sukcesję konkretnego tytułu sprawdzać osobno.
- Surowe zasoby: `gold/value=69`, `income=1.87625`; `current_strength=380`, `strength=380`, `levy=178`. Parametry migawki; nie ustalono ich pełnego przeliczenia na siłę koalicji ani wynik wojny.

## Rodzina — zapisane relacje

- Rodzice rozpoznani przez odwrotne powiązanie `family_data/child` w rejestrach żywych i zmarłych: ID 28415 — własny rekord poza zakresem, ID 27748 — własny rekord poza zakresem. Nie zgadywano drugiego rodzica przy jednym wpisie.
- `primary_spouse`: [Sophia 31579](../31579/karta.md). Pole zachowuje się także w niektórych rekordach zmarłych; nie oznacza trwającego dziś małżeństwa osoby zmarłej.
- Wszystkie powtarzane wpisy `spouse` (mogą obejmować zmarłych): [Sophia 31579](../31579/karta.md).
- `child`: [Beatrice 36154](../36154/karta.md), ID 36741 — własny rekord poza zakresem, ID 36942 — własny rekord poza zakresem, ID 37344 — własny rekord poza zakresem, ID 37604 — własny rekord poza zakresem, ID 37773 — własny rekord poza zakresem.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)
