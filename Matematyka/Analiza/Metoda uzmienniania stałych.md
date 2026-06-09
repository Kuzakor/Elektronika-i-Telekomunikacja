---
Czas stworzenia: "2026-06-09"
---
#matematyka #analiza 
# Definicja
- Jest to metoda rozwiązywania [[Równanie różniczkowe n-tego rzędu|niejednorodnego równania różniczkowego n-tego rzędu]] (CSRN), która działa zawsze. 
- Musimy najpierw poznać *układ fundamentalny* czyli funkcje spełniające [[Równanie różniczkowe jednorodne o stałych wspołczynnikach|równanie jednorodne o stałych wspołczynnikach]]
- Następnie rozwiązujemy następujący [[Macierz w rozwiązywaniu liniowych układów równań|układ równanń]]
- Jest to metoda złożona obliczeniowo - używa się jej tylko jeśli nie można skorzystać z [[Metoda przewdywań|metody przewidywań]] czyli przy np [[Logarytm|logarytmach]] czy [[Funkcja|funkcjach]] [[Funkcje cyklometryczne|cyklomentrycznych]]
# Wzór/Przykład
$$
\begin{bmatrix} y_{1}(x) & y_{2}(x) & y_{3}(x)\\  y_{1}'(x) & y_{2}'(x) & y_{3}'(x)\\  y_{1}''(x) & y_{2}''(x) & y_{3}''(x)\end{bmatrix}\begin{bmatrix} c_{1}'(x) \\ c_{2}'(x)  \\ c_{3}'(x) \end{bmatrix} = \begin{bmatrix} 0 \\ 0 \\ f(x) \end{bmatrix}$$

$$
y_{s}(x) = c_{1}(x)y_{1}(x) + c_{2}(x)y_{2}(x) + c_{3}(x)y_{3}(x)
$$