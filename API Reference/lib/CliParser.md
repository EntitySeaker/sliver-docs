# CliParser - function
The CliParser takes input and parses it in individual parts.

## Syntax
```c
STRING CliParser(
  STRING input
  MAP    vars
)
```
## Parameters

`input`

Type: **string**

The input that needs to be parsed.

`vars`

Type: **map**

A map containing the variables that need to be replaced when called ex: `$VAR` would be replaced.
## Return value

Type: **string**

The parsed input with replaced variables.

