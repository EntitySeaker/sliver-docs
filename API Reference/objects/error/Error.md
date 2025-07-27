# Error - object
The error object is an object that contains an error message.
This is useful for determining if the result of something is an error, ex: `if result isa Error` or `if typeof(result) == "Error"`

```c
Error {
  STRING msg // This contains the error message.
}
```