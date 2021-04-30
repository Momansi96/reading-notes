# Class06

[Return to home page](https://momansi96.github.io/reading-notes/). 

## WHAT IS AN OBJECT? 

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 

If a variable is part of an object, it is called a property. Properties tell us about the object, If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object. 

#### Creating an object (Literal notation): 

* Literal notation is the easiest way to create objects. 

* Accessing an object and dot notation: you can access the properties of an object using dot notation, you can also access properties using square brackets. 


## Document Object Model: 


#### THE DOM TREE IS A MODEL OF A WEB PAGE: 

* As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes: 

 1. THE DOCUMENT NODE: When you access any element, attribute, or text node, you navigate to it via the document node. It is the starting point for all visits to the DOM tree. 
 2. ELEMENT NODES: To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to.
 3. ATTRIBUTE NODES: The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree. 
 4. TEXT NODES: Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node.

* WORKING WITH THE DOM TREE: Accessing and updating the DOM tree involves two steps:

 1. Locate the node that represents the element you want to work with.
 2. Use its text content, child elements, and attributes. 

* Caching a dom queries: 

Methods that find elements in the DOM tree are called DOM queries, when you need to work with an element more than once, you should use a variable to store the result of the querey. 

* ACCESSING ELEMENTS: DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. Sometimes you will just want to access one individual element, Other times you may want to select a group of elements,

 - GROUPS OF ELEMENT NODES: If a method can return more than one node, it will always return a Nodelist, which is a collection of nodes. You then need to select the element you want from this list using an index number. 
 - FASTEST ROUTE: Finding the quickest way to access an element within your web page will make the page seem faster and or more responsive. This usually means evaluating the minimum number of nodes on the way to the element you want to work with.

* SELECTING ELEMENTS USING ID ATTRIBUTES: 

This method has one parameter: the value of the id attribute on the element you want to select. This value is placed inside quote marks because it is a string. The quotes can be single or double quotes, but they must match. 

* NODELISTS: DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT: 

When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element). A Nodelist is a collection of element nodes. Each node is given an index number (a number that starts at zero, just like an array). The order in which the element nodes are stored in a Node List is the same order that they appeared in the HTML page.

* LIVE & STATIC NODELISTS: There are times when you will want to work with the same selection of elements several times, so the Nodelist can be stored in a variable and re-used

 1. live Nodelist: when your script updates the page, the Nodelist is updated at the same time. They are also typically faster to generate than static Nodelists. 
 2. static Nodelist: when your script updates the page, the NodeList is not updated to reflect the changes made by the script.

* SELECTING AN ELEMENT FROM A NODELIST: There are two ways to select an element from a Nodelist:
 1. The item() method: Nodelists have a method called item() which will return an individual node from the Node list. You specify the index number of the element you want as a parameter of the method (inside the parentheses).  
 2. array syntax: you can access individual nodes using a square bracket syntax similar to that used to access individual items from an array, You specify the index number of the element you want inside square bracket that follows the nodelist. 
 
Both require the index number of the element you want. 

* SELECTING ELEMENTS USING CLASS ATTRIBUTES: 

The get El ementsByCl ass Name() method allows you to select elements whose class attribute contains a specific value. The method has one parameter: the class name which is given in quotes within the parentheses after the method name. 

* SELECTING ELEMENTS BY TAG NAME: 

The get ElementsByTagName () method allows you to select elements using their tag name. The element name is specified as a parameter, so it is placed inside the parentheses and is contained by quote marks. 

* SELECTING ELEMENTS USING CSS SELECTORS: 

querySe 1 ector() returns the first element node that matches the CSS-style selector. querySe 1ectorA11 () returns a Nodelist of all of the matches. Both methods take a CSS selector as their only parameter. The CSS selector syntax offers more flexibility and accuracy when selecting an element than just specifying a class name or a tag name, and should also be familiar to front-end web developers who are used to targeting elements using CSS.

