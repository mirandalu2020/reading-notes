# Class Three Notes (301)

## Passing Functions as Props

### List and Keys - React[^1]

- .map() returns an array that's been iterated through and operated on
- A loop can be used to loop through an array using {}
- East list item needs a unique key among siblings (not globally)
- The purpose of the key is how React keeps track of which items have changed, added, or removed

### The Spread Operator[^2]

- The spread operator is`...arr` that expands an iterable object arr ito the list of arguments
- The spread operator can: spreads an array into separate arguments, copy an array, using an array as arguments, and add to state in React
- Arrays can be concatenated by `[...array1, ...array2]`
- New item can be added to an array using `[item1, item2, ...array]`
- Objects can be combined into an array using `[...object1, ...object2]`

### Pass Functions between Components[^3]

- The first step to pass functions between components is: to set the initial state of the parent component
- An increment function updates the value of the state of the object by one
- The child component invoke a method from its parent by adding the state to the parent, and refer to the parent in the method


In your own words, what does the increment function do?
How can you pass a method from a parent component into a child component?
How does the child component invoke a method that was passed to it from a parent component?

## Things I want to know more about


 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://reactjs.org/docs/lists-and-keys.html
[^2]:https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab
[^3]:https://www.youtube.com/watch?v=c05OL7XbwXU
