# Class03 

[Return to home page](https://momansi96.github.io/reading-notes/). 


## Lists. 

#### Ordered Lists: 

1. "<ol>": The ordered list is created with this element.
2. "<li>": Each item in the list is placed between an opening "<li>" tag and a closing "</li>" tag. (The li stands for list item). 

#### Unordered Lists: 

1. "<ul>": The unordered list is created with the "<ul>" element.
2. "<li>": Each item in the list is placed between an opening "<li>" tag and a closing "</li>" tag. (The li stands for list item). 

#### Definition Lists: 

1. "<dl>": The definition list is created with the "<dl>" element and usually consists of a series of terms and
their definitions. Inside the "<dl>" element you will usually see pairs of "<dt>" and "<dd>" elements.

2. "<dt>": This is used to contain the term being defined (the definition term).

3. "<dd>": This is used to contain the definition.

#### Nested Lists: 

You can put a second list inside an "<li>" element to create a sublist or nested lists. 


## Boxes. 

#### Box Dimensions (width, height): 

By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties. The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size. 

#### Limiting Width (min-width, max-width): 

Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide. 

#### Limiting Height (min-height, max-height): 

In the same way that you might want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the min-height and max-height properties.

#### Overflowing Content: 

The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:

1. hidden: This property simply hides any extra content that does not fit in the box.
2. scroll: This property adds a scrollbar to the box so that users can scroll to see the missing content.

#### Border, Margin & Padding: 

Every box has three available properties that can be adjusted to control its appearance:

1. Border: Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.
2. Margin: Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.
3. Padding: Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

#### Border Width (border-width): 

The border-width property is used to control the width of a border. The value of this property can either be given in pixels or using one of the following values: (thin, medium, thick). 

#### Border Style (border-style): 

You can control the style of a border using the border-style property. This property can take the following values:
1. solid: a single solid line. 

2. dotted: a series of square dots (if your border is 2px wide, then the dots are 2px squared with a 2px gap between each dot). 

3. dashed: a series of short lines. 

4. double: two solid lines (the value of the border-width property creates the sum of the two lines).

5. groove: appears to be carved into the page. 

6. ridge: appears to stick out from the page. 

7. inset: appears embedded into the page. 

8. outset: looks like it is coming out of the screen. 

9. hidden / none no border is shown. 

#### Border Color (border-color): 

You can specify the color of a border using either RGB values, hex codes or CSS color names. 

#### Shorthand (border): 

The border property allows you to specify the width, style and color of a border in one property (and the values should be coded in that specific order).

#### Change Inline/Block (display): 

The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page. The values this property can take are:

1. inline: This causes a block-level element to act like an inline element.

2. block: This causes an inline element to act like a block-level element.

3. inline-block: This causes a block-level element to flow like an inline element, while retaining other features of a block-level element.

4. none: This hides an element from the page. In this case, the element acts as though it is not on the page at all.

#### Hiding Boxes (visibility): 

The visibility property allows you to hide boxes from users but It leaves a space where the element would have been. This property can take two values:

1. hidden: This hides the element.

2. visible: This shows the element.

#### ARRAYS: 

An array is a special type of variable. It doesn't just store one value; it stores a list of values. You should consider using an array whenever you are working with a list or a set of values that are related to each other. Arrays are especially helpful when you do not know how many items a list will contain because, when you create the array, you do not need to specify how many values it will hold. 

You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array). The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.

Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one). Each item in an array is automatically given a number called an index. This can be used to access specific items in the array. 

#### SWITCH STATEMENTS: 

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

#### TYPE COERCION & WEAK TYPING: 

If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error. JavaScript can convert data types behind the scenes to complete an operation. This is known as type coercion. 

#### TRUTHY & FALSY VALUES: 

Due to type coercion, every value in JavaScript can be treated as if it were true or false; and this has some interesting side effects. 

1. Falsy values are treated as if they are fa 1 se. The table to the left shows a hi ghScore variable with a series of values, all of which are falsy. Falsy values can also be treated as the number 0 .

2. Truthy values are treated as if they are true. Almost everything that is not in the falsy table can be treated as if it were true. Truthy values can also be treated as the number 1.

#### CHECKING EQUALITY & EXISTENCE: 

Because the presence of an object or array can be considered truthy, it is often used to check for the existence of an element within a page, A unary operator returns a result with just one operand. Here you can see an if statement checking for the presence of an element. If the element is found, the result is truthy, so the first set of code is run. If it is not found, the second set is run instead.

#### SHORT CIRCUIT VALUES: 

Logical operators are processed left to right. They short-circuit (stop) as soon as they have a result - but they return the value that stopped the processing (not necessarily true or fa 1 se). 

## Loops

Loops check a condition, it returns true a code block will run, then the condition will be checked again and if it still return true the code block will run again, it repeates until the condition returns false.  

- There are several types of loops such as: 

1- For loop: it is used to run a code specific number of times, the condition is usually a counter which is used to tell how many times the loop should run.   

A for loop is consisted of three parts which is: 

- Initialization: create a vaariable and sit it at a starting point it is usually referred to as "i". 

- Condition: the loop should continue to run until the counter reaches a specified number. 

- Update: every time the loop has run there is an updat on the variable. 

2- While loop: if you don't know how many times you should run the loop a while loop is the best to use. 


