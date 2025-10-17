---
Czas stworzenia: "2025-10-17"
---
#informatyka #układy_logiczne
# Definicja
- Jest to sposób na algorytmiczną *minimalizację* (uproszczenie) [[Funkcja logiczna|funkcji logicznej]] zapisaną w [[Zupełnie Normalna Postać Sumacyjna (ZNPS)|postaci kanonicznej]] lub [[Zupełnie Normalna Postać Iloczynowa (ZNPI)|parakanonicznej]] - notacja w [[Algebra boole'a|algebrze boole'a]].
- Jeżeli dwa kawałki w danym iloczynie bądz sumie rożnią się tylko jedną zmienną tak że w jednej jest wartość normalna a w drugim [[Bramki logiczne|zanegowana]] to tej zmiennej można się "pozbyć".
# Wzór
- Dla ZNPS $$Ax+A\overline{x} = A$$
- Dla ZNPI$$(A+x)*(A+\overline{x}) = A$$
# Zapis programistyczny
```python
#ZNPS
(A and x) or (A and !x) == A
#ZNPI
(A or x) and (A or !x) == A 
```
