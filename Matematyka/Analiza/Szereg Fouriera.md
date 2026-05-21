---
Czas stworzenia: "2026-05-18"
---
#matematyka #analiza 
# Definicja
- Jest to [[Szereg|szereg]] pozwalający przyblizyć [[Funkcja|funkcję]] za pomocą [[Funkcje trygonometryczne|funkcjii trygonometrycznych]]. 
- Funkcja która przybliżamy musi być [[Okresowość funkcji|okresowa]] a najlepiej z okresem 2pi
- Poniższe [[Całka|całki]] muszą być po całym okresie, niekoniecznie 0 - 2pi
# Wzór
$$
f(x) \approx \frac{a_{0}}{2} + \sum^{\infty}_{n=1}a_n \cos(nx) +b_{n}\sin(nx)
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
