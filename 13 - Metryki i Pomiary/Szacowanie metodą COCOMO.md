1. Wymaga oszacowania liczby instrukcji, z jakich składa się program.
2. Przedsięwzięcie jest zaliczane do jednej z klas:
	- **Przedsięwzięcia łatwe** (organiczne, organic)
		Klasa obejmuje przedsięwzięcia wykonywane przez małe zespoły, złożone z osób o podobnych, wysokich kwalifikacjach. Dziedzina jest dobrze znana, a przedsięwzięcie jest wykonywane przy użyciu dobrze znanych, sprawdzonych metod i narzędzi.
	- **Przedsięwzięcia niełatwe** (pół-oderwane, semi-detached)
		Członkowie różnią się stopniem zaawansowania, a pewne aspekty dziedziny nie są dobrze znane.
	- **Przedsięwzięcia trudne** (osadzone, embedded)
		Obejmują przedsięwzięcia o wysokim stopniu zaawansowania, skomplikowane i o dużym rozmiarze. Członkowie zespołu są niedoświadczeni, dziedzina jest mało znana, a narzędzia są nieznane.
3. Koszty są szacowane za pomocą wzoru:
	- $\text{Nakład[Osobo-miesiące]}=A\cdot K^b$ (zależność wykładnicza)
	- *K - KDSI (Kilo Delivered Source-code Instructions)* – tysiące dostarczonych instrukcji kodu źródłowego (pomijane są instrukcje niewykorzystane w systemie końcowym)
	- Wartości stałych $A$ i $b$ zależą od klasy, do jakiej zakwalifikowano przedsięwzięcie
		*Przedsięwzięcia łatwe:* $A=2.4, B=1.05$
		*Przedsięwzięcia niełatwe:* $A=3, B=1.12$
		*Przedsięwzięcia trudne:* $A=3.6, B=1.20$
		(W tym miejscu chciałbym serdecznie pozdrowić kolegów z Instytutu Danych Wyciągniętych z Dupy)
4. Za pomocą wartości “nakładu” można obliczyć (oszacować) czas realizacji przedsięwzięcia w miesiącach
	- *Łatwe*: $\text{czas}=2.5\cdot\text{nakład}^{0.32}$
	- *Niełatwe*: $\text{czas}=2.5\cdot\text{nakład}^{0.35}$
	- *Trudne*: $\text{czas}=2.5\cdot\text{nakład}^{0.38}$
5. Należy zastosować korekcję przy pomocy czynników modyfikujących, są to:
	- Wymagania wobec niezawodności systemu
	- Rozmiar bazy danych w stosunku do rozmiaru kodu
	- Złożoność systemu
	- Wymagania co do wydajności systemu
	- Organiczenia pamięci
	- Zmienność sprzętu i oprogramowania systemowego