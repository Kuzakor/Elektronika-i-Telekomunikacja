---
Czas stworzenia: "2025-09-22"
---
#matematyka #algebra_liniowa
# Definicja
- Wyznacznik opisuje o ile zostaną przeskalowane pola (objętości) na płaszczyźnie (przestrzenii) po [[Macierz|przekrztałceniu]].  Może on być ujemny gdy płaszczyzna zostanie "odwrócona na druga strone".
- Dotyczy tylko i wyłącznie macierzy kwadratowych
- Jeżeli jest on równy 0 to matryca ta pozbawia nas jednego lub wiecej wymiarów. (Np. objętość kwadrata jest równa zeru), nazywana też macierzą *osobliwą*
# Wzór dla 2x2 i 3x3
$$det \begin{bmatrix} a & c \\ b & d \end{bmatrix} = ad -cb $$
$$\det\begin{bmatrix} a & b & c\\ d & e & f \\ g & h  & i\end{bmatrix} = aei +dhc+ gbf - (ceg +bdi +afh)$$
# Wzór ogólny (Pierwszy wiersz np.)
$$
\det A = D_{11} a_{11} +D_{12}a_{12} + \dots +D_{1n}a_{1n}
$$
- W zależnośći od wybranego wiersza obliczamy [[Dopełnienie algebraiczne|dopełnienie algebraiczne]] i mnożymy przez [[Wektor]] o jeden wymiar mniejszy (wykluczamy rząd i kolumnę z tym punktem)
# Ułatwienie
$$
\det\begin{bmatrix} a & b & c\\ d & e & f \\ g & h  & i\end{bmatrix} = \det \begin{bmatrix} a+xb & b & c\\ d+xe & e & f \\ g+xh & h  & i\end{bmatrix},x \in C
$$
- [[Działania elementarne]] 
# Opis
Dla 3D jest to obliczane za pomocą [[Reguła Sarrusa.excalidraw|reguły Sarrusa]]. 