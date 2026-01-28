---
Czas stworzenia: "2025-11-26"
---
#matematyka #analiza 
# Co i jak
- [[Całka|Całkowanie]] [[Funkcja|funkcjii]] [[Funkcje trygonometryczne|trygonometrycznych]] w funkcjach złożonych odbywa poprzez [[Całkowanie poprzed podstawienie|poprzez podstawienie]] lecz trzeba zrobić to sprytnie z racjii że [[Funkcje trygonometryczne]] *zapętlają się*
$$
\int R(\sin x,\cos x)dx
$$
- Podstawienie zależy od [[Parzystość funkcji|parzystości funkcjii]] R w zależności od sinx i cosx.
	- R nieparzysta względm sinx -> użyj podstawienia cosx
	- R nieparzysta względem cosx -> użyj podstawienia sinx
	- R parzysta względem sinx i cosx -> użyj podstawienia tgx.
- W przypadku ostatniej sytuacji
$$
x = arctg\space u 
$$
$$
dx = \frac{1}{1+u^2}du
$$
$$
\sin x= \frac{u}{\sqrt{ 1+u^2 }}
$$
$$
\cos x = \frac{1}{\sqrt{1+u^{2}}}
$$
- Co wynika z [[Pochodne funkcji elementarnych|pochodnych funkcjii elementarnych]], definicji funkcji trygonoetrycznych, [[Funkcje cyklometryczne|funkcii cyklometrycznych]] oraz [[Twierdzenia pitagorasa|twierdzenia pitagorasa]].
- Doprowadzi nas to do [[Całkowanie funkcji wymiernych|całkowania funkcjii wymiernej]].
-  Jeżeli wszystko powyżej zawiedzie istnieje podstawienie uniwersalne u = tg (x/2).