# Operators and Loops

## Operators

### Comparison Operators

JavaScript language includes operators that compare two operands and return Boolean value true or false.

Operators | Description
------------ | -------------
==	| Compares the equality of two operands without considering type.
===	| Compares equality of two operands with type.
!=	| Compares inequality of two operands.
>	| Checks whether left side value is greater than right side value. If yes then returns true otherwise false.
<	| Checks whether left operand is less than right operand. If yes then returns true otherwise false.
>=	| Checks whether left operand is greater than or equal to right operand. If yes then returns true otherwise false.
<=	| Checks whether left operand is less than or equal to right operand. If yes then returns true otherwise false.

The following example demonstrates how comparison operators perform different tasks.

#### Example: Comparison Operators
```javascript
var a = 5, b = 10, c = "5";
var x = a;

a == c; // returns true

a === c; // returns false

a == x; // returns true

a != b; // returns true

a > b; // returns false

a < b; // returns true

a >= b; // returns false

a <= b; // returns true

a >= c; // returns true

a <= c; // returns true
```

### Logical Operators

Logical operators are used to combine two or more conditions. JavaScript includes following logical operators.

Operators | Description
------------ | -------------
&& | is known as AND operator. It checks whether two operands are non-zero 
|| | is known as OR operator. It checks whether any one of the two operands is non-zero 
!  | is known as NOT operator. It reverses the boolean result of the operand (or condition)

#### Example: Logical Operators

```javascript
var a = 5, b = 10;

(a != b) && (a < b); // returns true

(a > b) || (a == b); // returns false

(a < b) || (a == b); // returns true

!(a < b); // returns false

!(a > b); // returns true
```