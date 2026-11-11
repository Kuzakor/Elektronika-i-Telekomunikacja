---
Czas stworzenia: "2026-11-11"
---
#informatyka #architektury_systemy
# Definicja
- Liczby zmiennoprzecinkowe to sposób na zapisanie dowolnych liczb niecałkowitych w [[Rodzaje pamięci|pamięci]] komputera.
- Aby zapisać liczbę w tym formacie musimy poznać jej *wykładnik dwójkowy* oraz *mantysę*
- [[Zamiana systemu dziesiętnego na inny system liczbowy]]
- [[Standardy w sieci telekomunikacyjnej|Standard ustanowiony przez IEEE]] o nazwie IEEE 754
- System te ma ograniczenia, zapis dwójkowy ułamka bardzo często się nie kończy i jest ucinany co skutkuje błedami w obliczeniach.
# Wzór
$$
(a \cdot10^b)_{10} \implies (c\cdot2^w)_{2} \implies 1,m \cdot 2^w
$$
- Gdzie *m* to mantysa a *w* to wykładnik
# Zapis w pamięci
- Pierwszy [[Bit|bit]] to bit znaku( 1 - -, 0 - +)
#### 32 bit
- Kolejne osiem bitów to wykładnik+127
- Kolejne 23 bity to mantysa
#### 64 bit
- Kolejne osiem bitów to wykładnik+1023
- Kolejne 52 bity to mantysa