# Python Weight Converter

A terminal exercise for converting a weight between kilograms and pounds.

## Run

Requires Python 3; no additional packages.

```bash
python main.py
```

Enter a numeric weight, then choose its **current** unit:

| Input | Conversion |
| --- | --- |
| `K` or `k` | Kilograms to pounds |
| `L` or `l` | Pounds to kilograms |

The script uses the approximate conversion factor `1 kg = 2.205 lb` and rounds the displayed result to a whole number.

## Scope

This is a simple input and arithmetic exercise. It prints a message for unsupported units but does not validate numeric input or reject negative weights.
