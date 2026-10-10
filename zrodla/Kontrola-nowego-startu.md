# Kontrola przed rozpoczęciem nowej kampanii

1. Otrzymać nowy natywny zapis CK3 oraz potwierdzić wybraną datę startu i postać gracza.
2. Ustalić wersję gry, DLC, playset, kolejność ładowania i reguły. Nie odtwarzać tych danych ze starej rozgrywki. Upewnić się, że wszystkie 7 wykluczonych pozycji z [katalogu modów](Mody.md) i `mody.json` nie figurują w nowym playsecie. Populated World! jest warunkowy — sprawdzić jego wpływ na wydajność i zachowanie postaci. Zestaw 17 pozycji pozostaje roboczy, do potwierdzenia w launcherze.
3. Odczytać pełny gamestate, tożsamość gracza, posiadaczy tytułów i hierarchię de facto.
4. Dla zamierzonego startu w Cesarstwie sprawdzić posiadacza e_hre, istnienie i status władcy oraz powiązania seniorów. Potwierdzić wynik widokiem tytułu i mapą w grze. Brak pola w częściowym wyciągu sam w sobie nie wystarcza do diagnozy błędu.
5. Przy rozbieżności zatrzymać ustanawianie kanonu. Ustalić, czy wynik pochodzi z reguł, zamierzonej mechaniki moda, konfliktu plików, błędu inicjalizacji lub błędu odczytu. Nie wskazywać przyczyny bez dowodu.
6. Po zgodnym wyniku sprawdzić rodzinę, sukcesję, domenę, dwór, prawa, gospodarkę, relacje i modyfikatory. Każdy odczyt powiązać z nowym źródłem.
7. Dopiero wtedy utworzyć stan początkowy, karty i pakiet fabularny. Pamięć scen zaczyna się od zera.
