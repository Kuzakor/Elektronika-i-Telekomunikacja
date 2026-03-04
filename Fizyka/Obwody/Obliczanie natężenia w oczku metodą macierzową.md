---
Czas stworzenia: "2026-03-04"
---
#fizyka #obwody 
# Co i jak
- Metoda ta służy do wyliczenia [[Natężęnie|natężenia]] lub ewentualnie [[Napięcie|napięcia]] płynącego przez dane oczko.
- Po zaznaczeniu oczek tworzymy następująca [[Macierz|macierz]] opisującą [[Macierz w rozwiązywaniu liniowych układów równań|układ równań]]. 
- -R to [[Rezystor|rezystory]] sąsiadujące z oczkami o indeksie odpowiadającej kolumnie.
- Macierz wyrazów wolnych to napięcia w poszczególnych oczkach.
$$
\begin{bmatrix}
\sum R_{1} & -R_{2} &-R_{3} &\dots &-R_{n} \\
 -R_{1} & \sum R_{2} &-R_{3}, &\dots &-R_{n} \\
\dots &\dots &\dots&\dots&\dots\\
 -R_{1} & R_{2} &-R_{3}, &\dots & \sum R_{n} \\
\end{bmatrix}
\begin{bmatrix}
i_{o_{1}} \\
i_{o_{2}} \\
\dots \\
i_{on}
\end{bmatrix} =
\begin{bmatrix}
U_{1} \\
U_{2} \\
\dots \\
U_{n}
\end{bmatrix}
$$
- Najprościej ten układ rozwiązać korzystając z [[Wzory Cramer'a|wzorów cramera]] z racji że układ musi mieć 1 rozwiązanie. Korzystanie z [[Eliminacja Gaussa|eliminacjii gauusa]] to overkill.