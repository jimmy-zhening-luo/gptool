Evaluates and returns calculated result(s).

- `+-*/`, round, floor, ceil
- Tail-end unit conversion: currency as lowercase ISO4217 code (usd), otherwise full, lowercase name (square foot)

Evaluates multiple calculations separated by '&' and returns results in the same order, comma-separated.

Example input -> output:
30-4 -> 26
80-ceil(30.4) -> 49
8+12 celsius TO fahrenheit -> 68
1 foot TO inch & 2 foot TO inch -> 12,24
