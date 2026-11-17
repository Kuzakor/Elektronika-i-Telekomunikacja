---
Czas stworzenia: "2026-11-12"
---
#Przetwarzanie_sygnałów 
# Definicja
- [[Próbkowanie]]
- Jeżeli [[Sygnał]] x(t) posiada ograniczoną pasmowo  [[Transformata FT|transformatę FT]] to znaczy:
$$
|X(\omega)| = 0 \text{ dla }|\omega| \geq 2\pi f_{max} 
$$
- To [[Sygnał]] ten może zostać *bezblędnie i jednoznacznie zrekonstruoowany* na podstawie ciągu równomiernie rozłożonych próbek 
$$
x[n] = x(n\cdot T_{p})
$$
- jeżeli szybkość próbkowania
$$
f_{p} = \frac{1}{T_{p}} \geq 2f_{max}
$$
- Szybkość ta jest zwana *Szybkoscią Nyquista*
# Skutki niestosowania
- [[Aliasing]]