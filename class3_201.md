# Class Three Notes (201)

## More about HTML, CSS, and JS

### HTML, ordered and unordered lists[^1]

- an unordered list should be used when the list has no intrinsic ordering, and the order of the items do not matter; ordered list on the other hand, should be used when the listed items' order should not be changed, for instance: instructions for a procedure, rankings, etc. 
- the unordered list items' default bullet style can be changed using attribute `type` or CSS property `list-style-type`
- the ordered list items can be changed using `type` or CSS property `list-style-type`

### CSS - The Box Model[^2]

- margins are how far away one box if from the other box, and padding is the pads that "coats" box.
- HTML elements referrd in the article: `<span>`(inline by default and do not force line breaks), `<ul>`(set to inline-flex creates an inline box containing some flex items),`<h1>` and `<p>` have outer display type of block (box break onto new line, and width and height are respected

### JS

- *Arrays*[^3]
- Arrays: can be used to store various data types including strings, numbers, objects, other arrays, etc. Mixing data type is allowed. 
- The array in the example is a valid array. The values can be accessed by indecies

- *Expressions and Operators*[^4]
- Example short-hand assignment operators: 
- `+=` adds the result of the right operand and assigns the result to the variable; 
- `%=` divides the variable by the value of the right operand and assigns the remainder to the variable
- `&&=` only assigns if x is true
- `||=` only assigns if x is falsy
- in the example:

 >let a = 10;
 >let b = 'dog';
 >let c = false;
 >(a + c) + b; //evalueates to "10dog"

- *conditional statements and loops*[^5] [^6]
- A real world conditional statement can be: a test-taker is now allowed to go to the next page unless he/she inputs the name and tester ID
- a loops is useful in JavaScript is when someone is trying to input a passowrd, and the person should not have access to account until he/she has the password correct

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## Things I want to know more about

I want to see how everything come together with loops and conditional statement. So far I have a pretty boring website and I hope to make it better and have a more smooth presentation. 

## References

[^1]:https://developer.mozilla.org/en-US/docs/Web/HTML
[^2]:https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model 
[^3]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays 
[^4]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators
[^5]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals 
[^6]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code
