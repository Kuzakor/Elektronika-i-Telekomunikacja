---
Czas stworzenia: "2025-10-12"
---
#informatyka #układy_logiczne
# Definicja
- Każdą [[Funkcja logiczna|funkcję logiczną]] ([[Bramki logiczne|bramkę logiczną]]) można rozłożyć na czynniki iloczynu według następującej zasady.
- Funkcja logiczna zapisana w ten sposób nazywana jest *postacią parakanoniczną* danej funkcjii logicznej
- Alternatywą jest [[Zupełnie Normalna Postać Sumacyjna (ZNPS)]]
- Wymagana wiedza z [[Algebra boole'a|algebry bool'a]]
# Wzór
$$f
(x_1,x_2,x_3,..x_n) = [x_1+f(1,x_2,x_3...,x_n)] [\overline{x}+f(0,x_2,x_3,...x_n)]$$
# Zapis programistyczny
``` python
(... or ...) and (... or ...) and (... or ...) ...
```
# Zapis w notacji pi
- Jeżeli zapis funkcji jest w postaci tabelki a wejście zapiszemy jako jedna liczba w systemie dziesiętnym (index)
- To ZNPI to indexy wszystkich wyjść równych 0 (licząc od zera)
- [[ZNPS i ZNPI.excalidraw]]