---
Czas stworzenia: "2025-11-19"
---
#matematyka #analiza 
# Co i jak
- Jest to sposób [[Całka|całkowania]] [[Funkcja|funkcji]] złożonych. Wynika z [[Pochodna funkcji złożonej| wzoru na pochodną funkcjii złożonej]]
- [[Pochodna]]
- [[Funkcja pierwotna]]
$$
\int f(g(x)) * g'(x) dx = F(g(x)) + C
$$
- Podstawiamy g(x) jaku u
$$
\int f(u)du = F(u)+C=F(g(x)) +C
$$
# Przykład
$$
\int x\sin(x^2) = \int \sin(x^2 )xdx = \begin{Bmatrix}
u =x^2  \\
du = 2xdx \\
\frac{1}{2} du=xdx
\end{Bmatrix} =\frac{1}{2} \int \sin(u)du =-\frac{1}{2}\cos u+C = \frac{1}{2}\cos x^2
 +C$$