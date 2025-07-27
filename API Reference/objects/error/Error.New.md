# Error.New - function
The Error.New function will return a new error object.

## Syntax
```c
ERROR Error.New(
  STRING message // This should be error message.
)
```
## Parameters

`message`

Type: **string**

The error message.
## Return value
Type: **error**

An error object is returned containing the error `message`.