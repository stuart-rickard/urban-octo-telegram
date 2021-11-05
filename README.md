# Code Refactor Starter Code

## First Challenge for UC Berkeley Extension Full-Stack Developer Bootcamp Course

This website is the completed code for the first "challenge" of the course, refactoring html to be more accessible, which included these instructions:
* Use semantic HTML elements that follow a logical structure
* Include alt attributes for image elements
* Add a concise, descriptive title

## Refactoring That Was Done (and Not Done)

1. Changed title element to "Horiseon"
2. Added `alt-""` (empty) to the .png icons for Lead Generation, Brand Awareness, and Cost Management
3. Added `alt-""` with descriptions inside the quotes for the Search Engine Optimization, Online Reputation Management, and Social Media Marketing images.
4. I did not add an `alt` attribute for the hero image.  I spoke to a TA who said this was probably not intended to be part of the assignment.  In the original code, the hero image is ref'd through the style sheet.  If text is desired for this image, one way to do this would be to `ref` the image in the html instead of the style sheet and add `alt-""` code.  Another way would be to add `title=` to the `<div>` where the hero image is created via a `class=` reference, which would leave the `ref` in the style sheet, but the text behavior is different.
5. Changed `<div>` code to `<header>`, `<nav>`, `<article>`, `<footer>`, and `<aside>` semantic html code, where appropriate.
6. Updated the style sheet to reflect the change from `<div>` to `<nav>`.
7. Added `id=` tag to the search engine optimization article.  `id=` tags were already present for online reputation management and for social media marketing.
8. I noticed that Calibri is not in single quotes in the `font-family` coding in the style sheet.  Not certain that this was an error, I left it alone.
  
## Link to Live Refactored Code
  
The live refactored code can be found at this link: 
https://stuart-rickard.github.io/urban-octo-telegram/Develop/
