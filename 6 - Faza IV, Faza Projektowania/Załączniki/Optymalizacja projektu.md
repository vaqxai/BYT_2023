Bezpośrednia implementacja projektu może prowadzić do systemu o niskej efektywności, gdyż np. wykonywanie niektórych funkcji jest zbyt wolne, a struktury mogą wymagać zbyt dużej pamieci operacyjnej lub masowej.

**Sposoby optymalizacji**:
- Na poziomie projektu
- Na poziomie implementacji
	- Stosowanie zmiennych statycznych
	- Umieszczanie zagnieżdżonego kodu zamiast wywoływania procedur
	- Dobór typów minimalnej, niezbędnej wartości

>[!Important] Wiele specjalistów jest przeciwna sztuczkom optymalizacyjnym. Zyski są małe, a nieczytelność jest stanowczo zawyżona.

# Skąd wziąć największe zyski optymalizacyjne?
- Zmiana algorytmu przetwarzania (np. algorytmu sortującego poprzez wprowadzenie pliku pośredniego z kluczami i wskaźnikami do sortowanych obiektów)
- Wyłowienie “wąskich gardeł” i optymalizacja tychże
- Zaprogramowanie “wąskich gardeł” w języku niższego poziomu
- Denormalizacja relacyjnej bazy danych, np. łączenie dwóch tablic w jedną wbrw teorii normalizacji
- Stosowanie indeksów, tablic wskaźników i innych struktur pomocniczych
- Analiza mechanizmów buforowania danych