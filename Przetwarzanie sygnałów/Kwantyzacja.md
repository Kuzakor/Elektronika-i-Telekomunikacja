---
Czas stworzenia: "2026-10-28"
---
#Przetwarzanie_sygnałów 
# Definicja
- Odpowiednik [[Próbkowanie|próbkowania]] dla amplitudy. 
- Zamienia wartości zbioru na wartości *dyskretne* czyli niejako *zaokragła* je do konkretnych wartośći
- Zastąpienie opisu [[Funkcja|ciągłego]] danej wielko sci, np. sygnału elektrycznego, opisem nieciągłym za pomocą tylko niektórych wartośćci, przyjmowanych przez przebieg ciągły.
- *Kwantyzator* - [[Elementy liniowe inercyjne|Układ]] realizujący kwantyzację
- *[[Błąd (szum) kwantyzacji]] - różnica pomiędzy oryginalnym [[Sygnał|sygnałem]] a jego skwantowanym odpowiednikiem
- *Poziom kwantyzacji* - wartość do której jest *zaookraglana* amplituda
- [[Moc sygnału do szumu kwantyzacji]]
### Możliwe sposoby działania kwantyzatora
- [[Całka|całkujący]] - zliczanie kolejnych impulsów
- *przetwarzanie U/f* - -||--
- *przetwarzanie równoległe* - ustalenie które komparatory zwróciły jaki stan logiczny na wyjściach
- *delta-sigma*  - kwantyzacja w bloku filtracji cyfrowej poprzez ograniczanie rodzielczosci liczb danych wynikowych
- [[Kwantyzator liniowy]]
### Kodowanie skwantowanych słów (wartości)
- Kodowanie odbywa sie przeważnie w 
	- [[Zamiana systemu dziesiętnego na inny system liczbowy|naturalnym kodzie binarnym]]
	- [[Kod U2|kodzie U2]]