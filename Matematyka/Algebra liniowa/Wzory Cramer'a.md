---
Czas stworzenia: "2025-09-23"
---
#matematyka #algebra_liniowa
# Definicja
- Wzory Cramer'a pozwalają rozwiązywać [[Macierz w rozwiązywaniu liniowych układów równań| liniowe układy równań z wykorzystaniem macierzy]] bez obliczania [[Odwrotna macierz|odwrotnej macierzy]].
- Podobne metody: [[Eliminacja Gaussa]], [[Dekompozycja LU]]
# Wzór
$$\begin{cases}  2x+5y = -3 \\ 4x+0y = 0 \end{cases} \Rightarrow \begin{bmatrix} 2 & 5 \\ 4 & 0\end{bmatrix}\begin{bmatrix} x \\ y  \end{bmatrix} = \begin{bmatrix} -3 \\ 0 \end{bmatrix}$$
- Dla każdej obliczanej wspołrzędnej obliczamy pole równoległoboka przed [[Macierz|zastosowaniem macierzy]]. 
- Np. Dla współrzędnej x będzie to iloczyn wartości x oraz [[Podstawa systemu koordynatów|j-hat]]. Dla y będzie to y oraz i-hat. 
- Obliczone pole po zastosowaniu macierzy skaluje się o wartość jej [[Wyznacznik macierzy|wyznacznika]]. 
- Wynika z tego że (1 - wartość j-hat)
$$ S = d(A) * x *1 \Rightarrow S= d(\begin{bmatrix} 2 & 5 \\ 4 & 0\end{bmatrix}) * x$$
- Więc
$$x = \frac{S}{d(A)}$$
- Nowe pole możemy policzyć gdyż znamy współrzędne wektora końcowego (w przykładzie -3 0). W tym celu podmieniamy wartości i-hat na naszą nową matrycę.
$$S = d(\begin{bmatrix} -3 & 5 \\ 0 & 0\end{bmatrix})$$
- Końcowy wzór na bazie przykładu:
$$x = \frac{ d(\begin{bmatrix} -3 & 5 \\ 0 & 0\end{bmatrix})}{ d(\begin{bmatrix} 2 & 5 \\ 4 & 0\end{bmatrix})}$$
$$y =\frac{ d(\begin{bmatrix} 2 & -3 \\ 4 & 0\end{bmatrix})}{ d(\begin{bmatrix} 2 & 5 \\ 4 & 0\end{bmatrix})}$$
- ##### Wzór ogólny
$$ \begin{bmatrix} a & b \\ c & d\end{bmatrix}\begin{bmatrix} x \\ y  \end{bmatrix} = \begin{bmatrix} e \\ f \end{bmatrix}$$
$$x = \frac{d(\begin{bmatrix} e & b \\ f & d\end{bmatrix})}{d(\begin{bmatrix} a & b \\ c & d\end{bmatrix})}$$
$$y=\frac{d(\begin{bmatrix} a & e \\ c & f\end{bmatrix})}{d(\begin{bmatrix} a & b \\ c & d\end{bmatrix})}$$
### Rysunek
[[Wzory Cramer_a.excalidraw]]