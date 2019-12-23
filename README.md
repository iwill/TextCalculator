ScriptCalculator
================

## calculation

- basic: `+`, `-`, `*`, `/`, `%`, `()`

- comments

- variables: `<last>`, `$`, `$n`, ``

```
 1 + 2 // 3
   * 3 // 9
   - 4 // 5

10 / $ // 2
$1 % 2 // 1
```

```
              tax_rate: 0.45 // 0.45
             tax_qcd: 181920 // 181920
1000000 * tax_rate - tax_qcd // 268080
```

- functions

```
f(ads, usd, rmb, rate, qcd): ads * usd * rmb * (1 - rate) + qcd
f(10000, 20, 7, tax_rate, tax_qcd) // 951920.0000000001
```

- Math

```
round(2 / 3 * 100) / 100 // 0.67
floor(2 / 3 * 100) / 100 // 0.66
 ceil(2 / 3 * 100) / 100 // 0.67
```

```
min(max(1, 2), 3) // 2
       pow(2, 10) // 1024
       sqrt(1024) // 32
```

## features

- line number

- local storage

- sync scrolling

## settings & functions

- DecimalDigits

- RoundingMethod

- reset setting

- clear script

- TODO: export result

- TODO: share script
