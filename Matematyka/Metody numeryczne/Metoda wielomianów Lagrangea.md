---
Czas stworzenia: "2026-03-19"
---
#matematyka #metody_numeryczne
# Definicja
- Jest to metoda aproksymacji funkcji na podstawie przyjętych punktów
- Powiązana z [[Interpolacja wzorami Newtona|interpolacją Newtona]]
- Podobna do [[Metoda najmniejszych kwadratów|metody najmniejszych kwadratów]] jako metoda aproksymacji
# Wzór
$$
P(x) = \sum^n_{i=0} y_{i}L_{i}(x)
$$
gdzie
$$
L_{i}(x) = \prod^n_{j=0,j\neq i} \frac{{x-x_{j}}}{x_i-x_{j}}
$$
