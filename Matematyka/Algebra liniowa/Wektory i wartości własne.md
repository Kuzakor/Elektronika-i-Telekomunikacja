---
Czas stworzenia: "2025-09-24"
---
#matematyka #algebra_liniowa
# Definicja
- [[Wektor]] własny w danym [[Macierz|przekrtzałceniu]] to taki który zarówno przed jak i po przekrztałceniu znajduje się na tej samej prostej. Może on jedynie zmienić swój zwrot i/lub zostać wyskalowany przez jakąś wartość. Wartość ta to *wartość własna*. 
- W zastosowaniu może to być przydatne w określeniu wektora który jest osią obrotu danego przekrztałcenia (w 3D) jeżeli jednocześnie jego wartość własna jest równa 1

# Wzór
$$A\vec{v} = \lambda \vec{v} $$
$$A\vec{v} = \begin{bmatrix} \lambda &0 & 0 \\ 0 & \lambda & 0 \\ 0 & 0 &\lambda\end{bmatrix} \vec{v} \Rightarrow A\vec{v} = \lambda I \vec{v} $$
$$(A - \lambda I)\vec{v} = \vec{0}$$
$$Np. (A -\lambda I) =\begin{bmatrix}a - \lambda &b&c \\ d & e -\lambda & f \\ g & h & h- \lambda \end{bmatrix}$$
$$(A -\lambda I) = \vec{0} \Rightarrow d(A - \lambda I) = 0$$

# Opis
A - [[Macierz]]
d - [[Wyznacznik macierzy]]
v - [[Wektor]] własny
lambda - wartość własna