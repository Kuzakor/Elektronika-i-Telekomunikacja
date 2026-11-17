---
Czas stworzenia: "2026-11-12"
---
#informatyka #architektury_systemy
# Definicja
- Klaster to grupa połączonych z sobą komputerów.
- Ma to na celu poprawienie wydajności, stworzenia lepszej skalowalności lub większej dostępności (backup)
- [[Model warstwowy ISO OSI RM]]
### Typy:
- Wydajnościowy 
	- Ma na celu masowe przetwarzanie danych jednego rodzaju (głównie naukowych)
	- Wymagają bibliotek przetwarzania równoległego
- Wysokiej dostępnośći
	- Ma na celu zabezpieczenie systemu (np. bankowego) przed upadkiem
	- Jeżeli jeden serwer/komputer padnie to obsługę przejmie inny i system będzie cały czas on-line.
- Równoważenie obciążenia
	- Każdy komputer może wykonywać różne operacje ale wszystkie z sobą wspołpracują
	- Uzywa przy np 
		- HTTP
		- FTP 
		- NNTP
		- DNS
# Budowa
- *Węzeł obliczeniowy*
- *Węzeł zarządzający*
- *Węzeł obsługujący [[System plików]]*
- *Sieć*
### Model SSI
- Użytkownik widzi klaster jako jeden wielki komputer
### Model Beowulf
- Użytkownik widzi klaster jako sieć współpracujących komputerów