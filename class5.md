# Class Five Notes

## Intro to CSS

### **Vocab**

- CSS - Cascading Style Sheets (rule-based language separate from HTML)
- select element methods: by id (with #) or by class selectiors, which are identified in HTML by `<element class="class-name"> or <element id="id-name">`

>           by id 
>           #id {
>                float: left;
>           }
>
>        by class selector
>            .class selector {
>                float: left;
>        }

### **Things to note (CSS basics)**[^1]

- Specifying groups of styles that to be applied, ex.

>       selector {
>        declaration1: value;
>        declaration 2: value
>           }

- CSS is broken down into modules (ex. backgrounds and borders)
- CSS 
is only useful if the brower implements the feature

### **How to insert CSS**[^2]

- External CSS: change just one external file, and HTML refereces to the CSS file (ex. `<link rel = "stylesheet" href="xxx.css">`)

*external CSS file should not contain any HTML tags, and there is NO space between the property value and the unit*.

- Internal CSS: used if one HTML page has a unique style, the style is defined inside the `<style>` element, for ex.

>     <style>
>        body {
>            declaration:value;
>        }
>        h1 {
>        declaration: value;
>        declaration: value;
>        }
>        </style>

- Inline CSS: apply the style to a single element (ex. `<h1 style="declaration:value;declaration:value">heading</h1>`)

*Note: if multiple styles sheets were defined for the same element, the last style sheet will be used
*Note: if multiple style in a page is speified, the priority hierarchy is: inline --> external and internal style sheets --> browser default.

### CSS Color amd Property[^3]

Color can be a color description(ex. red, green), a hex(#xxxxxx) value, or RGB (rgb(0,0,255))

## Things I want to know more about

How to make the page move according to the display size of my browser?

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS
[^2]:https://www.w3schools.com/css/css_howto.asp
[^3]:https://www.w3schools.com/cssref/pr_text_color.php