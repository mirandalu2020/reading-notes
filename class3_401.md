# Class Three Notes (401)

## Express REST API

### ES6 Classes[^1]

- Classes are a template for creating objects, and they are not hoiseted.
- The keyword `this` is a pointer to an object inside the class, it refers to specific methods or properties that are defined inside the class. Arrow funcions do not carry their own `this`, so it will always point to its parents properties or methods. 

### Express Routing[^2]

- Within Express, routing refers to how an applications's endpoints (URIs) respond to client requets.
- A route path defines the endpoints a twhic requets can be made, whereas route methods are the HTTP request methods.
- When there's are callback functions to be skipped if a specific event happens, `next` is an appropriate parameter to be added to the route handler. A call back function must be specified if `next` has been passed to the middleware.

### Express Router[^3]

- Express router lets us routing APIs with .use, .get,. .para., and route. 
- We initialize express.Router() when we apply routes and tell the applciation to use those routes.
- Route middleware allows something to be done before a request is processed, such as input validity, authentication, data logging, etc. 

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes
[^2]:https://expressjs.com/en/guide/routing.html
[3]:https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4
