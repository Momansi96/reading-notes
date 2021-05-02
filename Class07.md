# Class07

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Domain Modeling: 

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

#### Model epic fails videos: 

Imagine you've been tasked to build a program that models the popularity of epic fail videos. After months of painstaking research, you've determined that the two essential metrics for gauging popularity are an epic rating and whether or not the video has animals.

Since you'll be modeling the popularity of many types of videos. you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.

#### Generate random numbers: 

To model the random nature of user behavior, you'll need the help of a random number generator. Fortunately, the JavaScript standard library includes a "Math.random()" function for just this sort of occasion, As you can see, methods can be added to a constructor function's prototype. Think of the prototype as an object's stunt double. Whenever a scene is too dangerous, you can substitute in the prototype to do the work. 

#### Calculate daily Likes: 

Popularity of a video is measured in Likes. And the formula for calculating Likes is the number of viewers times the percentage of viewers who'll Like a video. In other words, viewers times percentage, To calculate the number of viewers per day, generate a random number between 10 and 30 and then multiply it by the epic rating of that video.

#### Summary: 

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

 1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and  behaviors.
 2. Model its attributes with a constructor function that defines and initializes properties.
 3. Model its behaviors with small methods that focus on doing one job well.
 4. Create instances using the new keyword followed by a call to a constructor function.
 5. Store the newly created object in a variable so you can access its properties and methods from outside.
 6. Use the this variable within methods so you can access the object's properties and methods from inside.


## Tables: 

#### What's a Table?

A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results. Grids allow us to understand complex data by referencing information on two axes. Each block in the grid is referred to as a table cell. In HTML a table is written out row by row. 

#### Basic Table Structure: 

1. "<table>": The "<table>" element is used to create a table. The contents of the table are written out row by row.

2. "<tr>": You indicate the start of each row using the opening "<tr>" tag. (The tr stands for table row.) It is followed by one or more "<td>" elements (one for each cell in that row).

3. "<td>": Each cell of a table is represented using a "<td>" element. (The td stands for table data.)

* Table Headings: 

* "<th>":  The "<th>" element is used just like the "<td>" element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) Even if a cell has no content, you should still use a "<td>" or "<th>" element to represent the presence of an empty cell otherwise the table will not render correctly. 

* Spanning Columns: 

Sometimes you may need the entries in a table to stretch across more than one column. The colspan attribute can be used on a "<th>" or "<td>" element and indicates how many columns that cell should run across.

* Spanning Rows: 

You may also need entries in a table to stretch down across more than one row. The rowspan attribute can be used on a "<th>" or "<td>" element to indicate how many rows a cell should span down the table.

* Long Tables: 

There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content). These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table (as you will see when you learn about CSS).
 
 1. "<thead>": The headings of the table should sit inside the "<thead>" element.
 2. "<tbody>": The body should sit inside the "<tbody>" element.
 3. "<tfoot>": The footer belongs inside the "<tfoot>" element.


## Creating an object (Constructer Notation): 

First, you create a new object using a combination of the new keyword and the "Object()" constructer function, Next having created the blank object you can add properties and methods using dot notation. 

* Updating an object: to update the value of proprties you can use the dot notation or the square brackets, to delete the proprties use the keyword "delete". 

* CREATING MANY OBJECTS: CONSTRUCTOR NOTATION: 

Sometimes you will want several objects to represent similar things. Object constructors can use a function as a template for creating objects. First, create the template with the object's properties and methods. 

* ADDING AND REMOVING PROPERTIES: 

Once you have created an object (using literal or constructor notation), you can add new properties to it. You do this using the dot notation. To delete a property, you use the keyword delete, and then use dot notation to identify the property or method you want to remove from the object. 

* THIS: The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.

#### WHAT ARE BUILT-IN OBJECTS?

Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages. 

The first thing you need to do is get to know what tools are available. You can imagine that your new toolkit has three compartments: 

 1. BROWSER OBJECT MODEL: The Browser Object Model contains objects that represent the current browser window or tab. It contains objects that model things like browser history and the device's screen. 
 2. DOCUMENT OBJECT MODEL: The Document Object Model uses objects to create a representation of the current page. It creates a new object for each element (and each individual section of text) within the page.
 3. GLOBAL JAVASCRIPT OBJECTS: The global JavaScript objects represent things that the JavaScript language needs to create a model of. For example, there is an object that deals only with dates and times. 

#### THE BROWSER OBJECT MODEL: THE WINDOW OBJECT. 

The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser. 

* USING THE BROWSER OBJECT MODEL: Here, data about the browser is collected from the window object and its children, stored in the msg variable, and shown in the page. The+= operator adds data onto the end of the msg variable.

 1. Two of the window object's properties, innerWidth and innerHeight, show width and height of the browser window.
 2. Child objects are stored as properties of t heir parent object. So dot notation is used to access them, just like you would access any other property of that object.
 3. The element whose id attribute has a value of info is selected, and the message that has been built up to this point is written into the page.
 4. The window object's alert() method is used to create a dialog box shown on top of the page. It is known as an alert box.

#### THE DOCUMENT OBJECT MODEL: THE DOCUMENT OBJECT. 

The topmost object in the Document Object Model (or DOM) is the document object. It represents the web page loaded into the current browser window or tab. 

* USING THE DOCUMENT OBJECT: This example gets information about the page, and then adds that information to the footer.

 1. The details about the page are collected from properties of the document object.
 2. You have seen the document object's get El ementByid () method in several examples so far. It selects an element from the page using the value of its id attribute. 

#### GLOBAL OBJECTS: STRING OBJECT. 

Whenever you have a value that is a string, you can use the properties and methods of the String object on that value, These properties and methods are often used to work with text stored in variables or objects, Each character in a string is automatically given a number, called an index number. Index numbers always start at zero and not one (just like for items in an array). 

#### GLOBAL OBJECTS: NUMBER OBJECT. 

Whenever you have a value that is a number, you can use the methods and properties of the Number object on it. These methods are helpful when dealing with a range of applications from financial calculations to animations. Many calculations involving currency (such as tax rates) will need to be rounded to a specific number of decimal places. Or, in an animation, you might want to specify that certain elements. should be evenly spaced out across the page. 

#### WORKING WITH DECIMAL NUMBERS: 

As with the String object the properties and methods of the Number object can be used with with any value that is a number.

 1. In this example, a number is stored in a variable called originalNumber, and it isthen rounded up or down using two different techniques.
 2. originalNumber.toFixed(3) will round the number stored in the variable originalNumber to three decimal places. It will return the number as a string.
 3. toPrecision(3) uses the number in parentheses to indicate the total number of digits the number should have. 

#### GLOBAL OBJECTS: MATH OBJECT. 

The Math object has properties and methods for mathematical constants and functions. Because it is known as a global
object, you can just use the name of the Math object followed by the property or method you want to access. Typically you will then store the resulting number in a variable. This object also has many trigonometric functions such as sin(), cos(), and tan(). The trigonometric functions return angles in radians which can then be converted into degrees if you divide the number by (pi/ 180).

#### GLOBAL OBJECTS: DATE OBJECT (AND TIME). 

Once you have created a Date object, the following methods let you set and retrieve the time and date that it represents. 

* CREATING A DATE OBJECT: 

 1. In this example, a new Date object is created using the Date {) object constructor It is called today. 
 2. In this example, you can see that getFull Year() is used to return the year of the date being stored in the Date object.
 3. In this case, it is being used to write the current year in a copyright statement.





