# Class Seven Notes

## Programming with JavaScript

### **Intro**[^1] [^2]

- Control Flow: the order of how the computer executes statements in a script
- JavaScript Function Syntax:

> function name(parameter1, parameter2, parameter3) {
> //code
> }

- Function invocation (function calls): 1. event occurance; 2. explicitly called; 3. automatically (self invoked)
- Function must be invoked with () operator to obtain results, or only the function object will be returned
- Function return: function stops executing when  `return` statement is reached
- Functions can be used as variable values

### **Operators**[^3] [^4]

- **Arithmetic operators:**`+`, `*`, `-`,`/`,`**`,`%`(remainder),`++` (increment),`--` (decrement)
- **Assignment operators:** `=`,``+=` (x +=y same as x=x+y0), `-=`, etc.
- `+` and `+=` operator can be used to concatnate strings
- **Comparison Opeartors:** `==`,`===` (equal value and type),`!=` not equal, `!==` not euql value OR not equal type; `?` ternary operator
- **Logical operators:** `&` logical and, `||` logical or, `!` logical not
- **Type Operators:** `typeof`, `instanceof`(returns true if an object is an instance of an object type)
- **Bitwise Operators:**`&`= AND, `|` = OR, `~` = NOT, `^` XOR (5^1 same as 0101^0001 resulting in 0100 with Decimal 4), `<<` left shift, `>>`right shift, `>>>>` unsinged right shift
- **Conditional (ternary) operator:** `condition ? val1 : val2`; where if condition is true, the operator has the value of val1, otherwise it has a value of val2
- **Comma Operator:** evaluates both of its operands and returns the value of the last operand (mostly used in a for-loop)
- **Relational Operators:** `in` returns true if the specified prperty is in the specified object; `instanceof` returns true if the specified object is of the specified object type
- **Unary Operators:** `delete` deletes an object's property or array elements; `typeof` returns a string indicating the type of the unevaluated operand; `void` specifies an expression t be evaluated without returning a value (Paranthese surrounding the expression is optional)

## Things I want to know more about

How to incorporate my JavaScript with HTML and CSS?

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Glossary/Control_flow
[^2]:https://www.w3schools.com/js/js_functions.asp
[^3]:https://www.w3schools.com/js/js_operators.asp
[^4]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators
