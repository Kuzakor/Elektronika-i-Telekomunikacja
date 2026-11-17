---
Czas stworzenia: "2026-11-12"
---
#informatyka #architektury_systemy
# Definicja
- [[System operacyjny]] gdy zarządza [[Pamięć operacyjna|pamięcią operacyjną]] przydziela [[Proces|procesom]] tzw. *pamięc logiczną*
- System robi to na 4 różne sposoby
### Modele zarządzanie pamięcią
#### Przydział ciągły
- Każdy [[Proces]] dostaje jeden fragment pamięci fizycznej
- W systemie działa wiele procesów więc pamięc jest podzielona na zajęte i wolne
#### Segmentacja
- Przpisanie osobnego fragmentu (segmentu) pamięci dla kodu, zmiennych, stosu etc.
#### Stronicowanie
- Podzielenie pamięci na ramki stałych wielkości i przypisywanie ich do programów
- Ryzyko *szamotania* - system spędza więcej czasu na handlowaniu błędów z powodu przydzielenia za małej ilości ramek niż wykonywaniu pracy 
#### Pamięć wirtualna
- Wydłużenie pamięci o obszar pamięci dyskowej ([[Rodzaje pamięci]]). W efekcie uzyskujemy pamięć logiczna. SWAP file.