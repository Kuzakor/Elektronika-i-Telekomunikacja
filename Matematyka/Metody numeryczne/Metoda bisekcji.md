---
Czas stworzenia: "2026-03-12"
---
#matematyka #metody_numeryczne
# Definicja
- Metoda bisecji to iteracyjna (przybliżona) znajdowania miejsca zerowego [[Funkcja|funkcji]].
- Zgodnie z nazwą polega na *dzieleniu na pół* przedziału w którym może znajdować sie [[Funkcja]].
# Kod/Wzór
```python
def f: 
	pass
	
a = a_0 # Końce przedziału startowego
b = b_0 
x = 0
while abs(f(x)) > epsilon:
	x = (a+b)/2
	if f(a) * f(x) < 0:
		a = a
		b = x
	else 
		a = x
		b = b

print(x)
```
