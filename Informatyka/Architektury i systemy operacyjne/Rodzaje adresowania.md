---
Czas stworzenia: "2026-11-11"
---
#informatyka #architektury_systemy
# Definicja
- Są to rózne sposoby na dostęp do [[Pamięć operacyjna|pamięci operacyjnej]] w [[Rozkazy ASM x86|ASM]]
	- Adresowanie natychmiastowe - brak odwołania do [[Rodzaje pamięci|pamięci]] (mov eax, 5)
	- Adresowanie bezpośrednie - bezpośrendie odwołanie się do pamięci po etykiecie (mov eax, ocena_text)
	- Adresowanie pośrednie - odwołanike się do pamięci poprzez adres zawarty w [[Rejestr|rejestrze]] (mov eax, [ebx]) 
	- Rejestrowy
	- Rejestrowy pośredni
	- Indeksowany
	- [[Stos]]