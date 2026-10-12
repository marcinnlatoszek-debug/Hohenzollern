# Koncentracja wojsk pod Hohenbergiem — 17–19 XI 1067

**Status:** POTWIERDZONE_SCREEN z 17 XI i 19 XI 1067. Zrzuty są datowanymi migawkami mapy CK3, **nie** są nowymi zapisami `.ck3`. Ostatni odczytany save pozostaje z **14 XI 1067**.

## Źródła

| Data widoczna w kalendarzu CK3 | Oryginalny załącznik | SHA-256 | Obserwacja |
|---|---|---|---|
| **17 XI 1067** | `Zrzut ekranu 2026-10-12 193225.png` | `b9831af332c79cbb393cd719c4b3748488b7ea7d5ea6c3a610ebd6660ad3899a` | Zgrupowanie **(3) 1843** oraz odrębne znaczniki **1357**, **296**, **210** i **440** na mapie rejonu Hohenbergu; bez panelu składu trójki |
| **19 XI 1067** | `Zrzut ekranu 2026-10-12 193940.png` | `133c88d1b1a0297f3b79f7d019b13e6be0b3cb8651a17c191adea541d15a6f6b` | Panel `Armies in this location` identyfikuje trzy armie i ich liczebność; widoczne powiadomienie z **18 Nov** o dołączeniu hrabiego Kuna i jeszcze jednego władcy |

Oba pliki PNG pozostają załącznikami rozmowy; w publicznym repozytorium zachowuje się opis, metrykę oraz hash, a nie ich binarną kopię. Datę świata odczytano z dolnego kalendarza obrazu; czas utworzenia nazwy zrzutu dotyczy czasu rzeczywistego 12 X 2026.

## Potwierdzony skład koncentracji 19 XI

Otwarty panel `Armies in this location` pokazuje **trzy odrębne armie w jednym miejscu**:

| Nazwa w grze | Liczba żołnierzy z panelu |
|---|---:|
| `1st Army of Hohenberg` | **738** |
| `1st Army of Ulm` | **715** |
| `1st Army of Schmalkalden` | **390** |
| **Suma (OBLICZONE)** | **1 843** |

Ikona `(3) 1843` na mapie jest zgodna ze składem panelu. Współobecność trzech armii w tej samej lokalizacji **nie oznacza scalenia dowództwa, trzech różnych stron konfliktu, zakończenia bitwy ani jednego rozkazu marszowego**.

**Porównanie z 17 XI:** na wcześniejszym ekranie także widoczny jest znacznik **(3) 1843**, lecz **jego skład na ten dzień nie był potwierdzony osobnym panelem**. Zgodność liczebności silnie sugeruje ciągłość tego samego zgrupowania (WNIOSEK), nie upoważnia do przepisywania dokładnych stanów trzech armii wstecz na 17 XI.

**Dowódcy:** save z 14 XI wskazuje **Gerharda 62635** jako `commander` armii Hohenbergu (ID 388) i **Rudolfa 33226** jako `commander` jego armii (ID 355). Na ekranie 19 XI nie ma tooltipów dowódców; nie przenosić automatycznie tych danych jako nowego źródła potwierdzającego dowództwo na 19 XI. Dowódca Schmalkalden **NIEUSTALONY**.

## Inne oddziały na mapie

Na screenie 19 XI w sąsiedztwie mapy widoczne są odrębne znaczniki **210** i **440**. Liczby są zgodne ze stanami `current_strength` domen Egina II (210) i Eberharda VI (441) w save z 14 XI oraz wcześniejszą obserwacją mapy, ale **sam ekran nie wyświetla tooltipów** rozstrzygających nazwy, dowódców i strony tych jednostek. Nie sumować ich bez zastrzeżeń jako jednej armii łącznie z trójką.

Na ekranie 17 XI widoczny jest także znak armii **1357**, odpowiadający wcześniejszemu rozpoznaniu Villach księcia Bertholda II, oraz **296**, bez odczytanego osobnego dowódcy. Nie dopisywać do żadnej z tych liczb wyniku bitwy ani określonego marszu.

## Nowe powiadomienie — 18 XI 1067

**POTWIERDZONE_SCREEN (kalendarz na ekranie 19 XI):** powiadomienie `Allies Join War: Count Kuno and 1 other` z datą `18 Nov` oraz tekst `Count Kuno and 1 other Ruler have joined the War on your side`. Oznacza **hrabiego Kuna i drugiego, niezidentyfikowanego z imienia władcę** po stronie gracza.

**Ważne zestawienie SAVE vs SCREEN:** [Kuno z Wirtembergii ID 34995](../../02_POSTACIE/34995/karta.md) znajduje się już w `active_wars/36` w save z **14 XI**, a zapisane przy nim pole technicznej daty uczestnictwa ma wartość **13 XI**. Powiadomienie z **18 XI** jest o pięć dni późniejsze. Podobna pięciodniowa różnica występuje przy Hermannie, Eginie II i Eberhardzie VI. Mechanizm różnicy **NIEUSTALONY**; **nie traktować tego jako ponownego przystąpienia Kuna ani jako dowodu dwóch różnych wojen**. Drugiego władcy nie wolno utożsamić z dowolną postacią z listy wcześniejszych sojuszników bez innego źródła.

## Zastosowanie w osi fabuły

- Datować **koncentrację trzech osobnych armii** w rejonie Hohenbergu **najpóźniej na 19 XI**, z widoczną migawką zbiorczą także **17 XI**. Nie ustalać dokładnego dnia zawiązania zgrupowania.
- Zachować **18 XI** jako datę powiadomienia o Kunie i kolejnym władcy (nie podwójne wejście Kuna).
- Nie ogłaszać nowej bitwy, zwycięstwa, oblężenia, przemarszu lub osobistego dowodzenia Burkharda na podstawie samej koncentracji.
- **Oddzielny, wcześniej zatwierdzony kanon:** bitwa pod Hohenbergiem zakończyła się zwycięstwem **31 VIII 1067**; Gunzelin został ranny **23 VIII**, a później wyzdrowiał według potwierdzenia gracza (dzień zdrowienia w grze nieznany). Nowa koncentracja listopadowa **nie jest kontynuacją tamtej bitwy** tylko dlatego, że dotyczy tego samego obszaru.

[Oś fabuły](../../01_KAMPANIA/os_fabuly.md) · [Główny rejestr wojsk](wojna_szwabska_1067_lipiec_listopad.md) · [Indeks screenów](../indeks_screenow.md) · [Nadrzędny save 14 XI](../../07_ANALIZY/rozpoznania_poczatkowe/weryfikacja_save_1067-11-14.md).
