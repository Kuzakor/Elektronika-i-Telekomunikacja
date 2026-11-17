---
Czas stworzenia: "2026-11-12"
---
#Przetwarzanie_sygnałów 
# Definicja
- Twiedzenie to stanowi że jeżeli [[Funkcja|funkcja]] nie zawiera [[Widmo sygnału (dziedzina częstotliwości)|nie zawiera składowych]] o pulsacji większej niż w_max to jest ona *jednoznacznie określpna przez [[Szereg]] jej wartośći*
- [[Pulsacja unormowana (Omega)]]
$$
T = \frac{\pi}{\Omega_{max}}
$$
- Na podstawie tego twierdzenia powstaje wzór na rekonstrukcję funkcji czasu ciągłego na podstawie jej [[Próbkowanie|próbek]]
- [[Funkcja sinc]]
$$
f(x) = \sum_{k \in Z}
f(k\cdot T) \cdot\text{sinc}\left( \frac{x}{T} -k \right)$$