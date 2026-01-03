---
Czas stworzenia: "2025-09-22"
---
#matematyka #algebra_liniowa
# Definicja
Mnożenie czyli kompozycja macierzy to [[Macierz|wykonywanie przekrztałceń]] jeden po drugim. Wynikiem tego jest macierz która by przeniosła nas do punktu końcowego od razu.
#### WAŻNE: Kolejność wykonywania przekrztałceń ma znaczenie. Kolejność jest od PRAWEJ DO LEWEJ -> MNOŻENIE NIE JEST PRZEMIENNE.
# Wzór
$$\begin{bmatrix} a & c \\ b & d \end{bmatrix} \begin{bmatrix} e & g \\ f & h \end{bmatrix} = \begin{bmatrix}  &  \\  &  \end{bmatrix}$$
1. Gdzie idzie i-hat (ef)? Wynik to będzie pierwsza kolumna.
$$\begin{bmatrix} a & c \\ b & d \end{bmatrix} \begin{bmatrix} e \\ f  \end{bmatrix} = e \begin{bmatrix} a \\ b  \end{bmatrix} + f \begin{bmatrix} c \\ d  \end{bmatrix} = \begin{bmatrix} ea + fc \\ eb +fd  \end{bmatrix}$$
2. Gdzie idzie j-hat (gh)? Wynik to będzie druga kolumna.
$$\begin{bmatrix} a & c \\ b & d \end{bmatrix} \begin{bmatrix} g \\ h  \end{bmatrix} = g \begin{bmatrix} a \\ b  \end{bmatrix} + h \begin{bmatrix} c \\ d  \end{bmatrix} = \begin{bmatrix} ga + hc \\ gb +gd  \end{bmatrix}$$
3. Ostateczny wynik:
$$\begin{bmatrix} a & c \\ b & d \end{bmatrix} \begin{bmatrix} e & g \\ f & h \end{bmatrix} = \begin{bmatrix} ea+fc & ga+hc \\ eb+fd & gb+gd \end{bmatrix}$$
# Opis
- Przekrztałcamy  [[Podstawa systemu koordynatów|i-hat i j-hat]]. Aby to zrobić używamy [[Macierz|mnożenia matrycy i wektora]]. 
- Alternatywnie możemy zapisać jedną macierz po lewej a drugą u góry tworzać tabele. Poszczególne *komórki* nowej macierzy bedą mnożeniem i dodawaniem odpowiadającychk kolumn.