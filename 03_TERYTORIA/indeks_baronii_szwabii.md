# Baronie Szwabii de iure — ponowny odczyt 18 IX 1066

**Źródło:** `von_Hohenzollern(2).ck3`, SHA-256 `341d67fc3d15b23b3fba2d33e30a8ce2d4b0f822b3b18c465ec2e2c25821b941`; stan **1066-09-18**, CK3 **1.20.0.4**. Alias (1) ma identyczną zawartość. Odczyt wykonano 10 X 2026.

| Hrabstwo: zapisana nazwa (ID) | Baronia | Posiadacz |
|---|---|---|
| Ulm (1217) | `b_ulm 1218` | [Rudolf 33226](../02_POSTACIE/33226/karta.md) |
| Ulm (1217) | `b_hellenenstein 1219` | brak holder w rekordzie |
| Ulm (1217) | `b_helfenstein 1220` | [Ezzo 45250](../02_POSTACIE/45250/karta.md) |
| Ulm (1217) | `b_schelklingen 1221` | brak holder w rekordzie |
| Grünningen (1222) | `b_grunningen 1223` | [Friedrich 32172](../02_POSTACIE/32172/karta.md) |
| Grünningen (1222) | `b_sigmaringen 1224` | [Ekbert 45251](../02_POSTACIE/45251/karta.md) |
| Grünningen (1222) | `b_berge 1225` | brak holder w rekordzie |
| Grünningen (1222) | `b_heiligenberg 1226` | brak holder w rekordzie |
| Württemberg (1227) | `b_wurttemberg 1228` | [Kuno 34995](../02_POSTACIE/34995/karta.md) |
| Württemberg (1227) | `b_tubingen 1229` | [Friedrich 45252](../02_POSTACIE/45252/karta.md) |
| Württemberg (1227) | `b_teck 1230` | brak holder w rekordzie |
| Baden (1231) | `b_baden 1232` | [Berthold 31865](../02_POSTACIE/31865/karta.md) |
| Baden (1231) | `b_sulz 1233` | [Berthold 31865](../02_POSTACIE/31865/karta.md) |
| Baden (1231) | `b_calw 1234` | [Berthold 31865](../02_POSTACIE/31865/karta.md) |
| Zollern (1235) | `b_zollern 1236` | [Egino 37502](../02_POSTACIE/37502/karta.md) |
| Zollern (1235) | `b_vehringen 1237` | brak holder w rekordzie |
| Zollern (1235) | `b_reutlingen 1238` | [Bernhard 45253](../02_POSTACIE/45253/karta.md) |
| Hohenberg (1239) | `b_hohenberg 1240` | [Burkhard 62634](../02_POSTACIE/62634/karta.md) |
| Hohenberg (1239) | `b_rottweil 1241` | [Konrad 45254](../02_POSTACIE/45254/karta.md) |
| Nellenburg (1242) | `b_nellenburg 1243` | [Eberhard 31271](../02_POSTACIE/31271/karta.md) |
| Nellenburg (1242) | `b_furstenberg 1244` | brak holder w rekordzie |
| Nellenburg (1242) | `b_lupfen 1245` | brak holder w rekordzie |
| Nellenburg (1242) | `b_clettgau 1246` | brak holder w rekordzie |

Kontrola: 23 tytuły baronii, 14 z wpisem holder. Brak holder nie dowodzi całkowitego braku osady. Hierarchia tabeli jest de iure; nie zastępuje zależności kontraktowych. Baden podlega faktycznie Karyntii. Hrabstwo 1242 ma zapisaną nazwę Nellenburg mimo klucza c_furstenberg.

<details>
<summary>Wcześniejsze obserwacje i etap rozpoznania — zachowane historycznie</summary>

# Baronowie i baronie w obrębie analizowanej Szwabii — 1066-09-16

Źródło: `von_Hohenzollern.ck3`, SHA-256 `453ae8b338c428b5ccd9ec4ce591d587969c70317922942642ee163b321edf57`. Identyfikatory tytułów z rekordów `landed_titles`; posiadacz z pola binarnego `0x27d7`.

> Brak identyfikatora posiadacza w rekordzie **nie przesądza**, czy posiadłość istnieje, jest zbudowana, czy jest wakująca. Stan: NIEUSTALONE.

| Hrabstwo (ID) | Baronia (CK3 ID) | Klucz z gry | Posiadacz zapisany w tytule |
|---|---:|---|---|
| Ulm (1217) | 1218 | `b_ulm` | Rudolf (ID 33226) |
| Ulm (1217) | 1219 | `b_hellenenstein` | NIEUSTALONE / brak ID |
| Ulm (1217) | 1220 | `b_helfenstein` | Ezzo (ID 45250) |
| Ulm (1217) | 1221 | `b_schelklingen` | NIEUSTALONE / brak ID |
| Grüningen (1222) | 1223 | `b_grunningen` | Friedrich (ID 32172) |
| Grüningen (1222) | 1224 | `b_sigmaringen` | Ekbert (ID 45251) |
| Grüningen (1222) | 1225 | `b_berge` | NIEUSTALONE / brak ID |
| Grüningen (1222) | 1226 | `b_heiligenberg` | NIEUSTALONE / brak ID |
| Württemberg (1227) | 1228 | `b_wurttemberg` | Kuno (ID 34995) |
| Württemberg (1227) | 1229 | `b_tubingen` | Friedrich (ID 45252) |
| Württemberg (1227) | 1230 | `b_teck` | NIEUSTALONE / brak ID |
| Baden (1231) | 1232 | `b_baden` | Berthold (ID 31865) |
| Baden (1231) | 1233 | `b_sulz` | Berthold (ID 31865) |
| Baden (1231) | 1234 | `b_calw` | Berthold (ID 31865) |
| Zollern (1235) | 1236 | `b_zollern` | Egino (ID 37502) |
| Zollern (1235) | 1237 | `b_vehringen` | NIEUSTALONE / brak ID |
| Zollern (1235) | 1238 | `b_reutlingen` | Bernhard (ID 45253) |
| Hohenberg (1239) | 1240 | `b_hohenberg` | Burkhard (ID 62634) |
| Hohenberg (1239) | 1241 | `b_rottweil` | Konrad (ID 45254) |
| Fürstenberg (1242) | 1243 | `b_nellenburg` | Eberhard (ID 31271) |
| Fürstenberg (1242) | 1244 | `b_furstenberg` | NIEUSTALONE / brak ID |
| Fürstenberg (1242) | 1245 | `b_lupfen` | NIEUSTALONE / brak ID |
| Fürstenberg (1242) | 1246 | `b_clettgau` | NIEUSTALONE / brak ID |

## Liczby kontrolne
- 7 hrabstw w strukturze tytułu `d_swabia` (w tym Baden z odmienną relacją de iure).
- 23 tytuły baronii w ich wykazach; 14 ma wskazane ID posiadacza, w 9 brak ID posiadacza.
- Każdy wyżej wymieniony identyfikator można w przyszłości powiązać z osobną kartą ziemi i screenem mapy. Dla Hohenbergu osobne karty baronii są zakładane priorytetowo.

</details>
