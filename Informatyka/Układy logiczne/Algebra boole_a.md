---
Czas stworzenia: "2025-10-10"
---
#informatyka #układy_logiczne
# Definicja
- [[Bramki logiczne]] można również przedstawić w postaci działań arytmetycznych.
	1. Bramka *OR* to suma (tak samo jak w matematyce)
	2. Bramka *AND* to iloczyn (część wspólna)
	3. Negacja zapisana jest w postaci kreski nad daną zmienną
	4. Bramka *XOR* zapisana jest w postaci plusa w kółku
- Za pomocą tego zapisu można opisać dowolnoą [[Funkcja logiczna|funkcję logiczną]]
- Jest podstawą [[Układ kombinacyjny|układów kombinacyjnych]] i [[Układ sekwencyjny|układów sekwencyjnych]]
- Operuje na [[Bit|bitach]] w [[System binarny|systemie binarnym]]
- Za pomocą poniższych tożsamości można uprościć daną funkcję co upraszcza jej analizę
# Tożsamości
- Inne
$$x+1=1$$
$$x*0 = 0$$
$$x+x=x$$
$$x*x = x$$
$$\overline{\overline{x}} = x$$
$$x + \overline{x}y = x+y$$
- Prawo de Morgana$$\overline{xy} = 
\overline{x} + \overline{y}$$
$$\overline{x+y} = \overline{x}\space\overline{y}$$
- Reguła pochłaniania$$x+xy=x$$$$x(x+y) = x$$
- [[Reguły sklejania]]
$$xy+x\overline{y} =x$$
$$(x+y)(x+\overline{y}) =x$$