# Read07 

[Return to home page](https://momansi96.github.io/reading-notes/).

## Introducing CSS: 

- The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

- BLOCK & INLINE ELEMENTS: 

 1- Block level elements look like they start on a new line.

 2- Inline elements flow within the text and do not start on a new line. 

- CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.

- CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

- CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one  declaration, each separated by a semi-colon. 


#### CSS Selectors: 

There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document such as: 

1- Universal Selector: Applies to all elements in the
document. (* {}).

2- Type Selector: Matches element names. (h1, h2, h3 {} ). 

3- Class Selector: Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol. (.note {} ). 

4- ID Selector: Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol.  (#introduction {}). 


#### How Css Rules Cascade? 

If there are two or more rules that apply to the same element, it is important to understand which will take precedence: 

1- LAST RULE: If the two selectors are identical, the latter of the two will take precedence.

2- SPECIFICITY: If one selector is more specific than the others, the more specific rule will take precedence over more general ones. 

3- IMPORTANT: You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.


## Color: 


#### Foreground Color: 

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

1- rgb values: These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
 
2- hex codes: These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash #sign. For example: #ee3e80

3- color names: There are 147 predefined color names that are recognized by browsers.

#### Background Color: 

CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box, You can specify your choice of
background color in the same three ways you can specify
foreground colors, If you do not specify a background color, then the background is transparent. 

#### Contrast: 

When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

1- Low Contrast: Text is harder to read when there is low contrast between background and foreground colors. 

2- High Contrast: Text is easier to read when there is higher contrast between background and foreground colors.

3- Medium Contrast: For long spans of text, reducing the contrast a little bit improves readability.




