# Wzór Bayesa i jego przykładowe zastosowania

## Wzór Bayesa

Wzór Bayesa pozwala na obliczenie prawdopodobieństwa warunkowego zdarzenia, czyli prawdopodobieństwa wystąpienia
zdarzenia $A$ pod warunkiem, że zaszło zdarzenie $B$. Wzór ten można zapisać w następujący sposób:

```tex
\begin{equation}
P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
\end{equation}
```

gdzie:

- $P(A|B)$ – prawdopodobieństwo zdarzenia $A$ pod warunkiem zajścia zdarzenia $B$,
- $P(B|A)$ – prawdopodobieństwo zdarzenia $B$ pod warunkiem zajścia zdarzenia $A$,
- $P(A)$ – prawdopodobieństwo wystąpienia zdarzenia $A$,
- $P(B)$ – prawdopodobieństwo wystąpienia zdarzenia $B$.

## Przykładowe zastosowania

W diagnostyce medycznej wzór Bayesa jest używany do określenia prawdopodobieństwa, że pacjent ma określoną chorobę na
podstawie wyników testów.

**Przykład:**
Załóżmy, że istnieje test na pewną chorobę, który daje pozytywny wynik u 99% chorych ($P(T|C) = 0.99$) i u 5% zdrowych (
$P(T|¬C) = 0.05$). Jeżeli 1% populacji cierpi na tę chorobę ($P(C) = 0.01$), to możemy obliczyć prawdopodobieństwo, że
osoba ma chorobę, jeśli test jest pozytywny ($P(C|T)$):