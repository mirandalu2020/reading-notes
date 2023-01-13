# Class Eight Notes

## Loops

### Lecture

- `for` loops: evaluate a preset amount of times before breaking
- `while` loops: evaluate an infinetely amount of times

### **Expressions and Operators**[^1]

- Operator Operand form: prefix unary operator (most cases in JavaScript, ex. !, typeof)
- Operand Operator form: postfix unary operator (only `++` and `--` in JS)
- if an expression evaluate to an object, the left-hand side of an assginment expression may make assignments to properties of that expression
- Destructuring: extract data from arrays or objects using a syntax that mirrors the construction (ex. `const one = foo [0]`, `const two = foo[1]`, with destructing: `const [one, two] = foo`)
- Right Associative: evaluates from left to right
- (Expressions) `this` refers to current object; 
- (Expressions) **Grouping Operator:** `()` Parentheses creates a grouped expression; `new` create an instance of a user-defined object type; `super` call functions on an object's parent

### **Loops**[^2]

- doing something repeadly
-`for` statement:

> for ([initialExpression];[conditionExpression];[incrementExpression]) statement

- `for ... in` statement ()

> for (variable in object)
> statement

- *note:* for an Array, it is better to use `for` instead of `for...in`, since the name of user-defined properties in additional to the numeric indexes will be returned

- `do...while` statement: repeats until a specified condition evaluates to false

> do, is the condition is false, statement within the loop stops executing
> statement //always executed ONCE before the condition is checked, use `{}` to group the statements
> while (condition); //further executes if returned true

- `while`: condition test occurs before statement

> while (condition)
> statement

- `break` statement: terminate a loop. Can be used with a label (terminates the specified labeled statement) or without labels (terminates the innermost enclosing while, do-while, for, or switch)

- `continue` statement: restart a loop (can be used with or without label)

## Things I want to know more about


 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators
[^2]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration