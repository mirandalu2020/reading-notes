# Class Two Notes (301)

## State and Props

### React Lifecycle[^1]

- Three phases of the component lifecycle: mounting, updating, unmounting

- render takes place before componentDidMount
- the very first thing happens in the react lifecycle is the constructor
- constructor --> react updates --> render --> componentDidMount --> componentWillUnmount
- `componentDidMount()` is invoked after a component is mounted, where DOM initialization goes

### React State vs Props[^2]

- Props works like passing arguments to a function, like what the component is intended to take, where props can change but not the componenet, so the component can be re-rendered with different contents
- State is handled (and updated) inside of a component, versus props are handled outside of the commponent (like a variable that can be changed)
- An application is re-rendered when the information is dynamic
- Things needs to be updated will be stored in a state, such as counter

When do we re-render our application?
What are some examples of things that we could store in state?

## Things I want to know more about

How to use JS functions, constructors inside react when I am trying to render the page?

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093
[^2]:https://www.youtube.com/watch?v=IYvD9oBCuJI