# Zatwierdzony audyt: Gerlach, Gautselin i finanse Burkharda (2 X 1080)

**Pakiet:** `HZ-1080-10-02-U02`. **Zatwierdzono:** 18 X 2026. **Data gry:** 2 X 1080 według użytkownika.  
**Kanon:** Supabase `aieqqyglilxgyjnbfzws`, schemat `chronicle`; GitHub jest kopią zapasową.  
**Źródła:** [rejestr 6 plików i SHA-256](../../06_MATERIALY_ZRODLOWE/indeks_screenow_1080-10-02_U02.md); user-approved source record. Wartości zachowują dokładnie precyzję pokazanej lokalizacji CK3.

## 1. Gautselin — nowa postać, nie nowy poród w dniu obserwacji

Zrzut `214932`: **Gautselin**, **11 lat**, **dworzanin**, **nisko urodzony**, opis interfejsu **„Bezduszny oportunista”**. Kultura **szwabska**, obrządek **rzymski**.

| Umiejętność | Wartość |
|---|---:|
| Dyplomacja | 4 |
| Wojskowość | 8 |
| Zarządzanie | 10 |
| Intryga | 4 |
| Nauka | 4 |
| Waleczność | 6 |

**Rodzice:** Gerlach (CK3 **72054**) oraz Luitgard, jego małżonka. Zakładka na ekranie: **Dzieci (0)** i **Rodzeństwo (0)**. Brak potwierdzonej małżonki Gautselina; placeholder „Znajdź małżonka” nie jest dowodem zaręczyn. Ekran pokazuje 11 lat, ale nie podaje dokładnej daty urodzenia. **Nie nadano Gautselinowi ID CK3**. W bazie przydzielono jedynie **klucz archiwalny**, odrębny od identyfikatora gry.

Interpretacja postaci „Bezduszny oportunista” nie jest odczytem kodowych cech z tabeli `traits`, więc nie przypisano konkretnych nazw traitów bez tooltipów. Jego bliskość wiekowa do dzieci Burkharda nie dowodzi ich przyjaźni ani wspólnego wychowania.

## 2. Gerlach — rodzina i stanowiska

Z tej samej podpowiedzi: **Gerlach, 37 lat**, **zarządca, łowczy i rycerz**; przebywa w **Zollern**. Potwierdzono żonę **Luitgard** i syna **Gautselina**. Osobowość wyświetlana w UI: **„Współczujący oportunista”**. Obrządek rzymski, kultura szwabska. Wcześniej w kanonie: zarządca, **wielki łowczy** i rycerz; **nigdy nie przypisywać mu kanclerstwa**. Nie nadpisywać wcześniej odczytanych cech: `brave`, `lustful`, `gregarious` bez nowego save'a.

**Otwarte:** daty ślubu, urodzenia Gautselina, pełny ID CK3 Luitgard oraz zgodność tej Luitgard z jakąkolwiek inną znaną imienniczką. Zachowano je jako NIEUSTALONE. Syn Gautselin nie jest automatycznie wpisany do dworu Burkharda w sensie tytułu, jeżeli ekran nie ustala konkretnej zależności senioralnej.

## 3. Finanse i siły Burkharda

Na pasku: **371 złota**, zmiana **+3,9/miesiąc**, siła wojskowa **1406**. Wskaźnik przy osobnej ikonie **2/4** bez właściwej podpowiedzi pozostaje **nierozpoznany** (nie utożsamiać z domeną ani rycerzami).

| Miesięczna pozycja | Złoto |
|---|---:|
| Budowle siedziby | +0,6 |
| Domena | +7,6 |
| Podatki wasalne | +0,1 |
| Skupienie na bogactwie | +10% do dochodu |
| **Przychody łącznie** | **+9,2** |
| Niepowołani zbrojni | −3,8 |
| Podatki senioralne | −0,8 |
| Urzędy dworskie | −0,5 |
| **Wydatki łącznie** | **−5,3** |
| **Bilans miesięczny** | **+3,9** |

Kwoty UI są zaokrąglone; suma podkategorii może nie odtwarzać dokładnie sumy wynikowej przy zastosowaniu procentowych bonusów.

Poprzedni zatwierdzony panel wojskowy z 24 VII 1080 pokazywał **1207** żołnierzy; obecny **1406**, co daje różnicę **+199 pomiędzy obserwacjami**. Nie przypisywać jednoznacznie przyrostu do zlecenia +100 łuczników i +100 lekkiej piechoty bez nowego składu regimentów.

## 4. Prestiż, pobożność i renoma

- **Prestiż Burkharda 946**, **+0,99/mies.**; poziom sławy **„Postać wybitna”**, następny **„Postać niezrównana”** (`215053`).
- **Pobożność 271**, **+2,10/mies.**; religijność **„Postać sumienna”**, następny wyświetlany **„Postać wierząca”** (`215102`).
- **Renoma dynastii 102**, **+0,35/mies.**; splendor **„Początek korzeni”**, kolejny na UI **„Nieznana”** (`215111`). Renoma jest wskaźnikiem dynastii, a nie osobistym prestiżem Burkharda.

## 5. Legitymacja

Zrzut `215149`: **„Uznany władca”**, poziom **2/5**, postęp **350/1000**, przyrost **0,00/miesiąc**.

Efekty wyświetlone na ekranie: **−25% okresu krótkiego panowania**, nieznacznie zmniejszony koszt roszczenia `casus belli`, nieznacznie zwiększona akceptacja małżeństw. Oczekiwana średnia legitymacja wśród „wasali wpływowych” i „wasali” to **„Ambitny (1/5)”** w obu wierszach — jest to etykieta mechaniki oczekiwań, nie opis traitu wszystkich osób.

Poziom 2/5 został wcześniej zaobserwowany **14 IV 1073**. Zrzut z 1080 **potwierdza trwanie poziomu, nie nowy awans**.

## 6. Charakter chronologiczny i niepewności

Wszystkie sześć kadrów zakwalifikowano jako **przekrój sytuacji na 2 X 1080**. Nie dopisano dat urodzin, ślubów, awansów czy nowych konfliktów. Wiek jest pełnymi latami z panelu, a nie źródłem konkretnej daty urodzenia.

Równolegle zachowano starsze pomiary w kanonie oraz punkt zatwierdzonego zapisu `von_Hohenzollern(20261016-154350).ck3`. Pakiet U02 ma własny klucz i źródła, nie podmienia U01. W Supabase zweryfikowano 6 rekordów `screenshot`, zatwierdzenie `conversation`, snapshoty Gautselina/Gerlacha/Burkharda, 3 relacje, jeden event i jeden wpis osi.
