---
Czas stworzenia: "2025-09-23"
---
#matematyka #algebra_liniowa
# Co i jak
Każdy *liniowy* układ równań można zapisać w postaci mnożenia (zastosowania) [[Macierz|macierzy przez wektor]]  gdzie wynikiem jest wektor po przekrztałceniu.  [[Wyznacznik macierzy]] nie może być równy 0.
# Przykład
$$\begin{cases}  2x+5y+3z = -3 \\ 4x+0y+8z = 0 \\1x+3y+0z = 2\end{cases} \Rightarrow \begin{bmatrix} 2 & 5 & 3\\ 4 & 0 & 8 \\ 1 & 3  & 0\end{bmatrix}\begin{bmatrix} x \\ y  \\ z \end{bmatrix} = \begin{bmatrix} -3 \\ 0 \\ 2 \end{bmatrix}$$
$$A\vec{x} = \vec{v} \Rightarrow \vec{x} = \frac{\vec{v}}{A} \Rightarrow \vec{x} = A^{-1} \vec{v}$$
# Opis
- Aby wyliczyc x, y,z musimy obliczyć jaki był początkowy [[Wektor|wektor]] przed [[Macierz|przekrztałceniem]] go w wektor końcowy. 
- Aby to zrobić musimy poznać [[Odwrotna macierz|odwrotną macierz]].
- Lub wykorzystać [[Eliminacja Gaussa|eliminację Gaussa]].
