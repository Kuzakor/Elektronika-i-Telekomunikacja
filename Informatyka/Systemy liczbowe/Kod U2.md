---
Czas stworzenia: "2025-10-06"
---
#informatyka #systemy_liczbowe
# Definicja
- Kod U2 to *standard* kodowania liczb w [[System binarny|systemie binarnym]] przy [[Podstawowe działania na liczbach innych systemów liczbowych|wykonywaniu działań arytmetycznych]].
- Jest on ulepszoną wersją [[Kod U1|kodu U1]], który jest rzadko używany
- Liczbę zapisujemy zawsze na osmiu [[Bit|bitach]] (1 bajt)
- Zapis liczb dodatnich jest identyczny jak w przypadku [[Znak moduł systemu binarnego (ZM)|ZM]].
- Alternatywy: [[Znak moduł systemu binarnego (ZM)|ZM]]
$$(01101)_{ZM} = (00001101)_{U2}=+13$$
- Zapis liczb ujemnych jest bardziej skomplikowany
	- Jest to [[Bramki logiczne|negacja]] wszystkich bitów
	$$001101 \rightarrow 110010$$
	- Oraz dodanie liczby 1
	$$110010 \rightarrow 110011$$
	$$(11011)_{U2} = -13$$

- W zapisie tym podczas [[Podstawowe działania na liczbach innych systemów liczbowych|dodawania]] (dodanie liczby ujemnej jest tożsame z odejmowaniem) ignorujemy wszystko co wyjdzie "poza" naszą tabelke w obliczeniach pisemnych.
- Wynik również jest w U2