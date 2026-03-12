---
Czas stworzenia: 2026-03-12
---
#matematyka #metody_numeryczne
# Definicja
- Jest to metoda iteracyjne rozwiązywania [[Macierz w rozwiązywaniu liniowych układów równań|równań liniowych]].
- Bardzo podobna do [[Metoda Jackobiego|metody jackobiego]]
- Wynik nie jest dokładny, jest przybliżony
# Wzór
$$
Ax = b
$$
$$
x_{k+1} = -A_{D}^{-1} A_{L}x_{x+1} -A_{D}^{-1} A_{U} x_{k} +A_{D}^{-1}b 
$$
- Gdzie A_d A_l i A_U to odpowiednio macierz po przekątnej, trójkątna dolna, trójkątna górna powstałych z macierzy A.

