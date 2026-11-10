---
Czas stworzenia: "2026-11-05"
---
#Przetwarzanie_sygnałów 
# Definicja
- Odpowednik [[Transformata FT|transformaty FT]] dla sygnału dyskretnego. 
- Zarówno [[Widmo sygnału (dziedzina częstotliwości)|widmo]] jak i [[Sygnał|sygnał]] są dyskretne.
- [[Jednostka urojona (i)]]
# Wzór
$$
X_{n}[k] = \sum^{N-1}_{n = -\infty} x[n]e^{-j \frac{2\pi}{N}kn} 
$$
# Metoda macierzowa
- Transformatę tę można prościej policzyć za pomocoą [[Macierz|macierzy]] poprzez wyznaczenie macierzy transformacji:
$$
W_{N} = e^{j \frac{2 \pi}{N}}
$$
$$
W = \begin{bmatrix}
W_{N}^{0*0} & W_{N}^{0*1} & W_{N}^{0*2} & W_{N}^{0*3} &\dots \\
W_{N}^{1*0} & W_{N}^{1*1} & W_{N}^{1*2} & W_{N}^{1*3} & \dots  \\
W_{N}^{2*0} & W_{N}^{2*1} & W_{N}^{2*2} & W_{N}^{2*3} & \dots \\
\dots & \dots & \dots & \dots & \dots   
\end{bmatrix}
$$
- A następnie wymnożenie jej przez [[Wektor|wektor]] oryginalnego sygnału
# Właściwośći
- Liniowa
### Dualna
$$
x_{N}[n] \Leftrightarrow X_{N}[k]
$$
$$
X_{N}[n] \Leftrightarrow N \cdot x_{N}[(N-k)\text{mod} N] 
$$

### Cykliczne odwrócenie w czasie (odbicie lustrzane)
$$
\tilde{x}_{N}[-n] \Leftrightarrow \tilde{X_{N}}[-k]
$$
$$
\tilde{x}_{N}[-n] = x_{n}[-n \text{{mod}} N|]
$$
### Przesunięcie w dziedzinie czasu (bardzo podobne do FT)
$$
x_{N}[(n-n_{0})\text{modN}] \Leftrightarrow e^{-j\frac{2\pi}{N}kn_{0}}X_{n}[k]
$$

### Przesunięcie w dziedzinie częstotliwości jest analogiczne. Wykladnik po prostu po drugiej stronie

### [[Modulacja analogowa|Modulacja]] rzeczywista
$$
y_N[n] = x_N[n]\cos\left(\frac{2\pi}{N}k_0 n\right) \;\Leftrightarrow\; Y_N[k] = \frac{1}{2}\left[X_N[(k-k_0) \bmod N] + X_N[(k+k_0) \bmod N]\right]
$$
### Własności [[Splot|splotu]] są zachowane (mnożenie/splot i vice versa)
