---
Czas stworzenia: "2025-10-12"
---
#informatyka #układy_logiczne
# Definicja
- Każdą [[Funkcja logiczna|funkcję logiczną]] ([[Bramki logiczne|bramkę logiczną]]) można rozłożyć na składniki sumy według następującej zasady.
- [[Funkcja]] logiczna zapisana w ten sposób nazywana jest *postacią kanoniczną* danej funkcjii logicznej
- Alternatywą jest [[Zupełnie Normalna Postać Iloczynowa (ZNPI)]]
- Wymagana wiedza z [[Algebra boole'a|algebry bool'a]]
- [[Implikant i Implicent]]
# Wzór
$$f
(x_1,x_2,x_3,..x_n) = x_1f(1,x_2,x_3...,x_n) +\overline{x_1}f(0,x_2,x_3,...x_n)$$
# Zapis programistyczny
``` python
(... and ...) or (... and ...) or (... and ...) ...
```
#  Zapis w notacji sigma
- Jeżeli zapis funkcji jest w postaci tabelki a wejście zapiszemy jako jedna liczba w systemie dziesiętnym (index)
- To ZNPS to indexy wszystkich wyjść równych 1 (licząc od zera)
- [[ZNPS i ZNPI.excalidraw]]