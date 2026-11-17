---
Czas stworzenia: "2026-11-14"
---
#telekomunikacja
# Definicja
- Jest to jedna z [[Modulacja impulsowa|modulacji impulsowych]] oprata na [[AM - modulacja amplitudy|AM]] tylko że na [[Próbkowanie|dyskretnym]] czasie.
- Etapy generowania
	1. [[Próbkowanie]] z [[Okres i częstotliwość|okresem]] T
	2. Wydłużenie czasu trwania każdej próbki do pewnej stałej wartości T
	3. Te dwie operacje nazywają się *[[Próbkowanie]] z zapamiętywaniem (sample and hold)*
- Można to bezpośrednio przesyłać [[Kanał telekomunikacyjny|kanałem symetrycznym]]
- Nie można ich transmitować za pomocą [[Elektromagnetyczna fala płaska|fali elektromagnetycznej]]
## Odtwarzanie
1. Przepuszczenie przez [[Filtr pasywny|filtr]] [[Podział filtrów pasywnych|dolnoprzepustowy]]
2. Obróbka sygnału w *układzie wyrównującym*
# Wzór
$$
s(t) = \sum^{\infty}_{n = -\infty} m(nT_{s})h(t-nT_{s})
$$