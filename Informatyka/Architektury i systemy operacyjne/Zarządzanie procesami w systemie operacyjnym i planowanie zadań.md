---
Czas stworzenia: "2026-11-12"
---
#informatyka #architektury_systemy
# Definicja
- W [[System operacyjny|systemach operacyjnych]] są dwa sposoby zarządzania [[Proces|procesami]]
- *Wielozadaniowość bez wywłaszczania*
	- Procesy dobrowolnie oddają zasoby, z których korzystają i działają tak długo jak im się podoba
- *Wielozadaniowość z wywłaszczaniem*
	- [[Proces]] dostaje zasób na ograniczony czas i [[System operacyjny]] zabiera mu go bez dyskusji jak się on skończy.
### Algorytmy planowania zadań
- FCFS - First come first serve
- SJF - Shortest job first
- Piorytetowe SJF
- Planowanie rotacyjne - procesy  maja z góry zdeifniowany okres czasu w którym mogą pracować
- Wielopoziomowe planowanie kolejek 
- Wielopoziompowe planowanie kolejej z sprzężeniem zwrotnym
- Mechanizmy
	- [[Metoda przerwaniona]]
	- Niskiego poziomu (jądro/[[API]])
		- [[Sygnał]]
		- potoki
	- Wysokiego poziomu
		- semafory 
		- [[Sekcja krytyczna]]
		- monitory
		- komunikaty