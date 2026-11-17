---
Czas stworzenia: "2026-11-12"
---
#informatyka #architektury_systemy
# Definicja
- Blokada to sytuacja w której [[Proces|procesy]] nie moga kontunować zadania bo przetrzumują wzajemnie sobie [[System operacyjny|zasoby]]
- Powstają jeśli są spełnione jednoczenie 4 warunki:
	- Wzajemne wyłączanie
	- Przetrzymywanie i oczekiwanie na innyc zasób
	- Brak [[Zarządzanie procesami w systemie operacyjnym i planowanie zadań|wywłaszczeń]] zasobów
	- Czekanie cykliczne
### Zapobieganie, wykrywanie i usuwanie
1. Niedpousczanie do spełniania powyższych warunków.
2. Wykrycie za pomocą algorytmów
	- Mechanizm timeout
	- Algorytm redukcji grafu
	- Algorytm oparty na macierzach żądań
3. Usunięcie
	- Zakończenie procesów
		- Ofiara jest wybierana na podstawie
			- *Piorytetu*
			- *Czasu pracy*
			- *Liczby zajmowanych zasobów*
	- Zaniechanie
	- Wywłaszczenie zasobów