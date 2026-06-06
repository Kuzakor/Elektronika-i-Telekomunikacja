---
Czas stworzenia: "2026-05-18"
---
#matematyka #analiza 
# Definicja
- Jest to [[Szereg|szereg]] pozwalający przyblizyć [[Funkcja|funkcję]] za pomocą [[Funkcje trygonometryczne|funkcjii trygonometrycznych]]. 
- Funkcja która przybliżamy musi być [[Okresowość funkcji|okresowa]] a najlepiej z okresem 2pi
- Poniższe [[Całka|całki]] muszą być po całym okresie, niekoniecznie 0 - 2pi1
- W przypadku okresu innego niż 2pi wystarczy odpowiednio podzielić argumenty funkcji trygonometrycznych
- Szereg ten jest równy sumie algebraicznej [[Granica|granic]] funkcji w dowolnym punkcie
- Dla funkcji ciągłych jest on jej równy.
# Wzór
$$
\frac{{f(x^-) + f(x^+)}}{2} = \frac{a_{0}}{2} + \sum^{\infty}_{n=1}a_n \cos(nx) +b_{n}\sin(nx)
$$
$$
a_{0} = \int_{0}^{2\pi}f(x)dx
$$
$$
a_{n} = \int_{0}^{2\pi} f(x)\cos(nx) dx
$$
$$
b_{n} = \int_{0}^{2\pi} f(x)\sin(nx)dx
$$
