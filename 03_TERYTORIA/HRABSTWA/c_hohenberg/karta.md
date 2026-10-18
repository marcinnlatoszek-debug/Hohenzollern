# Hrabstwo Hohenberg — `c_hohenberg`

**Status:** ZATWIERDZONE; aktualny punkt kontrolny **18 października 1073**.  
**Źródło:** [raport binarny 18 X 1073](../../../07_ANALIZY/raporty_zmian/CK3_1073-10-18_weryfikacja.md) i [oś wydarzeń](../../../campaign/Os_czasu_Zollern_1070-1073.md).

## Władza i zmiana właściciela

- **12 XI 1070:** hrabina **Adelheid (31878)** posiada `c_hohenberg` i `b_hohenberg`.
- **7 IV 1072:** Burkhard (66952) uzyskuje roszczenie do hrabstwa przez działalność Meinharda.
- **10 IV 1072:** Burkhard wypowiada Adelheid wojnę o roszczenie do Hohenbergu.
- **7 V 1072:** potwierdzone zwycięstwo Burkharda w bitwie przeciw Adelheid; nie przesądza jeszcze końca wojny.
- **16–17 I 1073:** według ekranów kończy się oblężenie, potwierdzono okupację i pojmanie Kathariny.
- **17 I 1073:** **Burkhard wygrywa wojnę i przejmuje `c_hohenberg`**. Dowód: `war_won` i historia tytułu (31878 → 66952).
- **18 X 1073:** Burkhard posiada `c_hohenberg` i `b_hohenberg`; senior tytułu pozostaje księciem Szwabii **Rudolf (35525)**.

**Ważne:** rozbieżny ekran z 10 IV 1072 wskazywał Bertholda z Karyntii jako posiadacza, lecz binarna historia tytułu i pamięć wojny potwierdzają Adelheid jako stronę, od której Burkhard przejął hrabstwo. Nie wywodzić z tej rozbieżności osobnej zmiany tytułu.

## Inspekcja i zarządzanie — 1073

- **15 VI–8 VII:** Burkhard przeprowadza inspekcję Hohenbergu; 8 VII odnosi sukces.
- Według ekranów ogranicza korupcję i bandytyzm, otrzymuje **+50 prestiżu**, Hohenberg dostaje modyfikator „Usprawniony pobór podatków” na 10 lat, a posiadłość priorytet podatkowy na 15 lat (**+2 złota miesięcznie i +15% podatków**); obserwowano też wzrost kontroli i rozwoju.
- **18 X:** zadanie marszałka Radbota `task_increase_control` jest aktywne, lecz bez osobnego mapowania nie należy przypisywać mu na pewno lokalizacji Hohenberg ani motywu decyzji.

## Otwarte kwestie

Nieustalone: dokładna data przejścia `b_hohenberg` niezależnie od hrabstwa, stan wszystkich baronii i budowli, aktualna kontrola i rozwój na 18 X, obecność konkretnych dowódców w bitwie, szczegółowe straty, obecny stan sojuszy i frakcji. Lokalna zmiana właściciela `b_rottweil` (Lothar 48230 → Wenzel 44447) nastąpiła między porównanymi zapisami, **bez ustalonej daty**; nie jest to podbój Burkharda.

---

## Zatwierdzony przekrój — 2 X 1080 (pakiet HZ-1080-10-02-U01)

**Źródło:** zrzuty 212809, 212821, 212832, 212844 z 18 X 2026; [rejestr SHA-256](../../../06_MATERIALY_ZRODLOWE/indeks_screenow_1080-10-02_U01.md). Data gry wskazana przez użytkownika: **2 X 1080**.

- Właściciel **Burkhard von Hohenzollern (66952)**; kontrola **30** (tempo **+1,57/mies.**), rozwój **9**, opinia powszechna **0**, podatek **+1,65/mies.**, pospolite ruszenie **127**, garnizon **320**, poziom fortyfikacji **4**, limit zaopatrzenia **10657**, łup **0**, odporność na zarazę **2**; zamek poziomu 1.
- W porównaniu z poprzednim zatwierdzonym ekranem z **21 VII 1080** kontrola wzrosła z **25 do 30 (+5 punktów pomiędzy obserwacjami)**. Nie nazywać tego jednorazowym wydarzeniem ani nie wskazywać wyłącznej przyczyny bez źródła.
- **Obecność wojskowa:** +20% garnizonu, +1,00 kontroli/mies.; do **4 VII 1083**; historyczny wpis **4 VII 1078**.
- **Zamiana najemników w rolników:** +5% podatku, +200% „liczby kmieci na polach uprawnych”; do **5 VI 1094**. Jest to statystyka z mechaniki gry, **nie bezpośrednia liczba mieszkańców** ani opis decyzji Burkharda.
- **Usprawniony pobór podatków:** +20% podatków; do **3 VII 1083**. Powiązać z inspekcją z lipca **1073**; nie rekonstruować automatycznie dnia nałożenia z daty wygaśnięcia (różnica kilku dni względem wpisu o zakończeniu inspekcji).
- **Garnizon najemników:** +25% garnizonu, +0,30 kontroli/mies., −10 opinii powszechnej; do **29 VI 1083**.
- Archiwalna obserwacja **21 VII 1080** o skutkach splądrowania do **26 VIII 1083** pozostaje w mocy jako osobny wpis, choć ten pakiet nie dostarcza nowego tooltipu tego efektu.
- Ocena (nie nowe wydarzenie): widoczna odbudowa kontroli i równoczesne koszty porządku po wojnie.

Nie zakładać prostego sumowania premii, nowych reform ani szczegółów osadnictwa z opisów modyfikatorów. [Raport](../../../07_ANALIZY/raporty_zmian/CK3_1080-10-02_U01_uzupelnienie.md).
