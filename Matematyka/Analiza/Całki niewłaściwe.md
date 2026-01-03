---
Czas stworzenia: "2025-12-03"
---
#matematyka  #analiza
# Definicja
- Są to [[Całka|całki oznaczone]] zdefiniowane na przedziale gdzie funkcja ma nieciągłość lub takie, które dążą do nieskończonośći z którejść strony.
- Do ich obliczania korzystamy z [[Granica|granic]].
# Całki funkcji "dziurawych"
- Jeżeli funkcja w podanym przedziale zawiera wartość x która jest wyrzucona z [[Dziedzina|dziedziny]] to dzielimy ją na 2 np.
$$
\int^2_{-2} \frac{1}{x^2} dx = \begin{Bmatrix}
x \neq 0 \\
D= x \in R - 0
\end{Bmatrix} = \int_{-2}^0 \frac{1}{x^2}dx + \int_0^2 \frac{1}{x^2}dx
$$
- Oraz liczymy je osobno z użyciem granic
$$
\lim_{ t \to 0^-} \int_{t}^2 \frac{1}{x^2}dx = \infty  
$$
- Jeżeli wynikiem jest nieskończoność całka jest *rozbieżna* więc nie da się jej obliczyć.
- Jeżeli wynikiem jest liczba to wstawiamy powyżej
# Całki funkcji do nieskończonośći
- Dobieramy sobie dowolną pasującą nam liczbę i dzielimy całkę na 2 jeżeli jest to konieczne.
$$
\int^{\infty} _{-\infty} f(x)dx= \int _{-\infty}^3f(x)dx + \int_{3}^{\infty} f(x)dx
$$
- Całki te obliczamy tak samo jak powyżej -> za pomocą granicy.