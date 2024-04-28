"# Advance-CSS" 


Embark on an exhilarating learning journey with my GitHub project, NATOURS! Created with the aim of mastering advanced CSS and Sass, this project serves as a playground for honing skills in complex CSS animations, responsive design techniques, and cutting-edge layout frameworks like flexbox. Diving deep into the world of web development as I explore the intricacies of CSS architecture and fundamental concepts. Join me on this exciting adventure of growth and discovery!

<!-- Used rem instead of px: -->

~ rem (root em) units are relative to the root (html) font size.
~ rem units help create a more responsive design.
~ 1rem = 16px 
~ To calculate rem from px,  divide the pixel value by the root font size,
10px would be 10/16 = 0.625rem
20px would be 20/16 = 1.25rem
30px would be 30/16 = 1.875rem

<!-- Used BEM  -->

~ BEM (Block Element Modifier) is a popular naming convention in CSS architecture.

~ Block (block):
Represents a standalone component that is meaningful on its own. Example: .button, .navbar, .card

~ Element (block__element): Names of elements are written in lowercase and are separated from the block by two underscores.
Example: .button__text, .navbar__link, .card__title

~ Modifier (block--modifier or block__element--modifier): Names of modifiers are written in lowercase and are separated from the block or element by two hyphens.
Example: .button--primary, .button--large, .card--featured, .card__title--small
