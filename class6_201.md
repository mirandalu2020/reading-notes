# Class Six Notes (201)

## Intro to Objects and the DOM

### Lecture Notes

- array can be a pain to keep track of when the data structure is large
- use object instead `let objectName = {key1: value1, key2: value2}`
- dot notation: `<objectName>.<keyName>` //quicker than bracket notation
- bracket notation: `<objectName>[<keyName>]` //can be used with keyName that contains spaces
- *Methods*: function objects that's assigned to an object, invoked with `.()` notation. Syntax: `objectName.functionName();`

- adding data dynamically to an HTML document with JS (window to the DOM)
- *step 1*: create an element (the order of the following steps can be swtiched)
- `let profileContainer = document.getElementbyID('elementID') //create the element`
- `let kittenArticle = document.createElement('article')) //create an <article> on JS`
- *step 2*: give it content
- `kittenArticle.textContent = "some text about the kitten"`
- *step 3*: append to DOM
- parent element in the DOM to append this new element to. Pass appendChild() the new element by its variable name
- `profileContainer.appendChild(kittenArticle); //this appends the new article element to the parent`

- `document.querySelector('article;nth-child(2) h3') //targeted h3 that's second child as an article element` any CSS selector can be included in the quotation marks

### JS Object Basics[^1]

- An JS Object is a collection of members that can be accessed when needed
- The advantage of wrting an object literal is that is an efficient way of transferring structured, related data items. 
- Objects are easier to work with than an array, as it does not need to accessed via index
- Bracket notation must be used when the value to be retrieved is held in a variable, similarly to calling a dictionary's primary key.
- `this`: keyword refers to the current object the code is being written inside.

> const dog = {
> name: 'Spot',
> age: 2,
> color: 'white with black spots',
> humanAge: function (){
> console.log(`${this.name} is ${this.age*7} in human years`);
>   }

- In the code above, the `this` refers to the object `dog`. The advantage of using `this` is that the dynamic argument wouldn't have to be hard-coded, and the code can be reused when the object name is updated. This can especially useful in the case of generic data name such as "Q1_20xx" or "Q2_20xx", etc.

### **Intro to the DOM**[^2]

- DOM: Document Object Model, is a programming interface for web documents that allows the programming language to interact with the page
- DOM is an API that is used to build websites, that can be accessed using JS

## Things I want to know more about

- How exactly does DOM work?

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics
[^2]:https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction
