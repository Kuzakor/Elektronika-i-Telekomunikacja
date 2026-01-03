---
Czas stworzenia: "2025-09-23"
---
#matematyka #algebra_liniowa
# Definicja
- Jest to [[Macierz|przekrztałcenie]] które cofnie działania macierzy do punktu startowego. Zapisuje się ją jako matrycę do potęgi -1. Istnieje wiele sposobów na obliczanie odwrotnej macierzy.
- [[Macierz transponowana]]
- [[Dopełnienie algebraiczne]]
- [[Eliminacja Gaussa]]

#### WAŻNE: Odwrotność istnieje tylko gdy  [[Wyznacznik macierzy|wyznacznik]] macierzy nie jest równy 0. Wyznacznik równy 0 oznacza przekrztałcenie w niższy wymiar czego nie można cofnąć w ten sposób.
# Wzór
$$A^{-1}A = \begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix}$$
$$
A^{-1} = \frac{1}{\det A}\begin{bmatrix}
D_{11} & D_{12} &\dots  \\
D_{21} & D_{22} & \dots \\
\dots &\dots &\dots
\end{bmatrix} ^T
$$
$$

$$
# Opis
Jest to [[Mnożenie (kompozycja) macierzy]] po której [[Podstawa systemu koordynatów|i-hat i j-hat]] powracają do swojej "normalnej" pozycji.