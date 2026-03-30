---
Czas stworzenia: "2025-10-13"
---
#informatyka #układy_logiczne
# Definicja
Jest to [[Układ sekwencyjny|układ sekwencyjny]] w którym wyjście zależy tylko i wyłącznie od *stanu*
- Jest to alternatywa dla [[Model Mealy'ego|modelu Mealy'ego]].
- Wykorzystuje [[Przerzutnik|przerzutniki]] do przechowywania stanu.
- Różni się od [[Układ kombinacyjny|układu kombinacyjnego]] tym, że posiada pamięć stanu.
# Wzór
$$q_{k+1} = \delta(q_l, x_k)$$
$$y_k = \lambda(q_k)$$