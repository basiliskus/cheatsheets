# Python Regular Expressions Cheatsheet

## Regular Expressions

### Basics

| Match                        | Regex    |
| ---------------------------- | -------- |
| Any character except newline | `.`      |
| The character a              | `a`      |
| The string ab                | `ab`     |
| a or b                       | `a \| b` |
| 0 or more a's                | `a*`     |
| Escapes a special character  | `\`      |

### Quantifiers

| Match           | Regex    |
| --------------- | -------- |
| 0 or more       | `*`      |
| 1 or more       | `+`      |
| 0 or 1          | `?`      |
| Exactly 2       | `{2}`    |
| Between 2 and 5 | `{2, 5}` |
| 2 or more       | `{2,}`   |
| Up to 5         | `(,5}`   |

### Character Classes

| Match                            | Regex     |
| -------------------------------- | --------- |
| One character of: a, b, c, d     | `[ab-d]`  |
| One character except: a, b, c, d | `[^ab-d]` |
| Backspace character              | `[\b]`    |
| One digit                        | `\d`      |
| One non-digit                    | `\D`      |
| One whitespace                   | `\s`      |
| One non-whitespace               | `\S`      |
| One word character               | `\w`      |
| One non-word character           | `\W`      |

### Assertions

| Match                           | Regex       |
| ------------------------------- | ----------- |
| Start of string                 | `^`         |
| Start of string, ignores m flag | `\A `       |
| End of string                   | `$`         |
| End of string, ignores m flag   | `\Z`        |
| Word boundary                   | `\b`        |
| Non-word boundary               | `\B`        |
| Positive lookahead              | `(?=...)`   |
| Negative lookahead              | `(?!...)`   |
| Positive lookbehind             | `(?<=...)`  |
| Negative lookbehind             | `(?<!...)`  |
| Conditional                     | `(?() \| )` |

### Groups

| Match                         | Regex        |
| ----------------------------- | ------------ |
| Capturing group               | `(...)`      |
| Capturing group named Y       | `(?P<Y>...)` |
| Non-capturing group           | `(?:...)`    |
| Match the Y'th captured group | `\Y`         |
| Match the named group Y       | `(?P=Y)`     |
| Comment                       | `(?#...)`    |

### Flags

| Match                               | Regex       |
| ----------------------------------- | ----------- |
| Ignore case                         | `i`         |
| ^ and $ match start and end of line | `m`         |
| . matches newline as well           | `s`         |
| Allow spaces and comments           | `x`         |
| Locale character classes            | `L`         |
| Unicode character classes           | `u`         |
| Set flags within regex              | `(?iLmsux)` |

### Special Characters

| Match                    | Regex  |
| ------------------------ | ------ |
| Newline                  | `\n`   |
| Carriage return          | `\r`   |
| Tab                      | `\t`   |
| Octal character YYY      | `\YYY` |
| Hexadecimal character YY | `\xYY` |

### Replacement

| Match                           | Regex   |
| ------------------------------- | ------- |
| Insert entire match             | `\g<0>` |
| Insert match Y (name or number) | `\g<Y>` |
| Insert group numbered Y         | `\Y`    |

## strftime() and strptime() Format Codes

https://docs.python.org/3/library/datetime.html#strftime-and-strptime-format-codes

## References

- https://www.debuggex.com/cheatsheet/regex/python
