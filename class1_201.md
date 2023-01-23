# Class One Notes (201)

## Intro

### **How the Web Works**[^1]

- The website lives on a server, and the client is connected to the server by the internet
- The server is identified by an IP address, but the client uses Domain Name Server (DNS) to reach the IP address
- The server sends data in "packets" to the clients, which the packets are small chunks of the make-up of the website

### **Web Design Process**[^2]

1. Most importantly answer the question: what do I want to accomplish
2. Sketching the basic design
3. Decide on assets (texts, color, images, which can be found on Google, makes sure to filter for licenses)
4. Put them in code

### **Other Notes**

- create a string in JavaScript: enclose the texts in "" or '', make sure to stay consistent
- create a number in JavaScript: type the number (without quotation marks)
- use a variable: declared by `let` and can be used to store values that can also be updated
- metadata needs to be present to set the document's character encoding
- metadata stored in head can make the search results better found on search engine [^4]

### **Some Notes about HTML**[^3] [^5]

- HTML element: tags used to wrap and enclose different parts of the website's content. It's made up of an opening tag and a closing tang, and the contents are enclosed between the two tags
- HTML attribute: extra info of the element
- `<article>` vs `<section>`: `<article>` is designed to be independently reusable and redistributable; whereas `<section>` is just a generic standalone section of a document that has no sepecific element to represent the section, also heading is required for a `<section>`
- a typical website's elements: header, navigation bar, side bar, and footer
- `<h1>` headers are used to give the contents a role which is considered important for search engines. For instance, a header can be given on top of a `<span>` to give the block a heading, which makes it easier for search engines to identify key words
- benefits of using semantics: search engine optimization, easier to read code for develoopers, mirrors custom element/component naming

### **Some Notes about JavaScript**[^6]

- things that require JavaScript in a browser: dynamically modify HTML and CSS on the client side, update server-side note dynamically 
- JavaScript can be added to an HTML file in 3 ways: 1) internally, enclosed with `<script> JS goes here </script>`; 2) externally with `<script src="script.js"></script>`; 3) inline, directly to the HTML document (not recommended)

## Things I want to know more about


 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works
[^2]:https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like 
[^3]:https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#anatomy_of_an_html_element
[^4]:https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML 
[^5]: https://developer.mozilla.org/en-US/docs/Glossary/Semantics
[^6]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript 

