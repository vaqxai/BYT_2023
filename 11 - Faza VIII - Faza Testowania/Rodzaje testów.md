# Podział z punktu widzenia
## Wykrywanie błędów
Celem jest wykrycie jak największej liczby błędów

## Testy statystyczne
Celem jest wykrycie przyczyn najczęstszych błędnych wykonań i ocena niezawodności

- Losowa konstrukcja danych wejściowych zgodnie z rozkładem prawdopodobieństwa tych danych
- Określenie wyników poprawnego działania na tych danych
- Uruchomienie systemu i porównanie wyników z poprawnymi
(Powtarzane cyklicznie)

>[!Warning] Testy statystyczne są mało efektywne i rzadko stosowane

# Podział z techniki wykonywania
## Testy statyczne
Wykonywanie kodu w myśli, ręczna naoczna analiza

## Testy dynamiczne
Wykonywanie fragmentów programu i ocena wyjścia przez porównanie z poprawnym wynikiem

# Testy “skrzynkowe”
## Testy białej skrzynki (strukturalne)
Odpowiednie dobranie danych wejściowych tak, żeby sprawdzić wewnętrzną logikę (wszystkie ścieżki przebiegu sterowania)

## Testy czarnej skrzynki (funkcjonalne)
Sprawdzenie funkcji programu bez zaglądania do kodu. Powinno obejmować cały zakres danych wejściowych. 

# Testy wstępujące i zstępujące
## Wstępujące
Od najmniejszych elementów do całego systemu
## Zstępujące
Odwrotnie (przy testowaniu większych części mniejsze elementy zastępuje się implementacjami szkieletowymi)

# Testy obciążeniowe i odpornościowe
## Obciążeniowe (stress test)
System testowany jest pod pełnym lub nawet nadmiarowym obciążeniem

## Testy odporności (robustness test)
Sprawdzenie testu w przypadku zajścia niepowołanych zdarzeń tj. awaria zasilania, sprzętowa, niepoprawne dane niepoprawne polecenia