* LOOPING THROUGH A NODELIST: If you want to apply the same code to numerous elements, looping through a Nodelist is a powerful technique. It involves finding out how many items are in the Nodelist, and then setting a counter to loop through them, one-by-one. Each time the loop runs, the script checks that the counter is less than the total number of items in the Nodelist. 

* TRAVERSING THE DOM: When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM: 

 1. parentNode: This property finds the element node for the containing (or parent) element in the HTML. 
 2. previousSibling and nextSibling: These properties find the previous or next sibling of a node if there are siblings. 
 3. firstChild and lastChild: These properties find the first or last child of the current element. 
 
* ACCESS & UPDATE A TEXT NODE WITH NODEVALUE: When you select a text node, you can retrieve or amend the content of it using the node Value property, In order to use node Value, you must be on a text node, not the element that contains the text. 

* ACCESSING & CHANGING A TEXT NODE: To work with text in an element, first the element node is accessed and then its text node. The text node has a property called node Value which returns the text in that text node. You can also use the node Value property to update the content of a text node. 

* ACCESSING TEXT ONLY: In order to demonstrate the difference between textContent and i nnerText, this example features a CSS rule to hide the contents of the "<em>" element. The script starts off by getting the content of the first list item using both the textContent property and innerText. It then writes the values after the list. Finally, the value of the first list item is then updated to say sourdough bread. This is done using the textContent property. 

* ADDING ELEMENTS USING DOM MANIPULATION: 

DOM manipulation offers another technique to add new content to a page (rather than innerHTML). It involves three steps:

 1. CREATE THE ELEMENT: You start by creating a new element node using the createElement() method. This element node is stored in a variable. 
 2. GIVE IT CONTENT: createTextNode() creates a new text node. Again, the node is stored in a variable. It can be added to the element node using the appendChi l d () method. appendChi 1 d () method.
 3. ADD IT TO THE DOM: Now that you have your element (optionally with some contentin a text node), you can add it to the DOM tree using the appendChi 1 d () method.

* ADDING AN ELEMENT TO THE DOM TREE: 

createEl ement () creates an element that can be added to the DOM tree, in this case an empty "<li>" element for the list This new element is stored inside a variable called newEl until it is attached to the DOM tree later on. 

* REMOVING ELEMENTS VIA DOM MANIPULATION: DOM manipulation can be used to remove elements from the DOM tree.

#### XSS: 

* VALIDATION & TEMPLATES: 

Make sure that your users can only input characters they need to use and limit where this content will be shown on the page. 

 * FILTER OR VALIDATE INPUT: The most basic defense is to prevent users from entering characters into form fields that they do not need to use when providing that kind of information. 
 * LIMIT WHERE USER CONTENT GOES: Malicious users will not just use "script" tags to try and create an XSS attack. malicious code can live in an event attribute without being wrapped in "script" tags. XSS can also be triggered by malicious code in CSS or URLs. 

* ESCAPING & CONTROLLING MARKUP: 

Any content generated by users that contain characters that are used in code should be escaped on the server. You must control any markup added to the page. 

#### CREATING ATTRIBUTES & CHANGING THEIR VALUES: 

The className property allows you to change the value of the class attribute. If the attribute does not exist, it will be created and given the specified value. You have seen this property used throughout the chapter to update the status of the list items. Below, you can see another way to achieve the task. The setAttri bute() method allows you to update the value of any attribute. It takes two parameters: the attribute name, and the value for the attribute.

* REMOVING ATTRIBUTES: To remove an attribute from an element, first select the element, then call removeAtt r i bute (). It has one parameter: the name of the attribute to remove. Trying to remove an attribute that does not exist will not cause an error, but it is good practice to check for its existence before attempting to remove it. 

#### EXAMINING THE DOM IN CHROME: 

In the screenshot to the right, the "<li>" element is highlighted and the Properties panel (1) indicates that this is an:
 * 1i element with an id attribute whose value is one and class whose value is hot. 
 * an HTMLLIElement. 
 * an HTMLElement. 
 * an element. 
 * a node. 
 * an object. 

Each of these object names has an arrow next to it which you can use to expand that section. It will tell you what properties are available to that kind of node. 



 
