---
Czas stworzenia: "2025-09-23"
---
#matematyka #algebra_liniowa
# Co i jak
- Wynik iloczynu wektorowego to pole równoległoboku między nimi. Jest on negatywny gdy kierunek z pierwszego do drugiego wektora jest *zgodny z ruchem zegara*. A pozytywny gdy porusza się *przeciwnie do ruchu zegara*.
-  Aby to obliczyć [[Macierz jako liniowe przekrztałcenie|przekrztałcamy płaszczyznę]] taką macierzą aby nasze wektory znajdowały się w tym samym miejscu co [[Podstawa systemu koordynatów|i-hat i j-hat]]. Dzięki temu pojedynczy kwadrat o polu 1 który się między nimi znajdował zamienia się w równoległobok o polu tylu razy większym ile wynosi [[Wyznacznik macierzy| wyznacznik tej macierzy]]
#### WAŻNE: Rezultat to wektor prostopadły do pierwszych dwóch (następny wymiar) o obliczonej długości (równy polu tego równoległoboku) a znak decyduje o jego zwrocie. Zasada prawej ręki.
### Rysunek
[[Iloczyn wektorowy.excalidraw]]

# Wzór
- Długość otrzymanego wektora
$$\begin{bmatrix} a \\ b \end{bmatrix} \times \begin{bmatrix}c \\ d \end{bmatrix} = d(\begin{bmatrix}a & c \\ b & d \end{bmatrix}) = ad -bc$$
