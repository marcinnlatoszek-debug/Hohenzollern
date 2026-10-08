# Otoczenie Szwabii — regionalny atlas polityczny (24 IX 1070)

**Źródło:** natywny `von_Hohenzollern.ck3`, wersja gry 1.20.0.4; SHA-256 `93c678bd1c9aa73f58ad51f504f508ff5517927dc8a6a4023a8b437f45f4decc`. Data stanu: **24 września 1070**. Wartości liczebności sił odnoszą się do poszczególnych postaci, nie do połączonych armii ich wasali. Cechy i następców przedstawia się zgodnie z konkretną datą; przyszłość nie jest ustalona.

**Obowiązuje autorska korekta:** Friedrich Hohenberg należy do dynastii Hohenberg, niezależnie od niepoprawnego wyświetlania nazwy w grze. Bieżący save ma pierwszeństwo przed screenem we wszystkich pozostałych kwestiach mechanicznych.

## 1. Księstwa otaczające i powiązane ze Szwabią

| Księstwo | Tytuł ID | Władca (postać ID) | Siła postaci | Roszczeniodawcy do tytułu |
|---|---:|---|---:|---:|
| Alzacja | 1198 | tytuł nieobsadzony | — | 0 |
| Augsburg | 983 | tytuł nieobsadzony | — | 0 |
| Churrätien | 1184 | tytuł nieobsadzony | — | 0 |
| Wschodnia Frankonia | 1132 | Anno (28593) | 813 | 3 |
| Nordgau | 942 | Dietpold (33396) | 669 | 16 |
| Bawaria | 905 | Otto (32148) | 1800 | 0 |
| Karyntia | 1060 | Hermann (38069) | 1816 | 5 |
| Górna Lotaryngia | 837 | Gerhard (32273) | 2492 | 14 |
| Zachodnia Frankonia | 1089 | Heinrich (38652; również cesarz) | 6078 | 3 |
| Górna Burgundia | 7607 | Guillaume (31537) | 1282 | 0 |
| Lombardia | 2328 | Alberto-Azzo (30342) | 1410 | 2 |
| Styria | 1003 | Otakar (32817) | 1886 | 3 |
| Austria | 1020 | Ernst (35179) | 153 | 2 |
| Czechy / Bohemia | 3417 | Vratislav (34276) | 4891 | 4 |

Są to wybrane **księstwa pograniczne lub powiązane politycznie**, a nie geometrycznie wyliczona lista wszystkich ziem o wspólnej granicy. W pełnym indeksie odczytano 81 hrabstw de iure należących do 14 wymienionych księstw.

## 2. Pięć hrabstw pod Rudolfem, ale prawnie poza Szwabią

| Hrabstwo | De iure | De facto |
|---|---|---|
| Ravensburg `c_ravensburg` (997) | Augsburg (983) | Szwabia (1216) |
| Burgau `c_burgau` (1000) | Augsburg (983) | Szwabia (1216) |
| Nördlingen `c_nordlingen` (1157) | Wschodnia Frankonia (1132) | Szwabia (1216) |
| Zürich `c_zurich` (1193) | Churrätien (1184) | Szwabia (1216) |
| Sundgau `c_sundgau` (1211) | Alzacja (1198) | Szwabia (1216) |

**Kontrast:** Baden `c_baden` (1231) należy de iure do Szwabii, ale de facto podlega księciu Hermannowi w Karyntii. Knittelfeld `c_knittelfeld` (1070) de iure należy do Karyntii, de facto do Styrii. Tytuły książęce Alzacji, Augsburga i Churrätien pozostają nieobsadzone; istnieją za to ich hrabstwa, podzielone między różnych seniorów.

Przykład rozdrobnienia **Alzacji de iure**: Strasburg podlega bezpośrednio Cesarstwu, Breisgau Karyntii, Colmar Górnej Lotaryngii, a Sundgau Szwabii. W **Augsburgu de iure** Ravensburg i Burgau podlegają Rudolfowi, samo Augsburg i Alpsee Bawarii, a Kempten bezpośrednio Cesarstwu. **Churrätien:** Zürich należy do Rudolfa, Grisons i Sankt Gallen podlegają bezpośrednio Cesarstwu.

## 3. Wojny już toczące się w regionalnej polityce

**Wojna o Nordgau — ID 58.** Atakujący Vratislav `34276` (Czechy/Bohemia), obrońca Dietpold `33396` (Nordgau), cel `d_nordgau` `942`, CB `claim_cb`. Zapis zawiera rezultat jednej bitwy i straty. To rzeczywista aktywna wojna, nie przypuszczenie.

**Wojna Austrii o Styrię — ID 16.** Ernst `35179` (Austria) atakuje Otakara `32817` (Styria); cele obejmują `d_steyermark` `1003` i `c_amstetten` `1040`. Zapisano już sześć rezultatów bitew. Folmar `48511` z Knittelfeld występuje po stronie obrońców. To inna osoba niż Folmar, zarządca Burkharda — nie łączyć imienników.

