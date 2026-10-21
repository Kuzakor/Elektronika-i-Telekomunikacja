---
Czas stworzenia: "2026-10-15"
---
#matematyka #analiza 
# Definicja
- Splot [[Funkcja|funkcji]] to działanie na dwóch funkcjach zwracające inną funkcję
- Operacja ta *filtruje* jedną funkcję ([[Sygnał]]) przez drugą
- Wynikową funkcją jest wykres pola pod krzywą części wspólnej obu funkcji przesuwając jedną z nich po osi czasu ([[Dziedzina]])
- [[Całka]]
# Wzór
$$
f(t) * g(t) =\int_{-\infty}^{\infty} f(t-\tau)g(\tau) d\tau
$$
# Właściwości 
1. Przemienne
2. Liniowe
3. [[Delta Diraca]]
$$
f(t) * \delta (t) = f(t)
$$
4. [[Pochodna]]
$$
(f(t) *g(t))' = f'(t) *g(t) = f(t) * g'(t)
$$
5. Wynik spolotu jest dwa razy dłuższy niż funkcje go tworzące (w przpadku funkcji dyskretnych o jedną jednostkę mniej)
6. [[Transformata FT]] splotu to to samo co mnożenie osobnych transformat.
7. [[Splot kołowy]]
