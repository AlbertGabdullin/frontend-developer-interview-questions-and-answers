## What is the difference between == and ===?

The `==` operator compares values for equality after converting both values to a common type (type coercion). The `===` operator, on the other hand, compares both value and type without performing type coercion.

### Examples

```javascript
console.log(5 == '5'); // true, because '5' is converted to 5 before comparison
console.log(5 === '5'); // false, because the types are different (number vs string)
```
