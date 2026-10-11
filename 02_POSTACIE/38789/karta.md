# Irmengard — CK3 ID 38789

## Aktualizacja po 16 XI 1066 — małżeństwo

**KOREKTA_AUTORA:** Irmengard, córka [Eberharda 31271](../31271/karta.md) i [Ity 31410](../31410/karta.md), poślubiła [Burkharda von Hohenzollern 62634](../62634/karta.md) **3 stycznia**; rok **1067** to WNIOSEK z chronologii po ostatnim save z 16 XI 1066, do potwierdzenia. Potwierdzenie gracza z 11 X 2026. Jest odtąd małżonką Burkharda; wcześniejszy stan zaręczyn z 16 XI 1066 pozostaje prawidłową migawką.

Ekran `Zrzut ekranu 2026-10-11 184600.png` przedstawia zatwierdzaną propozycję małżeństwa: dzieci miałyby należeć do domu von Hohenzollern, opcja matrylinearna była niezaznaczona, odbiorca był skłonny przyjąć propozycję. Nie potwierdza dzieci, miejsca i przebiegu ślubu ani zmiany przynależności dworskiej po zawarciu związku. Stan najnowszego save nie został ponownie odczytany po ślubie.


**Źródło:** `von_Hohenzollern(7).ck3`, SHA-256 `c1c5f879a7d6529c3999c5d751509696ce06ff0ace9b7bcf369398a1e5f6c670`, CK3 1.20.0.4, stan **16 XI 1066**. POTWIERDZONE_SAVE dla pól; OBLICZONE dla wieku i różnic.

## Relacja — 16 XI

Nadal betrothed=62634, odwzajemnione przez Burkharda. Zaręczyny, bez potwierdzenia ślubu; wiek 15, cechy i bazowe umiejętności bez zmian. [Raport](../../07_ANALIZY/rozpoznania_poczatkowe/zmiany_1066-10-20_do_1066-11-16.md).


## Nowy stan — 20 X 1066 (POTWIERDZONE_SAVE)

**Weryfikacja 11 X 2026:** alias `von_Hohenzollern(6).ck3` ma identyczny SHA-256 i stan 20 X 1066. Ponowny odczyt Rakaly 0.8.21 z `--unknown-key error` skorygował wcześniejsze błędne przypisanie małżeństwa: oba rekordy zawierają `betrothed`, nie `primary_spouse`. [Wybrane surowe pola](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/weryfikacja_1066-10-20_2026-10-11.json).


**Źródło:** nowy `von_Hohenzollern(1).ck3`, SHA-256 `4db685e32ffb282fb88c436b37d468bf93c955cf57576b335e9679313afcfca0`. [Raport porównawczy](../../07_ANALIZY/rozpoznania_poczatkowe/zmiany_1066-09-18_do_1066-10-20.md).

- **Narzeczony: [Burkhard 62634](../62634/karta.md)**. Własne `family_data/betrothed=62634` i odwrotne `betrothed=38789` potwierdzają zaręczyny. Poprzedni opis małżeństwa był błędem odczytu.
- Wiek **15** (ur. 1051-01-01); dom Nellenburg **4138**. Sprawdzone bazowe umiejętności `[8,3,0,9,4,8]` i traity `compassionate`, `zealous`, `humble`, `bossy` bez zmiany.
- Nie wywodzono z zaręczyn sojuszu politycznego, potomstwa ani zmiany miejsca pobytu.


**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

## Aktualny odczyt własnego rekordu

**POTWIERDZONE_SAVE:** rekord `living/38789`; imię `Irmengard`; płeć: kobieta (female=yes). Urodzenie: `1051.1.1`.

**OBLICZONE:** wiek **15** na 18 IX 1066, z daty urodzenia.

- Dom: ID **4138**, nazwa/klucz `dynn_Nellenburg`; dynastia ID **4138**. Dom i dynastia mają odrębne identyfikatory.
- Kultura: ID `NIEUSTALONE / brak pola`, `culture_template=NIEUSTALONE / brak pola`. Brak pola nie oznacza braku kultury; wartości domyślnych nie dopowiedziano.
- Obrządek: ID `0`, `roman_rite`; jego rekord wskazuje wiarę ID `13`, `catholic`. Wiara ustalona przez powiązanie obrządku, nie przez założenie religii regionu.
- Bazowy `skill` (DIP / MAR / STE / INT / LEA / PRO): `[8, 3, 0, 9, 4, 8]`. To zapis, nie suma z modyfikatorami interfejsu.
- Traity według `traits_lookup` tego samego save’a: `compassionate` [indeks 75], `zealous` [indeks 72], `humble` [indeks 60], `bossy` [indeks 87].

## Posiadanie, urzędy i zależności

- Aktualne tytuły (przeszukano rekordy posiadaczy): nie znaleziono aktualnie posiadanego tytułu.
- Dwór: `court_data/employer=31271` — [Eberhard 31271](../31271/karta.md). To pole dworu, odrębne od kontraktu lennego.

## Rodzina — zapisane relacje

- Rodzice rozpoznani przez odwrotne powiązanie `family_data/child` w rejestrach żywych i zmarłych: [Eberhard 31271](../31271/karta.md), [Ita 31410](../31410/karta.md). Nie zgadywano drugiego rodzica przy jednym wpisie.
- Brak własnych wpisów `family_data`; nie dowodzi stanu wolnego ani bezdzietności.

## Roszczenia

- Własne pole `alive_data/claim` nie zawiera odczytanych wpisów. Historycznych uprawnień nie dopowiedziano.

## Granice rozpoznania

Wygląd i zatwierdzony portret, efektywne statystyki, pełne opinie, zamiary i sekretne motywy pozostają NIEUSTALONE. Trait, roszczenie lub więź rodzinna nie dowodzi wrogości, sojuszu ani planu spisku.

[Indeks](../indeks_postaci.md) · [Analiza polityczna](../../07_ANALIZY/rozpoznania_poczatkowe/odczyt_szwabia_1066-09-18.md)

Pierwotnie założono tę kartę jako odniesienie ID z rejestru rodzin. Własny rekord odczytano w obecnym rozszerzeniu; wcześniejsze oznaczenie wszystkich danych osobowych jako NIEUSTALONE zostało zastąpione powyższą obserwacją. [Pierwotna transkrypcja rodziny](../../06_MATERIALY_ZRODLOWE/notatki_z_wydarzen/rodziny_1066-09-18.md).
