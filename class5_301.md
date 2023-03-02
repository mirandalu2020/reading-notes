# Class Four Notes (301)

## Title

### Thinking in React[^1]

- The single responsibility principle: a component should only do one thing
- Static version of an application is the UI without interactivity. Use props, not state, state is meant for interactivity only.
- Once the static version is built, state can be introduced.
- To determine if something is state: 
  1. Is it passed in from a parent via props? If yes, then NOT state
  2. Does it remained uchanged over time? If yes, then NOT state
  3. Can you compute it based on other state or props? If yes, then NOT state

- To identify where state needs to live, identify the owner component or another component higher up in the hierachy, and that component should own the state. If neither makes sense to own the state, create a new component solely for holding the state.

### Higher Order Function[^2]

- Higher order function: functions that operate on other functions

>function greaterThan(n) {
> return m => m > n;
>}
>let greaterThan10 = greaterThan(10);
>console.log(greaterThan10(11));
>// → true

- Line 2 of the function given returns the value of m if m is greater than the value of n
- map() is a transofmration function that operates on the iterable of the original array, then output the new array with the values post-operation
- reduce() reduces a single from from an array, by repeatedly taking a single element from the array and combining it with the current value

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://reactjs.org/docs/thinking-in-react.html
[^2]:https://reactjs.org/docs/thinking-in-react.html
