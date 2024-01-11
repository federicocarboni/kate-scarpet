# Change Log

## Version 3 11 Jan. 2024

- Fix hexadecimal number literal highlighting

## Version 2 08 Jan. 2024

- Fix decimal number highlighting
- Decimal numbers with a leading `.` are highlighted as error
- Fix string escape highlighting (only `\t`, `\n`, `\\` and `\'` are accepted)
- Invalid string escapes are highlighted as error

## Version 1 08 Dec. 2023

- Basic syntax highlighting: comments, control flow, keywords, operators, constants, function calls and definitions, global variables
- Code folding for maps `{}`, lists `[]` and 'blocks' `()`
- Minecraft API highlighting as `dsBuiltIn` only in call position
- Minecraft Event API highlighting as `dsOthers`
- Deprecated APIs are ~~strikethrough~~
- Partial support for printf-like sequences in strings (e.g. `'%s %d %.2f'`)
