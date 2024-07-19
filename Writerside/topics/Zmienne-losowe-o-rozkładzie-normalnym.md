# Zmienne losowe o rozkładzie normalnym. Własności i znaczenie.

Rozkład normalny to jeden z najważniejszych i najczęściej występujących (również w naturze) rozkładów typu ciągłego.

Rozkład normalny opisywany jest dwoma parametrami:

- $\mu \in \mathbb{R}$ - średnia
- $\sigma > 0$ - odchylenie standardowe

![Rozkład Normalny](Normal_Distribution.svg)

## Własności rozkładu normalnego

1. $EX \text{ (Wartość oczekiwana)} = \mu = \text{mediana} = \text{dominanta}$
2. $Var X = \sigma^2$
3. $\alpha_3 \text{ (skośność)} = 0$
4. $\alpha_4 \text{ (kurtoza)} = 3$

Jeżeli chcemy zamienić zmienną losową o jakimś rozkładzie normalnym $N(\mu, \sigma)$ na zmienną o standardowym
rozkładzie normalnym $N(0,1)$, musimy odjąć od niej $\mu$ i podzielić przez odchylenie standardowe $\sigma$.

```tex
\begin{equation}
Z = \frac{X - \mu}{\sigma}
\end{equation}
```

Suma lub różnica dwóch zmiennych o rozkładach normalnych również ma rozkład normalny.

## Reguła trzech sigm

- 68% obserwacji mieści się w przedziale $[\mu - \sigma, \mu + \sigma]$
- 95% obserwacji mieści się w przedziale $[\mu - 2\sigma, \mu + 2\sigma]$
- 99,7% obserwacji mieści się w przedziale $[\mu - 3\sigma, \mu + 3\sigma]$

![Reguła trzech sigm](3_sigmy.png)
