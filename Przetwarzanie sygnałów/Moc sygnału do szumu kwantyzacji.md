---
Czas stworzenia: 2026-11-13
---
#Przetwarzanie_sygnałów 
# Definicja
- Miarą zepsucia [[Sygnał|sygnału]] przez [[Błąd (szum) kwantyzacji|szum addytywny]] jest tak zwany SNR (signal to noise ratio), zwykle wyrażany w [[Logarytm|decybelach]]. Dla B-bitowego [[Kwantyzator liniowy|kwantyzera]] wynosi on:
$$
SNR \approx  6,02B + 10,79 - 20\log\left( \frac{2X_{m}}{\sigma_{x}} \right)
$$
- Gdzie sigma^2 jest [[Moc sygnału|mocą sygnału]] poddanegokwantowaniu
- Z tego wzoru wynika że SNR rośnie o około 6dB przy zwiększaniu długości słowa kodowego o 1 [[Bit|bit]]
# Wzór używany w praktyce
$$
SNR \approx 10\log\left( \frac{\sum x_{Q}^2[n]}{\sum(x_{Q(}[n] - x[n])^2} \right)
$$
- S - [[Moc]] [[Kwantyzacja|kwantowanego]] sygnału
- N_q - [[Moc]] szumu
- N - liczba próbek skwantowanego sygnału