---
Czas stworzenia: "2026-11-13"
---
#Przetwarzanie_sygnałów 
# Definicja
- Bład [[Kwantyzacja|kwantyzacji]] czyli różnica między oryginalnym [[Sygnał|sygnałem]] a skwantowanym ma unikalne właściwości.
- Wygląda on bardzo często jak losowy szum
- Nie ma korelacji z oryginalnym sygnałem
- [[Ciąg]] błędów ma równomierny [[Rozkład prawdopodobieństwa|rozkład prawdopodobieństwa]] w całym zakresie wartości błędów kwantyzacji
- Kolejne wartości błedu kwantyzacji są ze sobą *nieskorelowane*
- Jeżeli [[Próbkowanie|próbka]] sygnału x[n] nie znajduje się w obszarze nasycenia charakterystyki kwantyzatora, to błąd kwantyzacji mieści się w przedziale
$$
e[n] \in \left[ -\frac{\Delta}{2} , \frac{\Delta}{2} \right)
$$
- *Jeżeli wartości próbek się bardzo zmieniają i krok kwantyzacji jest dostatecznie mały to charakteryzacja szumu kwantyzacji jest zbliżona do charakterystyki szumu o równomiernym rozkładzie prawdopodobieństwa.*