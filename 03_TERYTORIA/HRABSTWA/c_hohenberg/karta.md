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
