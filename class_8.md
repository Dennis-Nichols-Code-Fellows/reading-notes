# Operators and Loops

## [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

### Expressions

An **expression** is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

For example , `x =dog` is an expression that has the effect of assigning a string to the variable x.

While `3+8` is an expression which will simply eval to 11.

All expressions are joined by **operators**. See [class 7 notes](https://dennis-nichols.github.io/reading-notes/class_7) for more on these.

### [Operator precedence](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)

**Operator precedence** determines which parts of a complex expression evalutate fist. For example, in the expression `x = 1 + 2 * 4` the multiplication operation evaluates first and then the addition operation. You can override operator precedence using parentheses just like you may be used to from math class.

### More on operators

The different types of operators are also classed based on how many values they operate on (operands).

*Unary* operators take one operand.

-*prefix* operators come before the operand (this is most types of unary operators)
-*postfix* operators come after the operand. The only cases of these are `++` and `--`, the increment and decrement operators.

-*binary* operators take 2 operators and come in between.

-*tertiary* operator -> there's only one of these and it's called the conditional operator.

There are **many** different types of **assignment operators**. These assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

There are many more complex (and useful) assignment operators such as `x += f()` which assigns a value of `x + f(x)` to `x`.

A **comparison** operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values.


## [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

Loops offer a quick and easy way to do something repeatedly. 

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

### For loops

A for loop repeats until a specified condition evaluates to false.

1. The initializing expression (`i = 0`) , if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression (`i <10`)is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
4. If present, the update expression incrementExpression (`i++`)is executed.
5. Control returns to Step 2.

### While loops

A while statement executes its statements as long as a specified condition evaluates to true.

    while (condition)
        statement

If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

