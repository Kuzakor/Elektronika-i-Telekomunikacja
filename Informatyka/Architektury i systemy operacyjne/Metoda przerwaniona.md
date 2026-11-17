---
Czas stworzenia: "2026-11-12"
---
#informatyka #architektury_systemy
# Definicja
- Przerwania polegają na jak nazwa wskazuje przerwaniu pracy procesora aby obsłużyć [[Układy wejścia wyjścia|układ wyjscia-wejscia]]
- W chwili wywołania *przerwania* przez urządzenie zewnętrzne dzieją się następujące rzeczy:
	1. Zapisanie na [[Stos|stosie]] [[Pamięć operacyjna|adresu]] [[Rozkazy ASM x86|rozkazu]] ([[Rejestr]] EIP)
	2. Ustawienie EIP na adres podprogramu służącego do obsługi przerwania na podstawie tak zwanej *Tablicy deskryptorów przerwań*
	3. Podprogram po zakończonej pracy ściąga z stosu adres rozkazu jaki był przed przerwaniem
	4. Procesor kontynuuje pracę jak wcześniej
- W sytuacji gdy procesor dostaje wiele przerwań na raz, obsługuje je według *piorytetu*
- Podczas obsługi przerwania procesor nie obsługuje innych przerwań 
	- Dotyczy to tylko tzw. *Przerwań maskowalnych*
	- *Przerwania niemaskowalne* są w stanie nadpisać obecne przerwanie.