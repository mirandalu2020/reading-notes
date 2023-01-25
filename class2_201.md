# Class Two Notes (201)

## Intro Continued

### **Lecture Notes**

- *Date types:primatives:*
- primativesthe building blocks of larger or more complex data types, structures
- basic form of data
- numbers, booleans, strings, null, undefined

### **Intro to HTML**[^1]

- *HTML Text Fundamentals: headings and paragraphs*
- `<p></p>` wraps around paragraphs, and `<h1></h1>` wraps around headings (there are total of 6 heading elements, no more than 3 should be used on the same page)

- Structures and semantic makes a webpage easier to be searched, and easier to be used with screen reader softwares. It also makes stypling with CSS and JavaSript easier

- description lists: mark up a set of items and their associated descriptions, used so the browser categorize the same styple with indent by default. Note that multiple description for one item is allowed
- `<abbr>` element can be used to wrap around abbreviation or acronym. Note the full expansion of the term in plain text must be included before using the abbreviations
- `<sup>` and `<sub>` are superscripts and subscripts. Usecases can include mathematical formulas, scientific notations, and chemical formulas. 

### **Intro to CSS**[^2]

- CSS can be applied to HTML in three ways: 1) external style sheet by linking using `<link rel="stylesheet" href="styles.css" />`; 2) internal stylesheet `<style>Styles goes here</style>`; 3) Inline styles: `<h1 style="color: blue; background-color: yellow: border: 1px solic black;">`, using inline styles is not recommended due to the inefficient maintanance process)

- in the following example: the CSS code starts with a selector `h2`, with declarations using the curly brackets, and the modified properties are `color` and `padding`,

> h2 {
> color: black;
> padding: 5px;
>}

### **Intro to JS**[^3]

- recall that a string can be enclosed in either single or double quotation marks
- recall JS operators include: addition `+`, subtraction `-`, multiplication `*`, division `/`, assignment `=`, strict equality `===`, and not `!` (and there are more, this is just some examples of commonly used ones)
- Functions can be used to build modifiable blocks. For instance if a website wants to display a graph, a table, and other properties of a mathematical equation, a function can be used to contain a given mathematical equation. Therefore the equation can be referenced using the function, such that if the equation is changed, all the relevant data can be updated at once.

- *Conditionals:*[^4]
- An if statement checks a condition and if it evaluates to true, then the code block will execute.
- `else if` is used when there's more than two conditions to be checked
- conditional operators: `===` and `!==` test if a value is strictly (or not stricktly identical; `<`,`>` test if one value is less or greater than another; `<=`,`>=` test if one value is less than or equal to, or greater than or equal to
- logical operator `&&` is a logical `AND`, which the expression would only evaluate to `true` all conditions must be true; `||` is a logical `OR`, which the expression would evaluate to `true` if one individual is evalueated to true

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals
[^2]:https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured 
[^3]:https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics
[^4]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals 