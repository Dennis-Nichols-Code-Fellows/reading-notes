# Programmming with Javascript

## [MDN Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

**Control flow** is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the structures that change the control flow, such as *conditionals* (`if` and `else`), *loops* (`for` and `while`), and *functions*.

## [Functions](https://www.w3schools.com/js/js_functions.asp)

A JS function is a block of code designed to perform a specific function.

### Basic function syntax and behavior

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

The code to be executed, by the function, is placed inside curly brackets: {}

    function wagTail(param1, param2) {
        //tail wagging code
    }

Function **parameters** are listed inside the parentheses () in the function definition.

Function **arguments** are the values received by the function when it is invoked.

The code inside the function will execute when "something" invokes (calls) the function:

1. When an event occurs (when a user clicks a button)
2. When it is invoked (called) from JavaScript code
3. Automatically (self invoked)

The function will stop executing when it reaches a `return` statement -> this causes the function to give back some value to the  **caller**, that is to whatever invoked the function in the first place.

Functions can be used the *same way as you use variables*, in all types of formulas, assignments, and calculations.

## [Operators](https://www.w3schools.com/js/js_operators.asp)

Operators are symbols that are shorthand for the types of operations to be performed on 2 (or more) values. The values may be numbers, variables, strings, etc.

**Arithmetic operators** &rarr; These perform operations on numerical values.

**Assignment operators** &rarr; These operate on variables.

**String operators** &rarr; These operate on strings.

**Comparison operators** &rarr; These compare 2 different values and re.

**Logical operators** &rarr; Are like comparison operators, but take boolean values and return boolean values.
