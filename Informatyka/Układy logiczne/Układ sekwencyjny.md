---
Czas stworzenia: "2025-10-07"
---
#informatyka #układy_logiczne
# Definicja
- Układy sekwencyjne działają w podobny spsób co [[Układ kombinacyjny|układy kombinacyjne]] z taką różnicą, że zawierają jeszcze zmienny stan od którego zależy wynik.
``` c++
układ.stan = 'alpha'
switch układ.stan {
	case 'alpha':
		11 -> 1
		01 -> 0
		...
	case 'beta':
		11 -> 0
		01 -> 1
	etc.
}
```
- Oznacza to że to samo wejście nie zawsze oznacza ten sam wynik.
- Układy sekwencyjne można podzielić na
	- *Synchroniczne* - sprawdzające wejścia co tyknięcie zegara i przeprowadzanie obliczeń (można na bazie tego wyznaczyć wykres wyjścia mając wykresy wejścia)
	- *Asynchorniczne*
- Oraz niezależnie od powyższych podziałów na różne modele
	- [[Model Mealy'ego]]
	- [[Model Moore'a]]
- Układy te można opisywać za pomocą tabelki i/lub grafu.
- Jest to rodzaj [[Funkcja logiczna|funkcjii logicznej]]
### Przykład
[[Układ sekwencyjny.excalidraw]]