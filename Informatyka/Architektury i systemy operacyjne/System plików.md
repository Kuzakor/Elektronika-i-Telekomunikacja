---
Czas stworzenia: "2026-11-13"
---
#architektury_systemy #informatyka 
# Definicja
- Systemem plików zarządza [[System operacyjny|system operacyjny]] i *przeważnie* znajduje się on w [[Zarządzanie pamięcią pomocniczą (SO)|pamięci pomocniczej]] ([[Zarządzanie pamięcią pomocniczą (SO)]]) ale czasem zdarza się że jest on w [[Pamięć operacyjna|pamięci operacyjnej]] (Systemy live)
- Każdy system plików składa się z dwóch części:
	- Faktycznych plików
	- Struktury katalogowej - opisu plików
## Metody dostępu do plików
- Sekwencyjny - informacje o pliku są przekazywane *rekord* po *rekordzie* czyli trzeba czytać od początku
- Bezpośredni - pozwala na odczyt dowolnego kawałku pliku bez konieczności jechania *rekord po rekordzie* 
- Indeksowy - wykorzystuje klucze indeksowe pomagające znaleść odpowiedni rekord w pliku
## Sematyka spójności 
- Sematyka spójności określa reguły dostępu do plików i kontroli wersji w systemach wielozadaniowych.
- Sematyka *UNIX* - Wynik operacji jest natychmiastowo widoczy dla pozostałych [[Proces|procesów]]
- Samatyka *sesji* - Wynik operacji jest widoczny tylko dla nowootwarych procesów tzn. jeżeli zmieni się plik na którym obecnie operuje inny program to ten program nie zauważy zmiany.
- Sematyka *plików dzielonych* - Plik używany przez wiele procesów jest *read-only*