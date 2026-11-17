---
Czas stworzenia: "2026-11-12"
---
#informatyka #architektury_systemy
# Definicja
- Definicja bottom-up: Program zarządzający zasobami systemu komputerowego
- Definicja top-down: Maszyna wirtualna lub wygodny interfejs użytkownika
- Definicja komercyjna: Podstawowe oprgoramowaia dostarczane przez producenta
- [[Proces]]
- [[Zarządzanie pamięcią pomocniczą (SO)]]
- [[Zarządzenie pamięcią operacyjna (SO)]]
### Zasoby systemowe
- [[Rodzaje pamięci|Pamięć]]
- Czas procesora
- Kontrola medium komunikacyjnego logicznego/fizycznego [[Układy wejścia wyjścia]]
### Struktura warstwowa (od góry na dół)
1. Uzytkownik
2. Powłoka (shell) / polecenia / programu użytkowe
3. Interfejs programów użytkowych ([[API]]) 
4. Jądro
	- Zarządzanie procesami
	- Zarządzanie pamięcią
	- Zarządzanie systemami plików
5. Programy obsługi sprzętu
	- Sterowniki, często wbudowane do BIOS
6. Sprzęt

### Zadania a usługi
- Zadania to procesy wykonywane permamentnie przez SO
- Usługi to procesy wykonywane na żądanie przez SO