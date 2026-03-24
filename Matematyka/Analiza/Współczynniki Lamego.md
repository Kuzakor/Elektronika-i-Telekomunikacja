---
Czas stworzenia: "2026-03-24"
---
#matematyka #analiza 
# Definicja
- Przy obliczaniu [[Gradient|gradientu]], [[Dywergencja|dywergencji]] bądź [[Rotacja|rotacji]] danego [[Pole wektorowe|pola wektorowego]] w współrzędnych inne niż kartezjańskie musimy niektóre elementy wymnożyć jeżeli chcemy liczyć z nich [[Pochodna|pochodną]] (co jest potrzebne przy tych działaniach)
- [[Współrzędne walcowe]]
- [[Współrzędne sferyczne]]
- [[Współrzędne biegunowe]]
- Najpierw musimy zastanowić się które wartości faktycznie pokazują nam *wielkość* danego obiektu i odpowiednio dostosować [[Róniczki|różniczki]]
- Następnie musimy dane działanie przekształcić wykorzystując otrzymane różniczki.
- Iloczyn wszystkich tych przekształceń jest równy [[Jakobian|jakobianowi]] danych współrzędnych
# Przykład dla współrzędnych sferycznych
$$
\vec{A}(r,\theta,\phi) = [P,Q,R]
$$
$$
dr \implies 1dr
$$
$$
d\theta \implies r d\theta
$$
$$
d\phi \implies r\sin \theta d\phi
$$
$$
\vec{\nabla} \cdot \vec{A} = \frac{1}{1 *r *r\sin \theta} \left( \frac{\partial}{\partial r} P(r * r\sin \theta) + \frac{\partial}{\partial \theta}Q(1*r\sin \theta) +\frac{\partial}{\partial \phi }R(1 * r)\right)
$$
$$
\vec{\nabla}\cdot \vec{A}=\frac{1}{1*r*r\sin \theta}\begin{vmatrix}
i &j &k \\
\frac{\partial}{\partial r} & \frac{\partial}{\partial \theta} & \frac{\partial}{\partial \phi}  \\
P(r*r\sin \theta) &Q(1*r\sin \theta) & R(1 * r)
\end{vmatrix}
$$


