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
- Jest *dualna* czyli
$$
\text{Jeżeli }\space\space x(t) \Leftrightarrow X(\omega) \space\space\text{to} \space\space X(t) \Leftrightarrow 2\pi x(-\omega)
$$
