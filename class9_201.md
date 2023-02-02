# Class Nine Notes (201)

## HTML Forms and Intro to Events

### HTML Forms[^1]

- Forms are important because it allows the user to interact witht he website
- For better user experience, the bigger the form, the more risk it is to frustrate and lose users. It's better to keep the form simple and focused
- *Elements used in a web form:*[^2]
- `<form>`(required element to start a form, which defines a form and attributes that determines the behavior of the form_; 
- `<fieldset>`(create groups of widgets that share the same purpose); 
- `<legend>`(formally describes the purpose of the purpose of a fieldset);
- `<label>`: formal way to define a label for an HTML form widget, important to build accessible forms
- `<input>`: bridged by attribute of `for` from `<label>`, allows user to edit text

### **JS Events**[^3]

- JS `Events` are signals produced by the program that happen when a specific event take place, examples includes when the user selects, clicks, or hovers over a certain area of the web page
- The `addEventListener()` takes the arguements of the name of the events that will take place, and what the event should be (a function of the event)
- An `event object` automatically passed to even handlerse to provide extra features and info, the target is useful because it references to the element the event occures upon, so the event does not occur to other unintended elements
- *Event Bubbling* is how the browser handles events targeted at nessted elements, where the event *bubbles up*;
- *Event Captureing* is the reversed order of Event Bubbling, which is disabled by default, unless the `capture` option is passed in `addEventListener()` (ex: addEventListener())

## Things I want to know more about

- How do I add a cover page and let the page automatically fade as the user scrolls down the page? Is that event bubbling?

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form
[^2]:https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form
[^3]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events