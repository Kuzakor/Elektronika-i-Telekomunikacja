---
Czas stworzenia: "2025-09-29"
---
#matematyka #analiza
# Definicja
- Jest to sposób na obliczenie *przybliżenia* dowolnej [[Funkcja|funkcji]] za pomocą [[Wielomian|wielomianu]]  za pomocą [[Pochodne wyższego rzędu|pochodnych wyższego rzędu]] co może ułatwić obliczenia.
- Wyporowadzenie do skumania (!todo)
- Wzór dotyczy przbliżenia zaczynającego się od punktu 0
# Wzór
$$P(x) = f(0) + \frac{df(0)}{dx} \frac{x}{1!} + \frac{d^2f(0)}{dx^2} \frac{x^2}{2!} + \frac{d^3f(0)}{dx^3} \frac{x^3}{3!} + \frac{d^4f(0)}{dx^4} \frac{x^4}{4!} + ... $$
# Przykład na [[Podstawowa trygonometria|trygonometrii]]
$$cos(x)\Rightarrow \frac{d}{dx}cos(x) = -sin(x)\Rightarrow \frac{d^2}{dx^2}cos(x) = -cos(x) \Rightarrow ...$$
$$cos(0) = 1; \space -sin(0) = 0; \space-cos(0) = -1$$
$$cos(x) = 1 + 0 \frac{x}{1!} -1 \frac{x^2}{2!} + ...$$
$$cos(x) = 1 - \frac{x^2 }{2}+ ..$$
# Przykład na [[Funkcja wykładniczna|funkcji wykładniczej]]
$$e^x\Rightarrow \frac{d}{dx}e^x = e^x\Rightarrow \frac{d^2}{dx^2}e^x = e^x\Rightarrow ...$$
$$e^0 =1$$
$$e^x = 1 + 1 \frac{x}{1!} +1\frac{x^2}{2!} +1\frac{x^3}{3!} + 1 \frac{x^4}{4!} + ...$$
$$e^x = 1+x + \frac{x}{2} + \frac{x}{6}+ \frac{x}{24}+...$$


# Opis
! -> [[Silnia|silnia]]
