Metody i stosowane notacje są w dużym stopniu nieformalne, a ich użycie zależy silnie od rodzaju przedsięwzięcia. W związku z tym trudno ocenić jakość projektu w sensie adekwatności do procesu konstruowania oprogramowania i stopnia satysfakcji użytkowników: stopień spełnienia wymagań, niezawdoność, efektywność, łatwość w konserwacji i ergonomiczność

Pod terminem *jakość* rozumiemy więc bardziej szczegółowe kryteria:
- Spójność
- Stopień powiązania składowych
- Przejrzystość

>[!Important] Istotne jest spełnienie kryteriów formalnych jakości, które w dużym stopniu rzutują na efektywną jakość, chociaż w żadnym stopniu o niej nie przesądzają. Spełnienie formalnych kryteriów jakości jest warunkiem efektywnej jakości. Nie spełnienie tych kryteriów na ogól dyskwalifikuje efektywną jakość.

# Spójność
Opisuje ona w jakim stopniu części projektu pasują do siebie
Kryteria podziału projektu i rodzaje spójności:
- Podział przypadkowy – np. ze względu na trudność wydruku, edycji
- Podział logiczny – ze względu na podobieństwo funkcji
- Podział czasowy – wg. czasu uruchomienia
- Podział proceduralny – według sekwencji wejścia/wyjścia
- Podział komunikacyjny – według zbioru obsługiwanych danych
- Podział funkcjonalny – według funkcji którą realizują składowe

# Stopień powiązania składowych
W dobrym projekcie powinien być jak najmniejszy
![[Załączniki/Powiązanie składowych.png]]

## Czym są powiązania składowych?
- Korzystanie z tych samuch danych
- Przepływy danych
- Związki klas
- Przepływy komunikatów
- Dziedziczenie
Stopień powiązania można ocenić danymi liczbowymi (kohezja)

# Przejrzystość
>[!Important] Dobry projekt powinien być przejrzysty, czyli czytelny i łatwo zrozumiały.

## Czynniki przejrzystości
- Odzwierciedlenie rzeczywistości
- Spójność i stopień powiązania składowych
- Zrozumiałe nazewnictwo
- Czytelna i pełna specyfikacja
- Odpowiednia złożoność składowych na danym poziomie abstrakcji

>[!Important] Na uwagę zasługuje dziedziczenie oraz przypisanie metod do klas jako czynnik przejrzystości projektu, to pozwala uporścić i zekomponować projekt