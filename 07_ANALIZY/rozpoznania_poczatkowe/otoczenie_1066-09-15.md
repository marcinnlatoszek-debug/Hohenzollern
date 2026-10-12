# Rozpoznanie najbliższego otoczenia — 15 września 1066

## Potwierdzone fakty

- Burkhard (66943), wiek 16, jest hrabią Zollern i głową domu von Hohenzollern (13475).
- W profilu nie znaleziono czytelnych rodziców; w polach family_data nie odczytano małżonka ani dzieci. To nie rozstrzyga pełnego drzewa rodzinnego.
- Zidentyfikowano pięciu radnych z przypisanymi zadaniami oraz pięciu dodatkowych dworzan przypisanych employer=66943.
- Rudolf (35525) trzyma k_swabia_herzog (202) i d_swabia (3348), a jego de facto senior to Heinrich (41198), cesarz e_hre (199).
- 31 hrabstw de iure Szwabii jest podzielonych między księcia i 11 hrabiów.
- De facto bezpośrednio cesarzowi podlegają Ravensburg/Welf, Pfinzgau/Einhard, Thurgau/Romuald i Clettgau/Werner.
- Zollern ma dwa castle_holding z fort_level 7; Burkhard ma holder ID na b_zollern, a dla b_gammertingen holder ID nie ustalono.
- W historii Zollern występuje Friedrich (41148) jako wcześniejszy posiadacz, a obecny save zapisuje zmianę z typem revoked.

## Wnioski sytuacyjne

1. **Ciągłość domu jest wrażliwa.** Burkhard ma 16 lat, a następca zapisany dla Zollern to książę Rudolf. Jeżeli nic nie zmieni sukcesji przed śmiercią Burkharda, tytuł może przejść poza nowy dom. To scenariusz warunkowy, nie prognoza zdarzenia.
2. **Zollern ma wyraźny punkt obrony.** b_zollern i b_gammertingen mają najwyższy w regionie rozpoznanym fort_level 7. Save nie dowodzi, kto kontroluje każdy zamek ani jak wygląda teren poza mapą holdings.
3. **Szwabia ma dwie warstwy zwierzchnictwa.** De iure jedność pod d_swabia nie odpowiada całkowicie de facto: czterech hrabiów podlega bezpośrednio cesarzowi.
4. **Poprzednik pozostaje potencjalnym uczestnikiem wątku.** Friedrich 41148 jest w sekcji żyjących postaci i został zapisany jako poprzedni posiadacz; przyczyna utraty tytułu, roszczenie i relacja z Burkhardem są nieznane.
5. **Rada może podtrzymywać codzienną akcję.** Jej zadania są w save potwierdzone, ale bez nazw traits nie przypisujemy poszczególnym osobom lojalności ani motywów.

## Ograniczenia

Nie ustalono składu armii, aktywnych wojen, opinii wasali, roszczeń Friedricha, rodziców Burkharda, populacji ani nazw modów. Cechy występują jako numeryczne IDs i wymagają screenów/definicji. Statystyki wojskowe są skopiowane z pól save’a, bez interpretowania ich jako liczby oddziałów w polu.

Źródło: `von_Hohenzollern(1).ck3` • CK3 1.20.0.4 • stan 1066-09-15 • SHA-256 `E8DD2ECAC4D525EBF5456C22B5B3D3FA9422D45F620D57298FD25830B55A85D7`


## Korekta po porównaniu z save2

W save1 c_kirchberg (3460) już miało de_facto_liege=201 (Bawaria), a nie Swabia (202). Save2 pokazuje nowo utworzone d_augsburg (2678) Arnolda jako pośredni tytuł zależności Kirchbergu; samo d_augsburg jest de facto pod Bawarią. Wcześniejsze wpisy w tym raporcie i strukturze, które nazywały Kirchberg wasalem de facto Swabii, były błędne; zostały poprawione w indeksie i aktualnej strukturze.

Save2 potwierdza też zmiany tytułów Teck (Berthold 43117 od 1066-10-10) i Urach (Bernhard 61007 od 1066-10-18), małżeństwo Burkharda z Hedwig, gościa Gerharda (44445) oraz skutek wydarzenia rolnego w Zollern. Szczegóły i ograniczenia: [porównanie save’ów](../porownania_save/porownanie_1066-09-15_1067-01-15.md).
