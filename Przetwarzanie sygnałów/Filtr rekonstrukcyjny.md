---
Czas stworzenia: "2026-11-12"
---
#Przetwarzanie_sygnałów 
# Definicja
- Kompensacja zniekrztałcenia spowodowanego interpolatorem rzędu zerowego
- [[Próbkowanie]]
- [[Liczby zespolone]]
- [[Postać wykładnicza liczb zespolonych]]
- [[Liczba eulera (e)]]
- [[Widmo sygnału (dziedzina częstotliwości)]]
- [[Filtr pasywny]]
- [[Filtr aktywny]]
# Wzór
$$
H_{r} (\omega) = \begin{cases}
\frac{e^j(\omega T_{p})}{Sa\left( \frac{\omega T_{p}}{2} \right)} \text{ dla } |\omega| < \frac{\omega_{p}}{2}  \\
0 \text{ dla } |\omega|  > \frac{\omega_{p}}{2}
\end{cases}
$$