---
Czas stworzenia: "2026-11-11"
---
#informatyka #architektury_systemy
# Definicja
- Stos to sposób na dostanie się do [[Pamięć operacyjna|pamięci operacyjnej]] który jest bardzo łopatologiczny. 
- Na stos można wrzucać i zrzucać czyli w rezultacie jest to system typu last in - first out.
- Stos rośnie w kierunku malejących [[Pamięć operacyjna|adresów]]
### [[Rozkazy ASM x86]]
```asm
push ebx ;wrzuć ebx na stos
pop ebx; zdejmij z stosu i zapisz w ebx
```