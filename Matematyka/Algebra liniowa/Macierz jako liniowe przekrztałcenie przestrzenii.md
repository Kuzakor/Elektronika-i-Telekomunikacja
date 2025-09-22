---
Czas stworzenia: "2025-09-22"
---
#matematyka #algebra_liniowa
# Co i jak
- Przestrzeń (płaszczyznę) można w dowolny sposób przekrztałcać, zmieniać jej zachowanie
- Przekrztałcenie liniowe to takie po którym wszystkie linie w układzie pozostają do siebie równoległe, w równej odległości oraz punkt (0,0) nie został przeniesiony
- Takie przekrztałcenie można opisać jako zmianę [[Podstawa systemu koordynatów|podstawowych wektorów i-hat i j-hat]]. Po takiej zmianie każdy [[Wektor|wektor]] w nowej przestrzeni można obliczyć za pomocą [[Kombinacja liniowa|kombinacjiii liniowej]].
- Macierz 2x2 to tak naprawdę zapis nowych wartosci i-hat i j-hat.
- Mnożenie macierzy przez wektor to tak naprawdę obliczenie tego wektora po przemianie opisane tą właśnie macierzą
### Rysunek
[[Macierz jako liniowe przekrztałcenie przestrzenii.excalidraw]]

# Wzór
- Nowe wartości i-had i j-had:
$$\hat{i} =  \begin{bmatrix} a \\ b \end{bmatrix}$$
$$ \hat{j} =\begin{bmatrix} c \\ d \end{bmatrix}$$
- Ich zapis w postaci macierzy
$$M = \begin{bmatrix} a & c \\ b & d \end{bmatrix}$$
- Mnożenie (zastoswanie) przez wektor
$$\begin{bmatrix} a & c \\ b & d \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix} = x\begin{bmatrix} a \\ b \end{bmatrix} + y\begin{bmatrix} c \\ d \end{bmatrix} = \begin{bmatrix} xa +xc \\ xb +xd \end{bmatrix}$$
# Opis
Mnożenie to [[Podstawa systemu koordynatów|zapis wektora za pomocą nowych i-hat i j-hat]].