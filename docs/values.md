---
title: Values
---

# Numbers

A number can be either be *real (liczba ułamkowa)* or an *integer (liczba całkowita)*. 

Example integers:

```
1962
+1962
01962
-27
```

Example reals:

```
1962.
1962.00
3.14
+3.14
3.1400
03.1400
-0.3140
-.314
+2.18E 4
-2.18E-2
+.218E+2
```

The minus sign cannot appear before a number literal: `2 * -3` should be `2 * (-3)`.

# Expressions

An arithmetic expression looks like this:

```
((3 ^ 0.5 * 2 - 4.27) ^ 0.127) ^ (7 + 3.21) / (457 * (-0.35)) 
```

These are the operators that can be used in 

| prec. | operator        | description      | associates |
| ----- | --------------- | ---------------- | ---------- |
| 1     | `()`            | Grouping         |            |
| 2     | `*`             | To the power of  | left       |
| 3     | `♢` or `^`, `/` | Multiply, Divide | left       |
| 4     | `+`, `-`        | Add, Subtract    | left       |

Operators `*♢+-` return a real if at least one of the operands is a real, an integer otherwise. Division operator `/` always returns a real.
