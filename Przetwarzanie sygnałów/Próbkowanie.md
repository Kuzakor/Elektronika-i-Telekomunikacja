---
Czas stworzenia: "2026-10-28"
---
#Przetwarzanie_sygnałów 
# Definicja
- Próbkowanie to zamiana [[Sygnał|sygnału]] [[Funkcja|ciągłego]] na sygnal dyskretno-czasowy
$$
x(t) \implies x[n]
$$
- Najczęściej próbkowanie jest *równomierne* czyli próbki są pozyskiwane w równych odstępach czasu
- [[Filtr rekonstrukcyjny]]

# Muplikatywny model próbkowania
## [[Dziedzina]] czasu
- [[Sygnał]] próbkujący "grzebień"
- [[Delta Diraca]]
- [[Granica]]
- [[Całka]]
$$
s(t) = \sum^{\infty}_{k=-\infty} \delta(t - kT_{p}) 
$$
$$
x[n] = \lim_{ a \to \infty } \int^{nT_{p} +a}_{t =nTp-a} x(t)s(t)dt = x(nT_{p}) 
$$
## [[Widmo sygnału (dziedzina częstotliwości)]]
- [[Postać wykładnicza liczb zespolonych]]
- [[Liczba eulera (e)]]
- [[Dystrybuanta]] grzebieniowa
$$
s(t) = \sum^{\infty}_{k=-\infty} \delta(t - kT_{p}) 
$$
- [[Transformata FT]] dystrybuanty grzebieniowej s(t):
$$
S(\omega) = \sum^{\infty}_{k=-\infty} e^{-j\omega kT_{p}}
$$
- *Suma nieskończenie wielu [[Liczby zespolone|zespolonych]] sygnałów [[Funkcje trygonometryczne|harmonicznych]]*
# Szybkość próbkowania
- [[Szybkość Nyquista (tw. o próbkowaniu)]]
- Szybkość próbkowania to liczba próbek zarejestrowanych w ciągu jednej sekundy
$$
f_{s} = \frac{1}{T_{p}}
$$
- Jest to niejako odpowiednik *częstotliwości*
# Odtwarzanie sygnału
- Operacja próbkowania jest *jednoznaczna* ale odtworzenie tego sygnału może być *niejednoznaczne* 
- [[Twiedzenie Shannona - próbkowanie]]
#### Sposoby na rekonstrukcję sygnału
- [[Rekonstrukcja schodkowa (ZOH)]]
- [[Rekonstrukcja liniowa (FOH)]]
- [[Rekonstrukcja impulsu prostokątnego]]