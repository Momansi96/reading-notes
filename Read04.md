# Read04

[Return to home page](https://momansi96.github.io/reading-notes/). 


## How to wright a script for a web page? 

#### HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER: 

Web developers usually talk about three languages that
are used to create web pages: HTML, CSS, and JavaScript.

Where possible, aim to keep the three languages in separate files, with the HTML page linking to CSS and JavaScript files.

Each language forms a separate layer with a different purpose, Each layer, from left to right. builds on the previous one.

html:
CONTENT LAYER. (html files): 
This is where the content of the page lives. The HTML gives the page structure and adds semantics.

css:
PRESENTATION LAYER. (css files): 
The CSS enhances the HTML page with rules that state how
the HTML content is presented (backgrounds, borders, box
dimensions, colors, fonts, etc.).

(javascri) pt
BEHAVIOR LAYER. (js files):
This is where we can change how the page behaves, adding
interact ivity. We will aim to keep as much of our JavaScript as possible in separate files.


#### CREATING A BASIC JAVASCRIPT: 


JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script.

1- Create a folder then start up your code editor, A JavaScript file is just a text file (like HTML and CSS
files are) but it has a .js file extension, so save this file with the name add-content .js. 

2- In your code editor, enter the HTML. Save this file with the name add-content.html The HTML <script> element is used to load the JavaScript file into the page. It has an attribute called src, whose value is the path to the script you created. This tells the browser to find and load the script file (just like the src attribute on an <img> tag).

3- Open the HTML file in your browser. You should see that the JavaScript has been added. 

4- view the source code for the page. The source of the web page does not actually show the new element that has been added into the page; it just shows the link to the JavaScript file.

- JAVASCRIPT RUNS WHERE IT IS FOUND IN THE HTML When the browser comes across a <script> element, it stops to load the script and then checks to see if it needs to do anything.


## BASIC JAVASCRIPT INSTRUCTIONS: 


#### STATEMENTS: 

A script is a series of instructions that a computer can follow one-by-one, Each individual instruction or step is known as a statement, Statements should end with a semicolon.

STATEMENTS ARE INSTRUCTIONS AND EACH ONE STARTS ON A NEW LINE The semicolon also tells the JavaScript interpreter
when a step is over, indicating that it should move to the next step. 


#### COMMENTS: 


You should write comments to explain what your code does.
They help make your code easier to read and understand. This can help you and others who read your code.

MULTI-LINE COMMENTS: To write a comment that stretches over more than one line, you use a multi-line comment, starting with the (* characters and ending with the * /) characters.
Anything between these characters is not processed· by the JavaScript interpreter.


#### WHAT IS A VARIABLE? 


A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

A variable is a good name for this concept because the data stored in a variable can change (or vary) each time a script runs.

- Before you use a variable you need to announce that you want to use them, this involves creating a variable and giving it a name. 
(var name;)

- Once you created the variable you can tell it what kind of information you want to stor in it. 
(name = 'Mohammed'; )


#### DATA TYPES: 


JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.

1- NUMERIC DATA TYPE:The numeric data type handles
numbers. 
2- STRING DATA TYPE: The strings data type consists of
letters and other characters.
3- BOOLEAN DATA TYPE: Boolean data types can have one
of two va lues: true or false. 


#### RULES FOR NAMING VARIABLES: 


- Here are six rules you must always follow when giving a variable a name: 

1- The name must begin with a letter, dollar sign ($),or an
underscore (_). It must not start with a number.

2- The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name. 

3- You cannot use keywords or reserved words. 

4- All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases.

5- Use a name that describes the kind of information that the variable stores. 

6- If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word.


 
