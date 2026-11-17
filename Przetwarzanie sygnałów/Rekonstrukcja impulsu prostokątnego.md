---
Czas stworzenia: "2026-11-12"
---
#Przetwarzanie_sygnałów 
# Definicja
- W *szczególnych* przypadkach [[Rekonstrukcja schodkowa (ZOH)|rekonstrukcja schodkowa]] pozwala na idealną rekonstrukcję [[Sygnał|sygnału]] [[Próbkowanie|spróbkowanego]]
- Aby było to możliwe muszą być spełnione następujące warunki
	- Znajomoć czasu początku impulsu i jego czas trwania.
	- [[NWD]]
$$
	t_{0} \space\space T_{0}
$$
$$
T_{p} = [[NWD]](t_{0}, T_{0})
$$
- Jest to podatne na tak zwane *błedy taktowania (jitter)*. Wystarczy że próbka nominalna zostanie pobrana minimalnie wcześniej lub próbka końcowa minimalnie pózniej by odtworzony impuls miał nieprawidłowy czas trwania.
- Dla impulsu prostokątnego [[Rekonstrukcja schodkowa (ZOH)|zoh]] daje lepsze efekty a [[Rekonstrukcja liniowa (FOH)|foh]] pozwala tylko na poprawę jakości rekonstrukcji względem [[Szybkość Nyquista (tw. o próbkowaniu)|szybkośći]] prónkowania ale nigdy nie będzie idealny