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
\|\| | is known as OR operator. It checks whether any one of the two operands is non-zero 
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

## Loops

### While loop

A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.
Syntax :

```javascript
while (boolean condition)
{
   loop statements...
}
```
![while](https://media.geeksforgeeks.org/wp-content/uploads/Loop1.png)

#### How it works?

- While loop starts with the checking of condition. If it evaluated to true, then the loop body statements are executed otherwise first statement following the loop is executed. For this reason it is also called Entry control loop.

- Once the condition is evaluated to true, the statements in the loop body are executed. Normally the statements contain an update value for the variable being processed for the next iteration.

- When the condition becomes false, the loop terminates which marks the end of its life cycle.


### For loop

for loop provides a concise way of writing the loop structure. Unlike a while loop, a for statement consumes the initialization, condition and increment/decrement in one line thereby providing a shorter, easy to debug structure of looping.
Syntax:

```javascript
for (initialization condition; testing condition;increment/decrement)
{
    statement(s)
}
```

![forloop](https://media.geeksforgeeks.org/wp-content/uploads/loop2.png)

#### How it works?

- Initialization condition: Here, we initialize the variable in use. It marks the start of a for loop. An already declared variable can be used or a variable can be declared, local to loop only.

- Testing Condition: It is used for testing the exit condition for a loop. It must return a boolean value. It is also an Entry Control Loop as the condition is checked prior to the execution of the loop statements.

- Statement execution: Once the condition is evaluated to true, the statements in the loop body are executed.
Increment/ Decrement: It is used for updating the variable for next iteration.

- Loop termination:When the condition becomes false, the loop terminates marking the end of its life cycle.