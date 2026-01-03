---
Czas stworzenia: "2025-09-22"
---
#matematyka #algebra_liniowa
# Co i jak
- Przestrzeń (płaszczyznę) można w dowolny sposób przekrztałcać, zmieniać jej zachowanie
- Przekrztałcenie liniowe to takie po którym wszystkie linie w układzie pozostają do siebie równoległe, w równej odległości oraz punkt (0,0) nie został przeniesiony
$$L(\vec{v} + \vec{w}) = L(\vec{v}) + L(\vec{w})$$
$$L(c\vec{v}) = cL(\vec{v})$$
- Takie przekrztałcenie można opisać jako zmianę [[Podstawa systemu koordynatów|podstawowych wektorów i-hat i j-hat]]. Po takiej zmianie każdy [[Wektor|wektor]] w nowej przestrzeni można obliczyć za pomocą [[Kombinacja liniowa i zależność|kombinacji liniowej]].
- Macierz 2x2 to tak naprawdę zapis nowych wartosci i-hat i j-hat. Dla macierzy 3x3 będzie to przekrztałcenie w 3 wymiarach.
- Macierz 3x2 przenosi nas z 2 wymiarów w 3. Natomiast 2x3 z 3 wymiarów w 2. Itd.
- Mnożenie macierzy przez wektor to tak naprawdę obliczenie tego wektora po przemianie opisane tą właśnie macierzą
- Własnośći
	- [[Mnożenie (kompozycja) macierzy]]
	- [[Macierz otrogonalna]]
	- [[Macierz transponowana]]
	- [[Macierz w rozwiązywaniu liniowych układów równań]]
	- [[Rząd macierzy]]
	- [[Odwrotna macierz]]
	- [[Wyznacznik macierzy]]
### Rysunek
[[Macierz jako liniowe przekrztałcenie płaszczyzny.excalidraw]]

# Wzór
- Nowe wartości i-had i j-had:
$$\hat{i} =  \begin{bmatrix} a \\ b \end{bmatrix}$$
$$ \hat{j} =\begin{bmatrix} c \\ d \end{bmatrix}$$
- Ich zapis w postaci macierzy
$$M = \begin{bmatrix} a & c \\ b & d \end{bmatrix}$$
- Mnożenie (zastoswanie) przez wektor
$$\begin{bmatrix} a & c \\ b & d \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix} = x\begin{bmatrix} a \\ b \end{bmatrix} + y\begin{bmatrix} c \\ d \end{bmatrix} = \begin{bmatrix} ax + cx \\ by + dy \end{bmatrix}$$
# Specjalne macierze
- Jednostokowa -> jedynki po przekątnej
- Zerowa -> Same zera
- Trójkątna górna/dolna -> Połowa macierzy to 0
# Opis
Mnożenie to [[Podstawa systemu koordynatów|zapis wektora za pomocą nowych i-hat i j-hat]].