# Zalety baz danych
- Efektywność, stabilność
- Bezpieczeństwo, prywatność danych, spójność i integralność przetwarzania
- Automatyczne sprawdzanie warunków integralności danych
- Wielodostęp, przetwarzanie transakcji
- Rozszerzalność (zarówno dodawanie danych jak i dodawanie rodzajów danych)
- Możliwość geograficznego rozproszenia danych
- Możliwość kaskadowego usuwania powiązanych danych
- Dostęp przez języki zapytań (tj. SQL)

>[!Important] Integralność i spójność
> To poprawność danych w sensie organizacji i budowy oraz zgodność z rzeczywistością lub oczekiwaniami użytkownika

# Wady baz danych
- Konieczność przeprowadzania nietrywialnych odwzorowań przy przejściu z modelu pojęciowego w strukturę relacyjną
- Ustalony format rekordu może powodować trudności przy polach zminnej długości (w niektórych systemach)
- Trudności reprezentacji dużych wartości (grafiki, pliki tekstowe) zwykle jest niestandardowa
- Czasami duże narzuty czasu przetwarzania (kosztowne złączenia)
- Niedopasowanie interfejsu dostępu do bazy (SQL) do języka programowania (np  Java) określana jako “niezgodność impedancji”
- Brak możliwości rozszerzalności typów (zagnieżdżania danych)
- Brak systematycznego podejścia do informacji proceduralnej