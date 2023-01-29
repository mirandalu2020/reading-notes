# Class Five Notes (201)

## Lecture Notes

- `.splice()`: change the value in the middle of an array, it takes in at least 2 arguments in the following order `.splice(item you wnt removed, number of total items to be removed)`, additional items can be attached after the first 2 items by name

- `git branch` see what branch I am at
- `git checkout -b <branch name>`: create and move to new branch

## Images, Color, Text

### HTML Media[^1] [^2]

- `alt` is used as a alternate text to be displaed when the image cannot be properly displayed (ex. misspelled filename). One real world application is for screen readers or browsers that don't support images.
- Images can be made more accessible by adding captions `<figcaption>`, or adding titles (as a `title` attribute inside the `<img>` element)
- `<figure>` should be used as semantic element to contain figures, and `<figcaption>` is telling the browser the texts entered are captions for the figure embedded.
- A `gif` is an animated image, and a `svg` is an image casted using math, so when compressed or enlarged, no pixelated "dots" appears
- `PNG` should be used since it can better reproduce the original image, especially when there's texts present. Since a screenshot is likely a smaller version of the original image

### Color and Styling in CSS[^3] [^4]

- A background color colors the backgroud of the HTML element (what's behind the HTML box), while the foreground coor of the element colors the content itself (what's inside the HTML box)
- I would use a light background color for the body of the website, a slightly darker, but transparent color for the footer. And the contents I may or may not add color to, depending on the layouts. I might also add colors when mouse is hovered over to elements with hyperlinks.
- When selecting a font, the font-family should be readable and supported by most brosers.
- In HTML, `font-size` changes the size of the text, `font-weight` changes how much the text to be bolded, and `font-style` allows the style such as bold, italic, etc.
- The `<h1>` element can have extra spce by changing the `line height` to the font properties, or by changing the padding/margin of the entire element

## Things I want to know more about

- How do I move boxes in a list so it's not bottom-aligned?

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML 
[^2]:https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types 
[^3]:https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color
[^4]:https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color
