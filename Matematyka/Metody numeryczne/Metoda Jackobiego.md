---
Czas stworzenia: "2026-03-12"
---
#matematyka #metody_numeryczne
# Definicja
- Jest to metoda iteracyjne rozwiązywania [[Macierz w rozwiązywaniu liniowych układów równań|równań liniowych]].
- Wynik nie jest dokładny, jest przybliżony
# Wzór
$$
Ax = b
$$
$$
x_{k+1} = -A_{d}^{-1} (A-A_{d} )x_{k} +A_{d}^{-1}b
$$
$$
A_{d} = \begin{bmatrix}
a_{11}&0 & 0 &\dots &0  \\
0 & a_{22}  & 0 & \dots & 0 \\
0 & 0 & a_{33} &\dots & 0 \\
\dots &\dots & \dots & \dots & \dots \\
0 & 0 & 0 & 0 & a_{nn}
\end{bmatrix}
$$