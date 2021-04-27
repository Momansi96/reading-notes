# Class04 

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Links: 

#### Writing Links: 

Links are created using the "<a>" element. Users can click on anything between the opening "<a>" tag and the closing "</a>" tag. You specify which page you want to link to using the href attribute.

#### Linking to Other Sites: 

Links are created using the "<a>" element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link. Users can click on anything that appears between the opening "<a>" tag and the closing "</a>" tag and will be taken to the page specified in the href attribute. When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL. 

#### Linking to Other Pages on the Same Site: 

When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL. If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file. If you have different pages of a site in different folders, then you can use a slightly more complex syntax to indicate where the page is in relation to the current page. 

#### Directory Structure: 

On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.

* Structure: The top-level folder is known as the root folder. The root folder contains all of the other files and folders for a website. Each section of the site is placed in a separate folder; this helps organize the files.

* Relationships: The relationship between files and folders on a website is described using the same terminology as a family tree.

* Homepages: The main homepage of a site written in HTML (and the homepages of each section in a child folder) is called "index.html". Web servers are usually set up to return the index.html file if no file name is specified.

#### Relative URLs: 

Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

When you are linking to a page on your own website, you do not need to specify the domain name. You can use relative URLs which are a shorthand way to tell the browser where a page is in relation to the current page. This is especially helpful when creating a new website or learning about HTML because you can create links between pages when they are only on your personal computer (before you have got a domain name and uploaded them to the web).

#### Email Links: 

mailto: To create a link that starts up the user's email program and addresses an email to a specified email address, you use the "<a>" element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to. On the right you can see that an email link looks just like any other link but, when it is clicked on, the user's email program will open a new email message and address it to the person specified in the link. 

#### Opening Links in a New Window: 

If you want a link to open in a new window, you can use the target attribute on the opening "<a>" tag. The value of this attribute should be _blank. One of the most common reasons a web page author might want a link to be opened in a new window is if it points to another website. In such cases, they hope the user will return to the window containing their site after finishing looking at the other one.

#### Linking to a Specific Part of the Same Page: 

At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top.

Before you can link to a specific part of a page, you need to identify the points in the page that the link will go to. You do this using the id attribute (which can be used on every HTML element). 

The value of the id attribute should start with a letter or an underscore (not a number or any other character) and, on a single page, no two id attributes should have the same value.

To link to an element that uses an id attribute you use the "<a>" element again, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to.

#### Linking to a Specific Part of Another Page: .

If you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique. As long as the page you are linking to has id attributes that identify specific parts of the page, you can simply add the same syntax to the end of the link for that page. Therefore, the href attribute will contain the address for the page, followed by the "# symbol, followed by the value" of the id attribute that is used on the element you are linking to.

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


## Functions, Methods, and Objects: 

#### WHAT IS A FUNCTION? 

Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements). 

* Declaring a function: 

To create a function, you give it a name and then wright the statements needed to achieve its task inside the curly braces, this is called decraling a function. 

* Calling a function: 

Having declared the function, you can execute all the statements inside it using only one line of code, this is called calling a function. 

* Declaring a function that need information: 

sometimes a function needs specific information to perform its task, in such cases you need to add the parameters when you declare the function, inside the function the parameters act like variables. 

* Calling a function that need information:

When you call the function that has parameters, you specify the value it should use in the parantheses that follows it's name, the values are called arguments. 

* Getting a single value out of a function: 

some functions return information to the code that called them, for example when they perform a calculation. 

* Getting multiple value out of a function: 

Functions can return more than one value using an array. 

#### ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS: 

Expressions produce a value. They can be used where values are expected. If a function is placed where a browser expects to see an expression, then it gets treated as an expression, and it is known as a function expression. In function expressions, the name is usually omitted. a function with no name is called an anonymous function. 

In a function expression, the function is not processed until the interpreter gets to that statement. This means you cannot call this function before the interpreter has discovered it. It also means that any code that appears up to that point could potentially alter what goes on inside this function. 

#### VARIABLE SCOPE: 

The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope. 

* LOCAL VARIABLES: When a variable is created inside a function using the var keyword, it can only be used in that function. It is called a local variable or function-level variable. It cannot be accessed outside of the function in which it was declared.

* GLOBAL VARIABLES: If you create a variable outside of a function, then it can be used anywhere within the script. It is called a global variable and has global scope.

#### HOW MEMORY & VARIABLES WORK: 

Global variables use more memory. The browser has to remember them for as long as the web page using them is loaded. Local variables are only remembered during the period of time that a function is being executed. 



