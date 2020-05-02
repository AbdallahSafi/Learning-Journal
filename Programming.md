# Programming with JavaScript

## What is a script and how do I create one ?

A script is a series of instructions that a computer can follow to achieve a goal. To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.

## Designing a script tasks

When you pick a goal for your software if it's personal project or you working on project for client you should break down that goal into tasks to always achieve them.

You can consider talking to the client to write down the tasks to achieve that goal. Then you probaply would like to draw a flowchart to see things clearly.

see this example of a flowchart that describs the tasks of solving problem related to a lamp not working

![lamp](https://www.conceptdraw.com/How-To-Guide/picture/samples-of-flowchart.png)

there is a big task you con break it down to steps. These steps are the foundation stones
of your software. So after you define your steps you can go to coding. But you might consider that computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.

## Javascript basics

### Expressions

An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.

1. Expression that just assign a value to a variable.

`var color = 'beige';`

2. Expression tht use two or more values to return a single value.

`var area = 3 * 2;`

 Expressions rely on things called operators; they allow programmers to create a single value from one or more values.

#### Arithmetic Expressions:
Arithmetic expressions evaluate to a numeric value. Examples include the following

```javascript
10;     // Here 10 is an expression that is evaluated to the numeric value 10 by the JS interpreter
10+13; // This is another expression that is evaluated to produce the numeric value 23
```

#### String Expressions:
String expressions are expressions that evaluate to a string. Examples include the following

```javascript
'hello';
'hello' + 'world'; // evaluates to the string 'hello world'
```

#### Logical Expressions:
Expressions that evaluate to the boolean value true or false are considered to be logical expressions. This set of expressions often involve the usage of logical operators && (AND), ||(OR) and !(NOT). Examples include

```javascript
10 > 9;   // evaluates to boolean value true
10 < 20;  // evaluates to boolean value false
true;     //evaluates to boolean value true
a===20 && b===30; // evaluates to true or false based on the values of a and b
```

### Functions

Quite often we need to perform a similar action in many places of the script. For example, we need to show a nice-looking message when a visitor logs in, logs out and maybe somewhere else.

Functions are the main “building blocks” of the program. They allow the code to be called many times without repetition.

#### Function Declaration
To create a function we can use a function declaration.
It looks like this:

```javascript
function showMessage() {
  alert( 'Hello everyone!' );
}
```
The function keyword goes first, then goes the name of the function, then a list of parameters between the parentheses (comma-separated, empty in the example above) and finally the code of the function, also named “the function body”, between curly braces.

```javascript
function name(parameters) {
  ...body...
}
```
Our new function can be called by its name: showMessage().
For instance:

```javascript
function showMessage() {
  alert( 'Hello everyone!' );
}
showMessage();
showMessage();
```

The call showMessage() executes the code of the function. Here we will see the message two times.
This example clearly demonstrates one of the main purposes of functions: to avoid code duplication.
If we ever need to change the message or the way it is shown, it’s enough to modify the code in one place: the function which outputs it.