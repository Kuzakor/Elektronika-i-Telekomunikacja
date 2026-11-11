---
Czas stworzenia: "2026-11-10"
---
#obwody 
# Definicja
- Pozwala to uprościć *nieliniowy* [[Tranzystor MOS]] w obwodzie [[Metody rozwiązywania układów prądu zmiennego|prądu zmiennego]] do [[Sterowane źródła|sterowanego źródła prądowego sterowanego napięciem]] w zwykly obwód liniowy [[Metody rozwiązywania układów prądu stałego|prądu stałego]]
- Model ten można stosować jedynie do wyliczania *składowej zmiennej* rozwiązania, gdyż aby wyprowadzić ten model musimy znać już *stałoprądowy punkt pracy*
- Sterowane źródło prądowe ma wzór
$$
i_{d}[A] = g_{m}v_{gs}
$$
- Gdzie g_m to *transkoduktancja* wyrażana wzorem ([[Pochodna cząstkowa]])
$$
g_{m} = \frac{\partial I_{d}}{\partial U_{gs}} (U_{gs} \text{ prądu stałego})
$$
- A v_gs to *amplituda* zmian [[Sygnał|sygnału]]