# Class Three Notes (201)

## More about HTML, CSS, and JS

### *Lecture Notes*

- recall: how to use template literal: enclosed in `` and use ${this is a varaible}

> `string ${this is a variable} more string characters`

- **Arrays**
- list of elements/items. Each element has an index start at [0] (the [0]is pronounced at index zero)

- **For Loops**
- The code will continue to execute as long as the condition is `true`
- Steps:
    1. initiate the variable (ex. a counter i, stands for iterator)
    2. evaluate the variable (the condition `i < parkNRec.length`>)
    3. increment the counter (i++, which is equivalent of i = i+1)

> for (let i=0; i < parkNRec.length; i++>) {
>    //code executes here
>  }

- update an array: arrayName[index] = "value" //attache the value if the index is not present, update the value if index does exist
- method 2: arrayName[index].push("value 1", "value2", "value3") //value attached to the end of the array
- arrayName.unshift('newValue'); //adds the elemet to the front of the array, shift all the other indecies

- **CSS Box Model**
- avoid extra math when setting box sizes

>* {
>    box-sizing:border-box;
> }

- almost all HTML elements default to display: black or displau online
- take up the entire width of their parent. will know any sigbling elements to the next line.

- **Inline**
- only the width of their content and they flow wih the content around tham
- `<span>`: no top/bottom margins, inline elements, flow with the content

- **Block**
- take up the entire space available (width of the parent element)
- `<div>` for instance will take up the entire space available regardless of the width, unless specified to be changed to `display: inline-block`

- **float**
- can be cleared with `clear:both;`

- **CSS selectors**
- example: 

> `div-hover` {
>   color: green
> }     /*color changed to green when hovered over the element selected

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
