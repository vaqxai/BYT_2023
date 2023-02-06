# Koszty konserwacji
Zazwyczaj w ocenie koszt konserwacji bywa zaniżony. 
>[!Danger] Zazwyczaj koszty konserwacji kilkukrotnie przewyższają koszty wytworzenia.
Niedocenianie tych kosztów jest jedną z głównych przyczyn opóźnień przedsięwzięć programistycznych

## Obiektywne czynniki wpływające na koszty konserwacji
### Stabilność środowiska w którym pracuje system
Zmiany prawne np, zmiany struktury organizacyjnej i sposobów działania po stronie klienta prowadzą do zmian wymagań wobec systemu

### Stabilność platformy sprzętowej i opr. systemowego

### Czas użytkowania systemu
Koszty konserwacji (całkowite) rosną gdy system jest eksploatowany przez długi czas

## Czynniki redukcji kosztów konserwacji
### Znajomość dziedziny problemu
Jeżeli analitycy dobrze znają dziedzinę problemu, mają mniej trudności z zebraniem wymagań i budową dobrego modelu

### Wysoka jakość modelu i projektu
W szczególności spójność, stopień powiązania składowych oraz przejrzystość

### Wysoka jakość dokumentacji technicznej
Dokumentacja powinna w pełni odpowiadać systemowi, być wystarczająco szczegółowa oraz zgodna  ze standardami panującymi w firmie

### Stabilność personelu
Pewne aspekty systemu są znane tylko osobom bezpośrednio uczestniczącym w realizacji. Ważne jest to, żeby te osoby były przynajmniej dostępne do konsultacji

### Środowisko implementacji
Zaawansowane środowisko sprzyja skróceniu czasu potrzebnego na modyfikacje

### Niezawodność oprogramowania
Zmniejsza liczbę potrzebnych modyfikacji

### Inżynieria odwrotna
Odtwarzanie dokumentacji na podstawie oprogramowania

### Zarządzanie wersjami

### Dekompozycja
Właściwy podział oprogramowania na części jest kluczowy do zmniejszenia kosztów konserwacji

#### Podział na moduły
Z dobrze wyspecyfikowanym interfejsem pomiędzy nimi
- Umożliwia wymianę wadliwych modułów lub przestarzalych
- Zmniejsza przestrzeń oddziaływania błędu (ograniczona do modułu)

#### Warstwy systemu
Zgodne ze specjalizacją lub kierunkiem przekazywania sterowania, np
- MVC (Model, View, Controller) – baza danych, interfejs, logika biznesowa
- Klient-Serwer
- Warstwy zależne od poz. abstrakcji oprogramowania

#### Programowanie aspektowe
Niezależne programowanie zaplątanych (tangled) cech oprogramowania
- Dużo szumu, niewiele efektów