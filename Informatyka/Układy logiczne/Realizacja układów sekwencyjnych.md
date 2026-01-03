---
Czas stworzenia: "2025-12-09"
---
#informatyka #układy_logiczne
# Rysunek
- Aby stworzyć fizyczny [[Układ sekwencyjny|układ sekwencyjny]] należy
	- Rozpisać schemat *strzałkowy* układy wraz z stanami oraz zdecydować się na jeden z modelii
		- [[Model Moore'a]]
		- [[Model Mealy'ego]]
	- [[Minimalizacja liczby stanów układów sekwencyjnych|Zminimalizować liczbę stanów]]
	- [[Kodowanie stanów|Zakodować stany na bity]]
	- Rozpisać tabelke przejśc zakodowanych stanów w nowe stany w zależności od wejścia
	- [[Przerzutnik|Wybrać przerzutnik]]
	- W zależności od wybranego przrzutnika zapisujemy [[Funkcja logiczna|funkcję logiczną]] opisująca następny stan, dla przrzutnika *D* będzie to suma wszystkich wejśc gdzie Q_n+ przyjmuje 1 (lub iloczyn dla zer). [[Zupełnie Normalna Postać Sumacyjna (ZNPS)|ZNPS]], [[Zupełnie Normalna Postać Iloczynowa (ZNPI)|ZNPI]]. Dla przerzutnika *T* jedynka tam gdzie [[Bit|bit]] zmienia się na przeciwny etc.
	- Wyznaczyć funkcję logiczną dla wyjścia
	- Zminimalizować funkcje logiczne za pomocą [[Tabela Karnaugh|tabeli karnaugh]] lub ręcznie za pomocą [[Reguły sklejania|reguły sklejania]] tak samo jak przy [[Układ kombinacyjny|układach kombinacyjnych]]
	- Narysywać schemat wykorzystując zapisane funkcje logiczne oraz [[Sprzężenie zwrotne|sprzeżenie zwrotne]] dla przerzutników. Do przerzutników należy podłączyć zegar!
# Przykład
