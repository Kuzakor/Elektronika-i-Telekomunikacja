---
Czas stworzenia: "2026-03-12"
---
#matematyka #metody_numeryczne
# Definicja
- Metoda ta polega na upraszczaniu danej [[Funkcja|funkcjii]] poprzez *siekanie* jej prostą w okolicach miejsca zerowego.
- Jest to metoda iteracyjna z przybliżonym wynikiem
- Podobne metody: [[Metoda bisekcji]], [[Metoda.stycznych (Newtona)|metoda Newtona]]
- Powiązana z [[Metoda wielomianów Lagrangea|interpolacją Lagrange'a]] jako metoda aproksymacji
# Wzór
$$
x_{k+1} = x_{k} - \frac{{f(x_{k}) (x_{k} - x_{k-1})}}{f(x_{k}) -f(x_{k-1})}
$$