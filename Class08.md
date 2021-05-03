# Class08 

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Layout: 

#### Key Concepts in Positioning Elements: 

* Building Blocks: CSS treats each HTML element as if it is in its own box. This box will either be a: 
 
  1. Block-level elements: start on a new line. 
  2. Inline elements: flow in between surrounding text. 

* Containing Elements: If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. 

#### Controlling the Position of Elements: 

CSS has the following positioning schemes that allow you to control the layout of a page: 

1. normal flow: Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. 

2. relative positioning: This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.   

3. absolute positioning: This positions the element in relation to its containing element.

You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. 

1. Fixed Positioning: This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

2. Floating Elements: Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.

* Clearing Floats (clear): 

The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:

 1. left: The left-hand side of the box should not touch any other elements appearing in the same containing element.
 2. right: The right-hand side of the box will not touch elements appearing in the same containing element.
 3. both: Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element.
 4. none: Elements can touch either side. 

* Creating Multi-Column Layouts with Floats: 

Many web pages use multiple columns in their design. This is achieved by using a "<div>" element to represent each column. The following three CSS properties are used to position the columns next to each other:

 1. width: This sets the width of the columns.
 2. float: This positions the columns next to each other.
 3. margin: This creates a gap between the columns.

* Screen Sizes: Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

* Screen Resolution: Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

* Page Sizes: Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).

* Fixed Width Layouts: Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels. 

* Liquid Layouts: Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages. 

* Layout Grids: Composition in any visual art (such as design, painting, or photography) is the placement or arrangement of visual elements — how they are organized on a page. Many designers use a grid structure to help them position items on a page, and the same is true for web designers. 

* CSS Frameworks: CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating
printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.

#### Multiple Style Sheets: 

1. @import: Some web page authors split up their CSS style rules into separate style sheets. For example, they might use one style sheet to control the layout and another to control fonts, colors and so on. Some authors take an even more modular approach to stylesheets, creating separate stylesheets to control typography, layout, forms, tables, even different styles for each sub-section of a site. There are two ways to add multiple style sheets to a page:
 1. Your HTML page can link to one style sheet and that stylesheet can use the @import rule to import other style sheets.
 2. In the HTML you can use a separate "<link>" element for each style sheet.

2. link: On this page you can see the other technique for including multiple style sheets. Inside the "<head>" element is a separate "<link>" element for each style sheet. The contents of site.css are identical to styles.css on the left hand page, except the code does not contain @import rules. As with all style sheets, if two rules apply to the same element then rules that appear later in a document will take precedence over previous rules. 



