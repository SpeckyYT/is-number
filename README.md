# is-number

> Returns true if the value is a finite number.

## Usage

```spwn
isNumber = import 'is-number'

isNumber(5) // true
isNumber(69.420) // true
isNumber(0/0) // false
isNumber(10^309) // false
isNumber('hello') // false
isNumber(obj{}) // false
isNumber(3g) // false
isNumber({}) // false
isNumber([]) // false
```
