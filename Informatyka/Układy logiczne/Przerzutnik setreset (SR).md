---
Czas stworzenia: "2025-12-02"
---
#informatyka #układy_logiczne
# Definicja
- Jest to [[Przerzutnik|przerzutnik]] z dwubitowym wejściem które opisuje odpowiednio *guzik* set i *guzik* reset.
- [[Układ sekwencyjny]]
- Inne typy przerzutników: [[Przerzutnik data (D)|D]], [[Przerzutnik toggle (T)|T]], [[Przerzutnik setreset+toggle (JK)|JK]].
- Działanie
	- Jeżeli set jest równy 1 to ustawia stan na 1 niezależnie od poprzedniego stanu
	- Jeżeli set jest równy 0, ignoruje ten fakt, nic nie robi
	- Jeżeli reset jest równy 1 to ustawia stan na 0 niezależnie od poprzedniego stanu
	- Jeżeli reset jest równy 0, ignoruje ten fakt, nic nie robi
	- Wejście 11 jest zakazane. reset i set nie mogą być aktywne jednocześnie.