---
Czas stworzenia: "2025-10-29"
---
#matematyka #analiza 
# Definicja
- Jest to sposób na obliczanie [[Granica|granic]] porównując je do na pewno większych i mniejszych [[Funkcja|funkcjii]] ([[Ciąg|ciągów]])
- Jeżeli granica większego i mniejszego ciągu (funkcjii) jest taka sama to ta granica też jest tyle równa
# Przykład
$$\lim_{n\to\infty} \sqrt[n]{e^n +\pi^n+8^n}$$
$$\sqrt[n]{8^n} <\sqrt[n]{e^n +\pi^n+8^n}<\sqrt[n]{8^n +8^n+8^n}$$
$$\lim_{n\to\infty}\sqrt[n]{8^n} = 8$$
$$\lim_{n\to\infty}\sqrt[n]{8^n +8^n+8^n} = \lim_{n\to\infty}\sqrt[n]{3*8^n} = \lim_{n\to\infty}\sqrt[n]{3} \sqrt[n]{8^n}=1*8 = 8$$
$$\lim_{n\to\infty} \sqrt[n]{e^n +\pi^n+8^n} = 8$$