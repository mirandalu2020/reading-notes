# Class Seven Notes (201)

## More on Object-Oriented Programming, HTML Tables

### Lecture Notes

- constructor functions: using functions to create Objects

> function ConstructorFunction(x) {
>   this.x = value0;
>   this.a = value1;
>   this.b = value2;
>   this.newFunction = function() {
>    //code to be part of the function};  
}
> }

> // we use the keyworkd `new` to create a new instance of the construtor function
> let xxx1 = new ConstructorFunction();
> let xxx2 = new ConstructorFunction();
> //output would contain the keyworkd `ConstructorFunction`

> //create new properties of the constructorFunction for one object
> variable.newInstance = 'a string'

> create new properties for all objects created, use keyworkd `prototype`
> ConstructorFunction.prototype.newInstance = 'a string'


> use a for-loop to invoke all student at once
> let array = [array[0], array[1],array[2]]; //create instances of items to be iterated
> for (let i=0; i < array.length, i++) {array[i].newFunction()};

### Domain Modeling[^1]

- Domain modeling models a problem, such that there's a direction to find the solutions

### HTML Table Basics[^2]

- Tables should be used as they are very readable, and they are accessible to screen reader clients, so it's helpful for visually impaired users
- Examples of `<table>` semantic tags include: `<th>` (table headers), `<td>` (table data), `<colspan>`, `<rowspam>`

### Intro to Constructors[^3] [^4]

- A *Constructor* is a function called using the `new` key word, such that a new object will be creaetd
- `this` can be used to bind to the constructor code and refer to itself
- examples of a prototype: I used to have to make chemical models before running the experiment. More basic scientific experiment required me do prototype the reaction on paper, more advanced ones requires programming

## Things I want to know more about

- how to make my code from lab6 more clean?

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://github.com/codefellows/domain_modeling#domain-modeling
[^2]: https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics
[^3]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors
[^4]:https://ui.dev/beginners-guide-to-javascript-prototype 