---
Czas stworzenia: "2026-10-13"
---
#Przetwarzanie_sygnałów 
# Definicja
- Rozwinięcie idei [[Szereg Fouriera|szeregu fouriera]] [[Funkcja|funkcji]] do analizy [[Sygnał|sygnału]]
- Wynikiem jest ciągła [[Funkcja zespolona|funkcja zespolona]] w tak zwanej [[Widmo sygnału (dziedzina częstotliwości)|dziedzinie częstotliwośći]] zwana też widmem sygnału
- [[Całka]]
- [[Całkowanie częściami]]
- [[Jednostka urojona (i)]]
- [[Wartość bezwzględna]]
- [[Widmo sygnału (dziedzina częstotliwości)]]
- [[Widmo.excalidraw]]
- [[Funkcje trygonometryczne]]
- [[Liczby zespolone]]
# Gotowce
- [[Transformata FT dla sygnału prostkątnego]]
# Wzór
### Równanie analizy
$$
X(\omega) = \int^{+\infty}_{-\infty} x(t)e^{-j\omega t} dt 
$$
### Równanie syntezy
$$
x(t) = \frac{1}{2\pi} \int^{+\infty}_{-\infty} X(\omega)e^{j\omega t} d\omega 
$$
# Właściwości
- Transformata ta jest *liniowa* co znaczy że można wynik jak i f. pierwotną dowolnie mnożyć przez stałe i dodawać
- ### Dualnoość
$$
\text{Jeżeli }\space\space x(t) \Leftrightarrow X(\omega) \space\space\text{to} \space\space X(t) \Leftrightarrow 2\pi x(-\omega)
$$
### [[Splot]]
### Przeskalowanie
$$
x(at) \Leftrightarrow \frac{1}{|a|}  X\left( \frac{\omega}{a} \right)
$$
### Odwrócenie w czasie
$$
x(-t) \Leftrightarrow X(-\omega)
$$
### Iloczyn sygnałów
$$
x(t) y(t) \Leftrightarrow \frac{1}{2\pi} X(\omega) * Y(\omega)
$$
###  Przesunięcie w dziedzinie czasu
$$
x(t-t_{0}) \Leftrightarrow e^{-j\omega t_{0}}X(\omega)
$$
### Przesunięcie w dziedzinie częstotliwośći
$$
x(t) e^{\pm j\omega_{0}t} \Leftrightarrow X(\omega \pm \omega_{0})
$$
### Modulacja rzeczywista
$$
x(t)\cos(\omega _{0}t) \Leftrightarrow \frac{1}{2}[X(\omega-\omega_{0}) + X(\omega+\omega_{0})]
$$
$$
x(t)\cos(\omega _{0}t) \Leftrightarrow \frac{1}{2}j[X(\omega+\omega_{0}) - X(\omega-\omega_{0})]
$$
### Transformata [[Pochodna|pochodnej]]
$$
\frac{dx(t)}{dt} \Leftrightarrow j\omega X(w)
$$
### Transformata całki ([[Delta Diraca]])
$$
\int_{-\infty}^{t}x(\tau)d\tau \Leftrightarrow \frac{1}{j\omega}X(\omega) +\pi X(0)\delta(\omega)
$$