---
Czas stworzenia: "2025-11-18"
---
#matematyka #algebra_liniowa 
# Definicja
- Jeżeli równanie opiera się na [[Liczby zespolone|liczbach zespolonych]] to doprawadzamy do postaci która nam odpowiada.  Do wyboru mamy:
	- [[Postać wykładnicza liczb zespolonych]]
	- [[Postać algebraiczna liczb zespolonych]]
	- [[Postać trygonometryczna liczb zespolonych]]
# Przykład
$$
(\overline{z})^4 = -9|z^2|
$$
- Mamy do czynienia zarówno z [[Moduł liczby zespolonej|modułem]] jak i z [[Sprzężenie liczby zespolonej|sprzeżeniem]].
- Zamieniamy na postać wykładniczą.
$$
niech \space z=re^{i\phi}; \space r=|z|
$$
$$
(re^{-i\phi})^4 = -9r^2
$$
$$
r^4 *e^{-4i\phi} = r^2*9e^{i\pi}
$$
- Zarówno r jak i wykładniki muszą być identyczne
$$
r^4 = 9r^2 \land-4\phi = \pi+2k\pi,\space k\in Z
$$
$$
r = 0 \lor r=3 \land \phi=-\frac{\pi}{4} +\frac{k\pi}{2} =\left[ \frac{\pi}{4}, \frac{3\pi}{4}, \frac{5\pi}{4}, \frac{7\pi}{4}, \dots\right]
$$
- Możliwe wartości z to więc
$$
z =0 \lor z =3e^{i\pi/4} \lor z= 3e^{3i\pi/4} \lor\dots
$$
- Przechodzimy na postać trygonometryczną i finalnie algebraiczna aby ograniczyć ilośc rozwiązań do 5
$$
z_{1} = 0
$$
$$
z_{2} =3\left( \cos \frac{\pi}{4} +i\sin \frac{\pi}{4} \right) = 3\left( \frac{\sqrt{ 2 }}{2 } +\frac{i\sqrt{ 2 }}{2} \right)
$$
$$
\dots
$$