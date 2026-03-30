---
Czas stworzenia: "2025-10-13"
---
#informatyka #układy_logiczne
# Definicja
Jest to [[Układ sekwencyjny|układ sekwencyjny]] w którym wynikowy stan i wyjście zależy zarówno od *stanu* jak i *wejścia*.
- Jest to alternatywa dla [[Model Moore'a|modelu Moore'a]].
- Wykorzystuje [[Przerzutnik|przerzutniki]] do przechowywania stanu.
- Różni się od [[Układ kombinacyjny|układu kombinacyjnego]] tym, że posiada pamięć stanu.
# Wzór
$$q_{k+1} = \delta(q_k, x_k)$$
$$y_k = \lambda(q_k, x_k)$$