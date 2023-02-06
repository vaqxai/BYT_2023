# Miary niezawodności
## Prawdopodobieństwo błędnego wykonania
W trakcie realizacji transakcji. Błędne wykonanie powoduje zerwanie całej transakcji. Miarą jest częstotliwość występowania transakcji, które nie powiodły się wskutek błędów

## Częstotliwość występowania błędnych wykonań
Ilość błędów w jednostce czasu, np. 0.1/h. Miara jest stosowana do systemów, które nie mają charakteru transakcyjnego

## Średni czas między błędnymi wykonaniami
Odwrotność poprzedniej miary

## Dostępność
Prawdopodobieństwo, że system w danej chwili będzie dostępny do użytkowania.

# Oszacowanie niezawodności
Niekiedy poziom niezawodności (wartość pewnej miary) jest określany w wymaganiach klienta. Częściej jednak jest wyrażony w terminach jakościowych. Informacja o niezawodności jest przydatna, nawet jeśli klient jej nie określił w wymaganiach.

Dlaczego jest to ważne?
- Częstotliwość błędnych wykonań ma wpływ na koszt konserwacji
- Znajomość niezawodności pozwala szacować koszt serwisu, personel itd
- Znajomość niezawodności pozwala polepszyć preocesy wytwarzania

# Wzrost niezawodności
- Rezultatem wykrycia błędu jest usunięcie błędu
- Jeżeli nie wprowadza to nowych błędów, to mowa o wzroście niezawodności
- Jeżeli wykonywane są testy statystyczne to wzrost niezawodności określa się wzorem logarytmicznego wzrostu niezawodności
	![[Załączniki/Wzrost niezawodności.png]]
- Miarą niezawodności jest częstotliwość występowania błednych wykonań
- Szybszy wzrost niezawodności ma miejsce jeśli w kolejnych przebiegach są testowane nowe sytuacje