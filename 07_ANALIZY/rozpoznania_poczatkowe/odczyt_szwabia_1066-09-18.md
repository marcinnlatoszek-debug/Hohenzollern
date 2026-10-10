# Szwabia — rozszerzenie kart postaci, zapis 1066-09-18

## Techniczna metryka
- Save: `von_Hohenzollern.ck3`; SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; CK3 1.20.0.4; ZIP / binarny `gamestate` 73 103 324 B.
- Pole czasu `0x3157` = 53144400 => data gry **1066-09-18** (poprzednio 53144352 = 1066-09-16; jednostki 24/dobę). Nowy zapis różni się od poprzedniego SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.
- 17 024 158 leksemów Jomini sprawdzonych składniowo, poprawna równowaga klamer. **Skan składni to nie odszyfrowanie wszystkich kluczy.**
- Rzeczywiste powiązanie: `0xdc` (klucz tytułu), `0x27d7` (posiadacz), `0x2755` (imię w rekordzie postaci), `0x2e5e` (ID domu — identyfikacja na podstawie wcześniejszej analizy).

## Osoby (imię i posiadanie potwierdzone)
| ID | Osoba | Tytuły | Surowy ID domu | Surowe liczby pola 0x29a5 | Surowe pole 0x27e9 |
|---:|---|---|---:|---|---:|
| 33226 | Rudolf | `d_swabia 1216; c_ulm 1217` | 4224 | [7,6,4,8,3,3] | 52787760 |
| 32172 | Friedrich | `c_grunningen 1222` | 4221 | [6,5,6,7,10,8] | 52735200 |
| 34995 | Kuno | `c_wurttemberg 1227` | 4220 | [10,2,5,10,8,5] | 52866600 |
| 31865 | Berthold | `c_baden 1231` | 10607 | [7,5,8,4,9,7] | 52726440 |
| 37502 | Egino | `c_zollern 1235; b_zollern 1236` | 4228 | [5,10,7,4,9,4] | 52954200 |
| 62634 | Burkhard | `c_hohenberg 1239; b_hohenberg 1240` | 12843 | [3,5,4,5,0,8] | 53002968 |
| 31271 | Eberhard | `c_furstenberg 1242` | 4138 | [6,2,5,5,0,7] | 52691400 |
| 45250 | Ezzo | `b_helfenstein 1220` | 12154 | [3,10,4,5,1,10] | 53002848 |
| 45251 | Ekbert | `b_sigmaringen 1224` | NIEUSTALONE | [4,10,5,10,6,10] | 52932048 |
| 45252 | Friedrich | `b_tubingen 1229` | NIEUSTALONE | [2,7,7,1,0,5] | 52831848 |
| 45253 | Bernhard | `b_reutlingen 1238` | NIEUSTALONE | [5,7,6,4,7,7] | 52844808 |
| 45254 | Konrad | `b_rottweil 1241` | NIEUSTALONE | [6,0,8,9,3,6] | 52932048 |

## Fakty i niewiadome
- **POTWIERDZONE_SAVE:** siedem hrabstw w strukturze `d_swabia` 1216, 12 rozpoznanych osób będących posiadaczami tytułów, ich zapisane imiona i ID. Rudolf 33226 utrzymuje księstwo oraz Ulm, Burkhard 62634 — Hohenberg.
- **WNIOSEK:** pole `0x27e9` prawdopodobnie oznacza datę urodzenia, jednak pełne potwierdzenie semantyki tego kodu wymaga słownika. Sześciu liczb pola `0x29a5` nie przypisano automatycznie do nazw statystyk.
- **NIEUSTALONE:** realne traits, edukacja, kultura, wiara/obrządek, stan zdrowia, rodzina, małżonkowie/dzieci, urzędy, przynależność dworska, sojusze i relacje osobiste, portrety. Żaden władca nie jest automatycznie członkiem dworu Burkharda tylko z powodu położenia tytułu.
- **Do zdobycia:** datowany screen pełnej karty każdej osoby, Family/Relations, tooltipy traits, panel Council księcia, listy dworów i rycerzy oraz referencje Barber Shop; opisy wyglądu tylko z zatwierdzonych portretów.

[Indeks postaci](../../02_POSTACIE/indeks_postaci.md) · [Księstwo Szwabii](../../03_TERYTORIA/KSIESTWA/1216/karta.md) · [Indeks save'ów](../../06_MATERIALY_ZRODLOWE/indeks_saveow.md)
