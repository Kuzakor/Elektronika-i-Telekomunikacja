---
Czas stworzenia: "2026-11-11"
---
#informatyka #architektury_systemy
# Definicja
- Rozkazy to po prostu komendy języka assembler 
- Zaczynają się one od 3-literowego *mnemonika* który mówi procesorowi co ma zrobić. 
- Rozkazy można dzielić na rozkazy *sterujące (warunkowe i bezwarunkowe)*, których zadaniem jest obłsuga samego kodu i *niesterujące* które jedynie wykonują operacje na procesorze.
- Ogólnie rzecz biorąc składnia języka ASM wygląda następująco
- [[Rejestr flagowy]]
```asm
rozkaz arg1, arg2
```
### Rozkazy niesterujące
```asm
mov rdx, 5  ;ustawianie
add rdx, 5  ;dodawania - wynik w rdx
sub rdx, 5  ;odejmowaie
shl rdx, 1  ;przesunięcie bitowe w lewo
shr rdx, 1  ;przesunięcie bitowe w prawo
mul rdx,    ;mnożenie rax z rdx - wynik w rax
div rdx,    ;dzielenie rax z rdx - wynik w rax
cmp rax, rdx ;porównanie rax i rdx - wynik nie jest zapisywany, sluzy do ustawiania flag i korzystania z rozkazów sterujących
...
```
### Rozkazy sterujące 
```asm
jnz ptl  ;skok do etykiety ptl jeżeli wynik nie był zerem (na podstawie rejestru flagowego)
jz ;skok jesli zero
je ;skok jesli równe
ja ;skok jesli wieksze (bez znaku)
jb ;skok jesli mniejsze (bez znaku)
jg ;skok jesli wieksze (zr znakiem)
jl ;skok jesli mniejsze (ze znakiem)
jae ;skok jesli wieksze lub rowne (bez znaku)
jbe ;skok jesli mniejsze lub rowne (bez znaku)


```