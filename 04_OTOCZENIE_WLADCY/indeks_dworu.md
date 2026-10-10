# Dwór Burkharda — indeks bez zgadywania

**Data świata:** 1066-09-16 • **Postać gracza:** [Burkhard 62634](../02_POSTACIE/62634/karta.md).
Źródło: `von_Hohenzollern.ck3`, SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`.

## Dotąd potwierdzone
Tytuł hrabiego Hohenberg (1239), jego baronia (1240) oraz przynależność tytułu do struktury Szwabii (1216). Nie wynika z tego automatycznie lista jego dworzan.

## Rada — odczyt zadań (1066-09-16)

| Task ID | Zadanie zapisane w grze | Wskazany wykonawca | CK3 ID |
|---:|---|---|---:|
| 16782042 | `task_foreign_affairs` | [Notker](../02_POSTACIE/62636/karta.md) | 62636 |
| 16782043 | `task_collect_taxes` | [Gerhard](../02_POSTACIE/62635/karta.md) | 62635 |
| 16782044 | `task_organize_levies` | **NIEUSTALONE**: rekord bez ID wykonawcy | — |
| 16782045 | `task_disrupt_schemes` | [Konrad](../02_POSTACIE/45254/karta.md) | 45254 |
| 16782046 | `task_religious_relations` | [Helferich](../02_POSTACIE/58415/karta.md) | 58415 |

Rekordy zadań mają właściciela `0x299f=62634`, a dla wskazanych wykonawców pole `0x2812` lub `0x3457` z ID. Przekład na urzędy (kanclerz, zarządca, marszałek, mistrz intryg, duchowny) opiera się na nazwie wykonywanego zadania; dla `organize_levies` brak odczytanego wykonawcy nie dowodzi wakatu urzędu.

## Rycerze (odczyt powiązania z playable_data)
- [Gerhard ID 62635](../02_POSTACIE/62635/karta.md) — również wykonuje `task_collect_taxes`.
- [Gunzelin ID 65692](../02_POSTACIE/65692/karta.md).

Pole `0x30f2` w bloku Burkharda `playable_data` zawiera `[62635,65692]`. Zewnętrzny schemat CK3 wskazuje, że odpowiada polu `knights`; klasyfikacja wymaga jeszcze kontroli w interfejsie. Pozostali dowódcy nieustaleni.

## Rodzina, dworzanie, goście, relacje i stanowiska
**Pełny skład: NIEUSTALONE.** Powyżej są tylko osoby z konkretnymi powiązaniami zadania lub rycerstwa. Nie dopisywać innych posiadaczy sąsiednich tytułów na podstawie geografii. Konrad ma niezależnie potwierdzone posiadanie `b_rottweil` i udział w zadaniu `task_disrupt_schemes`.

## Plan powiązania screenów
Każdej wiarygodnie rozpoznanej osobie założyć katalog `02_POSTACIE/ID/karta.md`, osobny opis źródeł oraz pole portretu. Screenshot zapisać z datą gry, ID i typem panelu. Nie tworzyć kart nieistniejących osób.

## Braki w źródłach
Odczyt zgodnego słownika tokenów funkcji dworskich lub screeny: rada Burkharda, listy dworzan, rycerzy i najbliższa rodzina.
