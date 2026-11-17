---
Czas stworzenia: "2026-11-12"
---
#informatyka #architektury_systemy
# Definicja
- [[System operacyjny]]
- [[Rodzaje pamięci]]
- [[Pamięć operacyjna]]
- [[Pamięć drugorzędna (poboczna)]]
- Pamieć pomocniczna (dyskowa) składa się z:
	- Talerzy + głowic
	- Talerz podzielony na ścieżi i sektory
	- Ścieżki tworzą tzw. *cylindry*
	- Sektory tworzą tzw. *bloki fizyczne* danych o stałym rozmiarze
## Adresowanie
### CHS (Cylinnder-Head-Secotr) 
- Adresowanie zgodnie z fizyczną budową danych na dysku
### LBA (Logical Block Addressing)
- Adresowanie liniowe zgodnie z wzorem
$$
LBA = (C\times Lgc \times Ng) \times Lss + Ns
$$
- C - numer cylinda
- Lgc - liczba głowic na cylinder
- Ng - numer głowicy
- Lss - liczba sektorów na ścieżkę
- Ns - numer sektora

## Zarządzanie

### Zarządzanie wolnymi obszarami
 - Mapa bitowa
	- Każdu *blok fizyczy* jest reprezentowany przez jeden [[Bit|bit]]
		- 0 - wolny
		- 1 - zajęty
- Lista powiązana (Linked list)
	- Wskaznik pierwszego wolnego bloku a kolejne bloki zawierają wskazana na kolejny wolny blok za nimi
- Grupowe
	- Przechowanie adresów wszystkich wolnych bloków w pierwszym wolnym bloku
- Zliczanie
	- Można przechowywać adres pierwszego wolnego bloku w grupie koljenych wolnych bloków i ich liczbę
### Przydzielanie pamięci (bloków) procesom
- Ciągły - najszybszy ale problem z *fragmentacją*
- Listowy - [[System plików|plik]] stanowi listę powiązanych z sobą bloków
	- Zaleta - brak fragmentacji
	- Wada - osłabiona niezawodność
	- Nie może służyc do organizacji dostępu bezpośredniego
	- Przykład: FAT32
- Indeksowy - wskaźniki bloków pliku są skupione w bloku indeksowym
	- Zaleta - bezpośredni dostęp bez fragmentacji
	- Wada - indeksy zajmują i *marnują* miejsce na dysku
- Indeksowo-listowy - hybryda ostatnich dwóch 