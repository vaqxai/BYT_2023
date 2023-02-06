W trakcie analizy wymagania użytkownika przekształca się w wymagania na oprogramowanie.

Zakres wymagań na oprogramowanie:
![[Załączniki/Wymagania na oprogramowanie.png]]

Wymagania powinny być hierarchiczne, a niefunkcjonalne skojarzone z funkcjonalnymi (np. za pomocą odsyłaczy)

# Reguły modelu logicznego opartego na funkcjach
- Funkcje powinny mieć pojedyncze cele
- Funkcje powinny być zdefiniowane na tym samym poziomie (np Oblicz Sumę Kontrolną jest na niższym poziomie niż funkcja Obsługa Protokołu Sieciowego)
- Interfejsy (we, wy) do funkcji powinny być minimalne
- Przy dekompozycji należy trzymać się zasady “nie więcej niż 7 funkcji podrzędnych”
- Opis funkcji nie powinien odwoływać się do pojęć i terminów implementacyjnych
- Należy podawać wskaźniki wydajnościowe wszędzie gdzie to możliwe
- Powinny być zdefiniowane funkcje “krytyczne”
- Nazwy funkcji powinny być deklaracyjne (odzwierciedlające cel) - mówiące co ma być zrobione, a nie jak ma być zrobione