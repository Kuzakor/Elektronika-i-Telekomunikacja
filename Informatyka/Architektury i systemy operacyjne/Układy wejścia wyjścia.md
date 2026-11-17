---
Czas stworzenia: "2026-11-11"
---
#informatyka #architektury_systemy
# Definicja
- Układy te służą do komunikacji między komputerem a światem zewnętrznym.
- Często umieszczane są na *kartach rozszerzeniowych*
- Umożliwiają sprawdzanie gotowości urządzenia, wysyłania poleceń i przyjmowanie danych
- Od strony procesora odbywa się to zazwyczaj poprzez zapis i odczyt [[Rejestr|rejestrów]] zainstalowanych w owych układach.
- [[DMA - Direct Memory Access]]
### Najważniejsze rejestry i metody dostępu
#### Rejestry
- *[[Rejestr]] stanu* - zawiera informacje o stanie urządzenia
- *[[Rejestr]] sterujący* - przyjmuje polecania, które urządzenie ma wykonać
- *[[Rejestr]] danych wysłanych* 
- *[[Rejestr]] danych odebranych*
#### Dostęp
- Współadresowalne układy wejścia/wyjścia
	- Rejestry udostępniane są jako zwykle komórki [[Rodzaje pamięci|pamięci]] w [[Pamięć operacyjna|przestrzenii adresowej pamięci]]
- izolowane układy wejścia/wyjścia
	- Rejestry urządzenia dostępne są w odrębnej przestrzeni adresowej zwaną *przestrzenią adresową wejścia-wyjścia* lub *przestrzenią adresową portów*
### Sterowanie - działania
1. Sprawdzenie stanu urządzenia 
2. Wysyłanie odpowiednich poleceń do urządzenia, jeżeli znajduje się w stanie gotowośći
3. Przesyłanie (lub odczytywanie) danych
4. Sprawdzenie czy urządzenie wykonało polecenie
	- Metoda przeglądania
		- Metoda oparta na ciągłym odczytywyaniu stanu urządzenia aż dostaniemy informację zwrotną. 
		- Nieefektywne
		- Możliwość zacięcia jeżeli nie dostanie odpowiedzi
	- [[Metoda przerwaniona]]