---
Czas stworzenia: "2026-04-30"
---
#obwody #fizyka 
# Definicja
- Impedancja to uogólnione pojęcie [[Prawo Ohma|rezystancjii]] dwójników. 
- Jest to [[Liczby zespolone|liczba zespolona]] opisująca własnośc dowolnego dwójnika a w sczególności [[Elementy liniowe inercyjne|elementów inercyjnych]]
- Pozwala ona uprościć skomplikowany układ prądu przemiennego z [[Kondensator liniowy|kondesatorami]] lub [[Cewka (induktor) liniowy|cewkami]] na w miarę prosty układ prądu stałego gdzie elementy te są zastępywane na "semi-rezystory" o konkretnej impndancji zachowujące się zgodnie z prawem Ohma
- Znacząco ułatwia to obliczenia, sprowadzając układ do [[Źrodło napięciowe|źródeł napięciowych]], [[Idealne źródło prądowe|źródeł prądowych]],[[Rezystor|rezystorów]] oraz [[Wzmaczniacz operacyjny|wzmacniaczy]] 
- W takim układzie działają wszystkie prawa [[Metody rozwiązywania układów prądu stałego|znane z prądu stałego]] ([[Napięciowe prawo Kirhoffa]], [[Prądowe prawo Kirhoffa]])
- Impedanja wynika z [[Transformata Laplaca|tranformaty laplaca]]
- j to alternatywne oznaczenie [[Jednostka urojona (i)|jednostkii urojonej i]] używanej przez inżynierów aby nie mylić z [[Natężęnie|prądem]]
- W domyśle chodzi o impedancję dotyczącą metody wskazowej
# Wzór ([[Metoda operatorowa]])
$$
Z_{C} (s) = \frac{U_{C}(s)}{I_{C}(s)} = \frac{1}{sC}
$$
$$
Z_{L}(s) = \frac{U_{L}(s)}{I_{L}(s)} = sL
$$
# Wzór ([[Metoda wskazowa]])
$$
Z_C(\omega j) =\frac{1}{C\omega j}
$$
$$
Z_{L}(\omega j) = L\omega j
$$