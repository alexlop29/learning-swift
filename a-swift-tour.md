### Hello World
```
print("hello world")
```
[Link](https://swiftfiddle.com/3qzeizjyvfc3jmthu3j7ryf474)

### Simples Values
> Use let to make a constant and var to make a variable.
> https://docs.swift.org/swift-book/documentation/the-swift-programming-language/guidedtour#Simple-Values

```
let CONSTANT = 40
var VARIABLE = 23

print(CONSTANT)
print(VARIABLE)

VARIABLE = 25
print(VARIABLE)

# The following returns a runtime error
CONSTANT = 20
```
[Link](https://swiftfiddle.com/zlgyyljhtzd63jy37qh2gvk6km)

> Providing a value when you create a constant or variable lets the compiler infer its type.
> ...
> Specify the type by writing it after the variable, separated by a colon.

```
let DOUBLE: Double = 20.0
print(DOUBLE)
```
[Link](https://swiftfiddle.com/hymigzokrbexdmo7howfq3qzxy)

> If you need to convert a value to a different type, explicitly make an instance of the desired type.
```
let DOUBLE: Double = 20.0

print(type(of: String(DOUBLE)))
```
[Link](https://swiftfiddle.com/orbvwaoq5vdunckceudbby6ns4)
