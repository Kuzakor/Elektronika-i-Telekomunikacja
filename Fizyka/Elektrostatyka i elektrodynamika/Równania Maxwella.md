---
Czas stworzenia: "2026-06-09"
---
#fizyka #elektrostatyka #magnetyzm 
# Definicja
 - Równania maxwella są **najważniejsze**!!!!
 - Bazują one na kolejno
	 - [[Prawo Gaussa]]
	 - [[Prawo Ampera]]
	 - [[Prawo Faradaya]]
- Są one zawsze spełnione i łączą one z sobą [[Pole elektryczne]] i [[Prawo Biota-Savarta|Pole magnetyczne]]
- [[Indukcja pola elektrycznego]] (D)
- [[Dywergencja]]
- [[Rotacja]]
- [[Pochodna cząstkowa]]
- [[Pochodna]]
- [[Całka]]
- [[Całka powierzchniowa skierowana]]
- [[Całki krzywoliniowe skierowane po krzywej zamkniętej]]
- [[Podsumowanie pole i indukcja]]
# Równania
### Postać lokalna
$$
div \vec{D} = \rho_{v}
$$
$$
div \vec{B} = 0
$$
$$
rot \vec{E} = -\frac{\partial\vec{B}}{\partial t}
$$
$$
rot \vec{H} = \vec{J} + \frac{\partial \vec{D}}{\partial t}
$$
### Postać globalna
$$
\iint_{S} \vec{D} \cdot d \vec{s} = \iiint_{V} \rho_{v} dV
$$
$$
\iint_{S} \vec{B} \cdot d \vec{s} = 0 
$$

$$
\oint_{L} \vec{E} \cdot d \vec{l} = -\iint_{S} \frac{\partial\vec{B}}{\partial t} \cdot d \vec{s}
$$
$$
\oint_{L} \vec{H} \cdot d \vec{l}  = \vec{J} +\frac{\partial \vec{D}}{\partial t}
$$