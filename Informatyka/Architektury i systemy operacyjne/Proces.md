---
Czas stworzenia: "2026-11-12"
---
#informatyka #architektury_systemy
# Definicja
- Proces w kontekście [[System operacyjny|systemów operacyjnych]] to po prostu uruchomione zadanie korzystające z
	- Procesora
	- [[Rodzaje pamięci|Pamięci]]
	- Programu
- Wykonuje się niezależnie od innych procesów
- Ubiega się i współzawodniczny o zasoby systemu
- Korzysta z jądra systemu operacyjnego
### Atrybuty
- Identyfikator
- Stan
- Piorytet
- id właściciela
- miejsce w kolejce (kolejkach)
- ograniczeia pamięci

### Opis
- gotowy
- aktywny
- czekający
- zawieszony/wstrzymany

### Proces lekki a ciężki
- Proces *ciężki* to tradycyjny proces systemowy, który stanowi samodzielne zadanie z własną wydzieloną [[Pamięć operacyjna|przestrzenią adresową]] i jednym *wątkiem*
- Proces lekki to jednostka wykonawcza wyodrbębniona w obrębie jednego procesu (zadania) realizująca *wielozadaniowość wewnątrz zadania*