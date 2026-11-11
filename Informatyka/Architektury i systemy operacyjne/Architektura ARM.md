---
Czas stworzenia: "2026-11-11"
---
#informatyka #architektury_systemy
# Definicja
- Architektura ARM charakteruzuje się niskim poborem mocy jak na moc obliczeniową
- Skrót to Advanced RISC Machine a RISC oznacza reduced instruction set computer czyli arm posiada mniej [[Rozkazy ASM x86|rozkazów]]
# Różnice
- Rozkazy na architekturze ARM w typowyh przypadkach zawierają 3 argumenty a nie 2 jak w x86.
```asm
ADD R1, R2, R3
```
- Posiada specjalne *przedrostki* które wykonują się tylko jeśli dany warunek jest prawdziwy (sprawdza [[Rejestr flagowy]])
```
EQADD R1, R2, R3 ;Wykona się tylko jeśli ZF = 1
```
### Przedrostki
- EQ - Equal
- NE - Not Equal
- HS/CS - Unsigned higher or same
- LO/CC - Unsigned lower
- GE - Greater or equal
- LT - Lower
- GT - Greater
- AL - Always