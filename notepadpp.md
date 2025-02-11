# Regular expressions
## Delete uneven rows
- Find: .+\r\n(.+(\r\n|$))
- Replace: $1

## Add comma in a determined position (Regular Expressions)
- Find: (\d{N})(\d.*)
- Replace: \1,\2

### Explanation:
    (\d{N}) → Captures the first N digits.
    (\d.*) → Captures the rest of the number.
    \1,\2 → Inserts a comma after the first two digits.
