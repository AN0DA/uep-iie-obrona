# Net Present Value (NPV)

Net Present Value (NPV), czyli wartość bieżąca netto, to metoda oceny opłacalności inwestycji, która polega na
zdyskontowaniu przyszłych przepływów pieniężnych generowanych przez daną inwestycję. NPV to suma zdyskontowanych
przyszłych przepływów pieniężnych pomniejszona o początkowy koszt inwestycji.

## Jak obliczyć NPV

Aby obliczyć NPV, należy:

1. Określić przyszłe przepływy pieniężne generowane przez inwestycję w każdym okresie (np. rok).
2. Określić stopę dyskontową, która odzwierciedla oczekiwaną stopę zwrotu lub koszt kapitału.
3. Zdyskontować przyszłe przepływy pieniężne do ich wartości bieżącej.
4. Zsumować zdyskontowane przepływy pieniężne.
5. Odjąć początkowy koszt inwestycji od sumy zdyskontowanych przepływów pieniężnych.

## Wzór na NPV

```tex
\begin{equation}
\text{NPV} = \sum_{t=1}^{n} \frac{CF_t}{(1 + r)^t} - I_0 
\end{equation}
```

gdzie:

- `CF_t` - przepływy pieniężne w okresie  `t`
- `r` - stopa dyskontowa
- `t` - numer okresu
- `n` - łączna liczba okresów
- `I_0` - początkowy koszt inwestycji

## Interpretacja NPV

- **NPV > 0**: Inwestycja jest opłacalna, ponieważ generuje wartość dodaną, przewyższając koszt kapitału.
- **NPV = 0**: Inwestycja jest neutralna, ponieważ generuje dokładnie taką samą wartość, jak koszt kapitału.
- **NPV < 0**: Inwestycja jest nieopłacalna, ponieważ nie generuje wystarczającej wartości, aby pokryć koszt kapitału.

## Zalety NPV

1. **Uwzględnia wartość pieniądza w czasie**: Dyskontowanie przyszłych przepływów pieniężnych pozwala na realistyczną
   ocenę wartości inwestycji.
2. **Kompleksowa ocena**: NPV uwzględnia wszystkie przyszłe przepływy pieniężne, zarówno dodatnie, jak i ujemne.
3. **Łatwość interpretacji**: Wynik NPV daje jednoznaczną informację o opłacalności inwestycji.

## Wady NPV

1. **Zależność od stopy dyskontowej**: Wybór odpowiedniej stopy dyskontowej może być trudny i ma znaczący wpływ na wynik
   NPV.
2. **Prognozowanie przyszłych przepływów pieniężnych**: Dokładne przewidywanie przyszłych przepływów pieniężnych może
   być trudne, co wpływa na dokładność obliczeń.

## Przykład obliczenia NPV

Załóżmy, że przedsiębiorstwo planuje inwestycję o początkowym koszcie 100,000 zł, która w ciągu trzech lat przyniesie
następujące przepływy pieniężne:

- Rok 1: 40,000 zł
- Rok 2: 50,000 zł
- Rok 3: 60,000 zł

Przyjmując stopę dyskontową 10%, NPV można obliczyć następująco:

```tex
\begin{align*}

\text{NPV} &= \frac{40,000}{(1 + 0.10)^1} + \frac{50,000}{(1 + 0.10)^2} + \frac{60,000}{(1 + 0.10)^3} - 100,000 \\

\text{NPV} &= \frac{40,000}{1.10} + \frac{50,000}{1.21} + \frac{60,000}{1.331} - 100,000 \\

\text{NPV} &= 36,364 + 41,322 + 45,084 - 100,000 \\

\text{NPV} &= 22,770
\end{align*}
```

Wartość bieżąca netto (NPV) tej inwestycji wynosi 22,770 zł, co oznacza, że inwestycja jest opłacalna.
