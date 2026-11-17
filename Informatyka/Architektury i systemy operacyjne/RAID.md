---
Czas stworzenia: "2026-11-13"
---
#architektury_systemy #informatyka 
# Definicja
- RAID to jedna z realizacji [[Macierze dyskowe|macierzy dyskowych]]
- Istnieją też macierze hybrydowe czyli *łączenie drzewnie* różnych typów RAID. W nazwie pierwsza cyfra to ten raid *niżej w hierarhi*. Na przykład RAID 01 to RAID 1 którego dyski to w rzeczywistości pary RAID0.
### RAID 0
- Połaczenie dwóch dysków w jeden dysk
- Dane przeplecione między dyskami
- Zalety dość oczywiste, wady:
	- Przestrzeń Nx przestrzeń najmniejszego dysku
### RAID 1
- Połączenie dwóch dysków
- Dane replikowane między dyskami w celu zabezpieczena
### RAID 3
- Modyfikacja *RAID 0*
- Dodatkowy dysk przechowujący sumy kontrolne
- Zalety:
	- Odporność na awarię jednego dysku
	- Duża szybkość odczytu
- Wady:
	- Mniejsza szybkość zapisu (obliczanie sum)
	- Czasochłonna odbudowa
### RAID 4
- Modyfikacja *RAID 3*
- Dane podzielone na większe bloki danych
- Zalety
	- Odporność na awarię jednego dysku
	- Duża szybkość odczytu i zapisu
- Wady
	- Powolna przy małych plikach

### RAID 5
- Modyfikacja *RAID 4*
- Sumy kontrolne są rozpraszane po całej strukturze macierzy
- Zalety:
	- Odporność na awarię jednego dysku
	- Duża szybkość odczytu
- Wady:
	- Powolna przy małych plikach
	- Powierzchnia dyskowa N-1

### RAID 6
- Modyfikacja *RAID 5*
- [[Macierz]] z podwójną parzystością
- Zalety:
	- Odporność na awarię dwóch dysku
	- Duża szybkość odczytu
- Wady:
	- Wydajność zależna od implementacji
	- Powierzchnia dyskowa N-2