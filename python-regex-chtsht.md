# Python Regular Expressions Cheatsheet

## Regular Expressions

### Basics

`.` Any character except newline
`a` The character a
`ab` The string ab
`a|b` a or b
`a*` 0 or more a's
`\` Escapes a special character

### Quantifiers

`*` 0 or more
`+` 1 or more
`?` 0 or 1
`{2}` Exactly 2
`{2, 5}` Between 2 and 5
`{2,}` 2 or more
`(,5}` Up to 5

### Character Classes

`[ab-d]` One character of: a, b, c, d
`[^ab-d]` One character except: a, b, c, d
`[\b]` Backspace character
`\d` One digit
`\D` One non-digit
`\s` One whitespace
`\S` One non-whitespace
`\w` One word character
`\W` One non-word character

### Assertions

`^` Start of string
`\A ` Start of string, ignores m flag
`$` End of string
`\Z` End of string, ignores m flag
`\b` Word boundary
`\B` Non-word boundary
`(?=...)` Positive lookahead
`(?!...)` Negative lookahead
`(?<=...)` Positive lookbehind
`(?<!...)` Negative lookbehind
`(?()|)` Conditional

### Groups

`(...)` Capturing group
`(?P<Y>...)` Capturing group named Y
`(?:...)` Non-capturing group
`\Y` Match the Y'th captured group
`(?P=Y)` Match the named group Y
`(?#...)` Comment

### Flags

`i` Ignore case
`m` ^ and $ match start and end of line
`s` . matches newline as well
`x` Allow spaces and comments
`L` Locale character classes
`u` Unicode character classes
`(?iLmsux)` Set flags within regex

### Special Characters

`\n` Newline
`\r` Carriage return
`\t` Tab
`\YYY` Octal character YYY
`\xYY` Hexadecimal character YY

### Replacement

`\g<0>` Insert entire match
`\g<Y>` Insert match Y (name or number)
`\Y` Insert group numbered Y

## strftime() and strptime() Format Codes

https://docs.python.org/3/library/datetime.html#strftime-and-strptime-format-codes

## References

- https://www.debuggex.com/cheatsheet/regex/python
