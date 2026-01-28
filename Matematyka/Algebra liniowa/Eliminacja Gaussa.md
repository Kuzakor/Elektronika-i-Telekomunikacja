---
Czas stworzenia: "2025-12-19"
---
#matematyka  #algebra_liniowa 
# Definicja
- Jest to sposób na [[Macierz w rozwiązywaniu liniowych układów równań|rozwiązywanie ukladów równań liniowych]] oraz obliczania [[Macierz|macierzy odwrotnej]]
- Polega ona na sprowadzeniu [[Macierz|macierzy]] do tak zwanej *postaci schodkowej* czyli w każdej kolumnie i wierszu powinna znajdować się jedna jedynka a reszta to zera.
- [[Działania elementarne]]
# Macierz odwrotna
- Przy obliczaniu macierzy odwrotnej chcemy sprowadzić [[Macierz]] do bardzo specyficznej *postaci schodkowej* wyglądającej jak [[Macierz]] jednostkowa. Po drugiej stronie pojawi nam się [[Macierz]] odwrotna
$$
\begin{bmatrix}
A|I 
\end{bmatrix} \to [I|B]
$$
# Równania liniowe
- [[Macierz]] doprowadzamy do dowolnej postacii schodkowej
- Ilość rozwiązań zależy od tego co stanie się w między czasie:
	- Wyzerowany wiersz -> Nieskończenie wiele rozwiązań, odpowiadająca zmienna staje się parametrem
	- Wiersz sprzeczny -> Brak rozwiązań
	- Normalna sytuacja -> 1 rozwiązanie.
# Praktyka
- W prakyce zerujemy kolumna po kolumnie poprzed dodawanie n-tego wiersza pomnożonej przez skalar do wszystkich pozostałych aby daną kolumnę wyzerować
- Oraz jeżeli pojawi nam się zero na przekątnej to przesuwami wiersz tak aby nam pasował.
- Gwarantuje to minimalna ilość obliczeń 
