# Kanon nowej kampanii Hohenzollern — stan aktualny

**Ostatni potwierdzony stan gry:** **1066-09-18**.
**Źródło aktualne:** `von_Hohenzollern(1).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`, CK3 1.20.0.4.
**Źródło poprzednie:** `von_Hohenzollern.ck3`, SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`, stan **1066-09-16**.
**Zasada:** późniejszy zapis jest źródłem bieżącego stanu; starszy pozostaje świadectwem historii. Nie łączyć statystyk z obu dni w jeden stan bez weryfikacji.

## Gracz i jego domena — 18 IX 1066
- [Burkhard, CK3 ID 62634](../02_POSTACIE/62634/karta.md), dom von Hohenzollern ID **12843**.
- Hrabstwo **Hohenberg**, `c_hohenberg` **1239**, oraz baronia `b_hohenberg` **1240** — osobista domena `[1239,1240]` ([karta Hohenbergu](../03_TERYTORIA/HRABSTWA/1239/karta.md)).
- Ustrój: `feudal_government`. Prawa w `landed_data`: `crown_authority_0`, `confederate_partition_succession_law`, `male_preference_law`.
- Imię, numer, data urodzenia i traity zweryfikowane z tablicy `traits_lookup` w obu save'ach, szczegóły w karcie. Pole `skill` ma sześć wartości `[3,5,4,5,0,8]` — **bazowe zapisane statystyki**, które mogą różnić się od statystyk w panelu po uwzględnieniu modyfikatorów.

## Aktualna rada — 18 IX 1066
| Urząd | Postać ID |
|---|---|
| Kanclerz | [Ezzo 65691](../02_POSTACIE/65691/karta.md) |
| Zarządca | [Konrad 45254](../02_POSTACIE/45254/karta.md) |
| Marszałek | [Gerhard 62635](../02_POSTACIE/62635/karta.md) |
| Mistrz intryg | [Gunzelin 65692](../02_POSTACIE/65692/karta.md) |
| Duchowny | [Helferich 58415](../02_POSTACIE/58415/karta.md) |

[Pełne porównanie obsady między 16 a 18 września](../04_OTOCZENIE_WLADCY/rada.md). W pierwszym zapisie Notker prowadził sprawy zagraniczne; Gerhard podatki; zadanie organizowania wojsk nie miało wpisanego wykonawcy; Konrad działał przy rozbijaniu spisków; Helferich zajmował się stosunkami religijnymi.

## Rycerze i dwór
Pole `playable_data/knights` jest reprezentowane w obu save'ach przez ID **62635** (Gerhard) i **65692** (Gunzelin). Wniosek o nazwie pola wsparty zewnętrznym schematem CK3; do weryfikacji interfejsem. **Pełny dwór, rodzina, inne urzędy, goście i relacje NIEUSTALONE.**
[Indeks dworu — obserwacja 16 IX](../04_OTOCZENIE_WLADCY/indeks_dworu.md).

## Region
- Książę [Rudolf ID 33226](../02_POSTACIE/33226/karta.md), posiadacz [`d_swabia` 1216](../03_TERYTORIA/KSIESTWA/1216/karta.md).
- Siedem rozpoznanych hrabstw w strukturze księstwa, wykaz w [indeksie terytoriów](../03_TERYTORIA/indeks_terytoriow.md).
- 23 tytuły baronii rozpoznane w [indeksie baronii Szwabii](../03_TERYTORIA/indeks_baronii_szwabii.md). Ich wykaz pochodzi z 16 IX, nie należy automatycznie uznawać wszystkich posiadaczy za ponownie zweryfikowanych na 18 IX.
- „Holten” jako nazwa robocza wymaga identyfikacji w panelu gry; NIE utożsamiać jej samodzielnie z Zollern.

## Wiarygodność danych
**POTWIERDZONE_SAVE:** odczyt wartości i nazw z binarnych rekordów, powiązania ID, daty 16 oraz 18 września, aktualny skład zadań rady.
**WNIOSEK oparty na strukturze/schemacie:** interpretacja wybranych bezimiennych kluczy binarnych (np. `knights`), zanim zostaną porównane z aktualnym interfejsem.
**NIEUSTALONE:** rodzina i pełny dwór, efektywne wartości po modyfikatorach, pełna lista aktywnych modów i ich znaczeń oraz wygląd postaci. Screenshoty przypisywać do kart poprzez ID i datę stanu.

## Dokumenty
- [Indeks postaci](../02_POSTACIE/indeks_postaci.md)
- [Rada — chronologia](../04_OTOCZENIE_WLADCY/rada.md)
- [Raport techniczny 16 IX](../07_ANALIZY/rozpoznania_poczatkowe/odczyt_ck3_2026-10-10.md)
- [Raport z 18 IX](../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)
- [Cechy i umiejętności — 17 postaci, 18 IX](../07_ANALIZY/rozpoznania_poczatkowe/traits_i_umiejetnosci_1066-09-18.md)
- [Rejestr obu save'ów](../06_MATERIALY_ZRODLOWE/indeks_saveow.md)

## Uzupełnienie kanonu — potwierdzenie gracza 10 X 2026

Rozpoznane 15 modów przyjęto jako zweryfikowane: [aktualny katalog](../zrodla/Mody.md). Save zawiera 20 wpisów; pięć nazw nadal NIEUSTALONYCH. Historyczny plan konfiguracji nie zastępuje potwierdzenia dotyczącego bieżącej kampanii. Nazwa (2) to identyczny hash aktualnego save'a z 18 IX.

Rozpoznanie obejmuje 20 osób z imienia i 30 dodatkowych kart ID. [Rozszerzenie polityczne i rodziny](../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md). Łańcuch faktycznej władzy: Burkhard/Hohenberg → Rudolf/Szwabia → Heinrich/Cesarstwo. Rudolf jest wskazanym następcą Burkharda przy fallback_default. Stan tytułu i wynik sukcesji nie są prognozą przyszłego wydarzenia.

Wcześniejsze NIEUSTALONE dotyczące rodziny zastępują w zakresie wskazanych ID datowane rejestry relacji władców; imiona i własne rekordy 30 krewnych nadal nieodczytane. Dwór Burkharda: potwierdzeni employer=62634 Ezzo 65691, Gunzelin 65692, Helferich 58415, Gerhard 62635, Notker 62636, Amalie 62637, Emma 62638. Nie jest to twierdzenie o kompletności gości i wszystkich relacji.
