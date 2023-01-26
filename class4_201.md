# Class Four Notes (401)

## Layouts and Hyperlinks

### HTML Hyperlinks[^1]

- hyperlinks are wrapped inside of the `<a>` element;
- the `href` attribute contains the web address
- a hyperlink is more accessible to users when link wording is clear, so screen readers have the freedom to jump around from link to link, search engine can better locate index target files, and visual readers can quickly skim over the webiste

### CSS Normal Flow[^2] [^3]

- *Normal Flow* is the way that webpage elements lay themselves out by default
- *Block level elements* content fills the available space of the parent element, and the element grows long the block dimention (horizontally). Each element appear on a new line
- *inline elements* have the size of their content, no height or wedth can be set (except for images) unless changed by using `display:block` or `display: inline-block`. Note that inline elements do NOT appear on new lines, they all sit on the same line along any adjacent or wrapped text content as long as there's space
- *Margin collapsing*: when two vertically adjacent elements both have a margin set on them and their margins touch, the larger margin remains while the smaller one disappears (only relevanet to vertical direction)

- *Positioning:* takes elements out of normal document flow and make them behave differently. Static positioning is the default of all elements
- Absolute positioning: specify the distance the element should be from each of the containing element's sides. So we have the advantage of being able to create isolated features that don't interfere with the layout of other elements
- Fixed positioning: fixes an element in place relative to the visible portion of the viewport, and the element persist regardless of how the page scrolls (similar to Excel FreezePane)

### JS Functions[^4]

- Function declaration is when a function is created and declared; function invocation is when a function is called (to use)
- Parameter are sometime. s called arguments (or properties, or attributes)

### The Benefits of Pair Programming[^5]

- Benefit 1: practice the communication skill in code, that includes listening, speaking, reading, and writing
- Benefit 2: despite it may take longer to complete a project, the code tend to be higher quelity and requires less troubleshooting and debugging. 

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

### Things I want to know more about

- How do I create multiple pages and link them together? How do I create a site and the boxes don't move around when I shrink the page?

## References

[^1]:https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks
[^2]:https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow 
[^3]:https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning 
[^4]:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions
[^5]:https://www.codefellows.org/blog/6-reasons-for-pair-programming/

