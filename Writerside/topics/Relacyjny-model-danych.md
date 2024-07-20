# Relacyjny model danych

> Dominujący model danych dla transakcyjnych baz danych oparty na teorii mnogości.

Dane grupowane są w relacje, które reprezentowane są przez tabele.

## Relacja

Relacja to zbiór rekordów o ustalonej strukturze powiązanych ze sobą za pomocą kluczy.

Relacja składa się z:
- Nagłówka - zbiór atrybutów w formie par `atrybut: dziedzina`.
- Treści - zbiór tupli `(atrybut, wartość)`.

## Klucz

Każda relacja posiada klucz główny, który jednoznacznie identyfikuje każdy rekord.

Klucz obcy to zbiór atrybutów jednej tabeli wskazujący wartość klucza kandydującego innej tabeli. Służy do tworzenia relacji między tabelami.

## Operacje relacyjne

- **Selekcja** - wybór rekordów spełniających warunek.
- **Projekcja** - wybór kolumn.
- **Suma** - suma rekordów z dwóch relacji.
- **Różnica** - różnica rekordów z dwóch relacji.
- **Iloczyn** - iloczyn rekordów z dwóch relacji.