**Miśnia — ID 33554449.** Główny atakujący Otto `33265` (Miśnia), obrońca Dedo `30556`, cel `d_meissen` `3542`, CB `individual_duchy_de_jure_cb`. **Książę Otto Bawarski `32148` bierze udział po stronie atakującej**, ale nie jest inicjatorem tej wojny.

**Wojna o wolności — ID 92.** Voislav `33544` występuje jako atakujący, Sviatoslav `33377` jako obrońca. Książę Vratislav `34276` bierze udział **po stronie obrońców**. Jest to drugi równoległy konflikt z udziałem czeskiego księcia; nie utożsamiać go z wojną o Nordgau.

**Przygody Herewearda — ID 113 i ID 127.** Hereweard `37080` jest atakującym w osobnych aktywnych konfliktach przeciw cesarzowi Heinrichowi `38652` i księciu-arcybiskupowi Siegfriedowi `34082`. To nie jest bezpośrednia wojna Burkharda.

## 4. Frakcje i wewnętrzne napięcia

| Frakcja | Cel | Przywódca | Niezadowolenie | Siła / próg |
|---|---|---|---:|---:|
| `16777333`: liberty faction | Anno `28593`, Wschodnia Frankonia | Konrad `34084`, Hohenlohe | **100** | **75.156 / 50** |
| `145`: liberty faction | Gerhard `32273`, Górna Lotaryngia | Hermann `38124`, Colmar | brak wartości | 17.72 / 70 |
| `211`: liberty faction | Otto `32148`, Bawaria | Meginhard `37282`, München | brak wartości | 24.024 / 50 |
| `83`: liberty faction | Matilda `37721`, Toskania | Enrico `30392`, Verona | brak wartości | 17.451 / 50 |

Przy braku pola `discontent` **nie zastępować go zerem**. Wartość `power=75.156` i próg `50` to pola techniczne, nie procent szansy na rewolucję. Szczególnie istotna jest obecna frakcja Konrada z Hohenlohe przeciw Annonowi. Nördlingen, podległe Rudolfowi, jest **de iure** częścią Wschodniej Frankonii, co zwiększa potencjał jej politycznego oddziaływania na naszą opowieść. Nie dowodzi to formalnego udziału Hartmanna we frakcji.

## 5. Aktywne schematy i sekrety — wiedza analityczna, NIE wiedza bohaterów

- Otto z Bawarii `32148` → Kuno z Regensburga `31305`: `sway` (schemat `33554542`).
- Dietpold z Nordgau `33396` → Potho z Leuchtenburga `33078`: `sway` (schemat `67108981`).
- Cesarz Heinrich `38652` → książę-arcybiskup Siegfried `34082`: `sway` (schemat `220`).
- Gerhard z Górnej Lotaryngii `32273` → Hermann z Colmar `38124`: `sway` (schemat `16777639`).
- Udalrich z Kaiserslautern `34463` → Reginhard `33564`: aktywny `murder` (schemat `33554828`), `scheme_exposed=false`. Istnienie planu wynika z save’a; żadnego zgonu ani powodzenia nie potwierdzono. **Nie nadawać Burkhardowi wiedzy o tajnym planie bez uzasadnionego sposobu jej uzyskania.**
- Burkhard `62640` → Hartmann `37494`: aktywny `sway` (schemat `50332181`), utrwalony już w głównym atlasie.

## 6. Propozycje wątków narracyjnych — możliwe, nie przesądzone

**Nordgau i Czechy:** wojna zwiększa napięcie przy wschodnim krańcu regionu; nie należy jeszcze przewidywać jej wyniku. **Wschodnia Frankonia:** frakcja wolnościowa przeciw Annonowi i prawna przynależność Nördlingen mogą rodzić niepewność sąsiadów Rudolfa. **Alzacja, Augsburg i Churrätien:** podzielone zwierzchnictwo to wiarygodne źródło sporów o lojalność, prawa i powinności. **Styria i Austria:** toczy się wojna, która może wpływać na atmosferę bezpieczeństwa w Cesarstwie. **Cesarz i arcybiskup:** równoczesne zabiegi dyplomatyczne i konflikty z Hereweardem sugerują wielowątkowe zaabsorbowanie dworu cesarskiego — bez automatycznego wniosku o słabości państwa.

**Wymóg perspektywy:** narrator może wiedzieć, że save zawiera konflikt lub sekretny schemat, ale postacie w opowiadaniu mogą je znać tylko po wiadomości, własnej obserwacji lub innym uzasadnionym kanonicznie źródle. Żadnej prognozy nie zapisywać jako dokonanego faktu gry. Każdy kolejny nowszy save staje się nowym bieżącym punktem kontrolnym, ten atlas pozostaje migawką z 24 IX 1070.
