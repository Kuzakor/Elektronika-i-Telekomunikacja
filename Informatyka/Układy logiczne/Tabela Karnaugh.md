---
Czas stworzenia: "2025-10-19"
---
#informatyka #układy_logiczne
# Definicja
- Jest to sposób na algorytmiczną *minimalizajcę* [[Funkcja logiczna|funkcjii logicznych]] zapisanych za pomocą tabelki prawdy.
- Polega ona na narysowaniu tabeli zmienne/zmienne posegregowanych według [[Kod Gray'a|kodu graya]] oraz zakreśleniu w prostokątach jedynek. Grupa jedynek musi mieć wielkość bedącą wielokrotnością dwójki.
- Tabelka ta "zapętla się" tam gdzie różnica między wejściami jest równa 1.
- Dla każdej z tych grup patrzymy które zmienne pozostają takie same dla każdej z jedynek.
- Do wzoru w postaci [[Algebra boole'a|boolowskiej]] w systemie [[Zupełnie Normalna Postać Sumacyjna (ZNPS)|znps]] spisujemy tą zmienną.
- Jeżeli jest ona równa 0 wpisujemy jej zanegowaną wersję. 
- Po zapisaniu wszystkich zmiennych (iloczyn) przechodzimy do następnej grupy i powtarzamy. Wynik dodajemy do poprzednego.
- Dla [[Zupełnie Normalna Postać Iloczynowa (ZNPI)|znpi]] postępujemy analogicznie lecz łączać 0. I negując przy 1.
- Działa to dzięki [[Reguły sklejania|regule sklejania]]
# Przykład
[[Tabela Karnaugh.excalidraw]]
