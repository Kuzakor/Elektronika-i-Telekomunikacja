---
Czas stworzenia: "2026-10-22"
---
#obwody 
# Definicja
- Tranzystor mosfet to swoisty *przełącznik* przewodzący [[Natężęnie|prąd]] jeśli [[Napięcie|napięcie]] bramki (G) jest większe niż *Threshold* (U_T). 
- Prąd płynie z *drenu* (D) do *źródła* (S)
- Sama bramka nie jest podłączona do tranzystora (robi to "zdalnie") więc niie płynie przez nią żaden prąd. 
- Prąd drenu (czyli jaki płynie przez tranzystor) zależy od poziomu nasyciania tranzysotra
	- Tranzystor nienasycony -> prąd rośnie w raz z napięciem bramki
	- Tranzystor nasycony -> prąd stablilzuje się do stałego poziomu
- I jest opisany następującymi wzorami
# Wzór
### Nienasycony (T)
$$
I_{D} = \beta\left[ (U_{GS} - U_{T})U_{DS} - \frac{U^2_{DS}}{2} \right]
$$
### Nasycony (P)
$$
I_{D} = \frac{\beta(U_{GS} - U_{T})^2}{2}
$$
