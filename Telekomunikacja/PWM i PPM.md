---
Czas stworzenia: "2026-11-15"
---
#telekomunikacja
# Definicja
- Jest to jedna z [[Modulacja impulsowa|modulacji impulsowych]]
- [[Sygnał]]
- PWM
	- [[Próbkowanie|Próbki]] sygnału informacyjnego powodują zmiany czasów trwania poszczególnych impulsów *fali nośnej* 
- PPM
	- Położenie impulsu mierzone w stosunku do jego normalnego położenia jest zmieniane w takt sygnału informacyjnego

# Wzór (PPM)
$$
s(t) = \sum^{+\infty}_{n=-\infty} g(t-nT_{s} -k_{p}m(nT_{s}))
$$
- Impulsy muszą być rozłączne
- k_p - *czułość* modulatora

# Odtwarzanie
1. PPM -> PWM
2. [[Całka|Całkowanie PWM]]
3. [[Próbkowanie]] sygnału wyjściowego aby wytworzyć [[PAM]]
4. Demodulacja [[PAM]]