---
Czas stworzenia: "2026-05-07"
---
#obwody #fizyka 
# Definicja
- Metoda wskazowa opiera się w dużej mierze na [[Liczby zespolone|liczbach zespolonych]] oraz[[Impedancja| impendacji]]
- Sluży do wyznaczania [[Natężęnie|prądów]]/[[Napięcie|napięć]] w tak zwanym stanie ustalonym (czyli t->infty, [[Granica]])
- Wymuszenie musi być w postaci [[Funkcje trygonometryczne|sinusa lub cosinusa]]
# Metoda
- Wszystkie sygnały źrodłowe zamieniamy na ich [[Postać wykładnicza liczb zespolonych|postać wykładiczą]]
- Przesunięcie w fazie o 90 stopni - sinus
$$
e(t) = a\cos(\omega t + \phi)
$$
$$
\hat{e}(t) = ae^{i(\omega t + \phi)}
$$
- Zamieniamy [[Elementy liniowe inercyjne|elementy inercyjne]] na ich odpowiednik w bloczach z [[Impedancja|impendacji (metoda wskazowa)]]
- Rozwiązujemy obwód jak [[Metody rozwiązywania układów prądu stałego|obwód prądu stałego]]
- Konwertujemy prąd/napięcie w postaci zespolonej na "normalne" wartości poprzez wzięcie części rzeczwistej
$$
\Re(\hat{i}(t)) = i(t)
$$
$$
$$