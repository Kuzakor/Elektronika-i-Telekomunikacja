---
Czas stworzenia: "2025-09-25"
---
#matematyka #algebra_liniowa
# Co i jak
- Dowolną funkcję można traktować jako [[Wektor|wektor]] o nieskończonej ilości współrzednych (z racji że mamy nieskończoną ilość wejść i wyjść). Więc ma "nieskończenie wiele" wymiarów.
- Przekrztałcenia  liniowe funkcji takie jak [[Pochodna|pochodna]] czy [[Całka|całka]] można traktować jako [[Macierz jako liniowe przekrztałcenie|przekrztałcenie liniowe w algebrze liniowej]]
- Jest tak dlatego że fukncje są [[Przestzeń wektorowa|przestrzenią wektorową]].
# Przykład: pochodna [[Wielomian|wielomianu]] jako macierz
- Podstawowe funkcje jako [[Podstawa systemu koordynatów|i-hat i i-hat]]
$$1, x,x^{2,}x^3,..$$
- Nasza fukcja
$$f(x) = 1x^3+5x^{2}+4x+5$$
- Zapisana jako wektor. (Wszystkie wyższe potęgi mają skalar = 0)
$$\begin{bmatrix} 5 \\4 \\ 5 \\ 1 \\ 0  \\ 0 \\ ...\end{bmatrix}$$
- Pochodna wielomianu jako macierz
$$\frac{d}{dx}= \begin{bmatrix} 0 & 1 & 0 & 0 & ... \\ 0 & 0 & 2 & 0 & ... \\ 0 & 0  & 0 & 3 & ...\\ 0 & 0 & 0 &0 & ... \\ ... & ... & ... & ... & ...\end{bmatrix}$$
- [[Macierz jako liniowe przekrztałcenie|stosujemy]]
$$\frac{df(x)}{dx} \Rightarrow\begin{bmatrix} 0 & 1 & 0 & 0 & ... \\ 0 & 0 & 2 & 0 & ... \\ 0 & 0  & 0 & 3 & ...\\ 0 & 0 & 0 &0 & ... \\ ... & ... & ... & ... & ...\end{bmatrix}\begin{bmatrix} 5 \\4 \\ 5 \\ 1  \\ ...\end{bmatrix} = \begin{bmatrix} 0* 5 \\ 1 * 4 \\ 2*5 \\ 3*1 \\  ...\end{bmatrix} = \begin{bmatrix} 0 \\4 \\ 10 \\ 3 \\ ...\end{bmatrix} \Rightarrow \frac{df(x)}{dx} = 3x^{2}+ 10x +4$$

