# Class01

[Return to home page](https://momansi96.github.io/reading-notes/). 


## Structure:

#### How Pages Uses Structure: 

Think about the stories you read in a newspaper: for each
story, there will be a headline, some text, and possibly some images. If the article is a long piece, there may be subheadings that split the story into separate sections or quotes from those involved. 
Structure helps readers understand the stories in the
newspaper.
The structure is very similar then a news story is viewed
online (although it may also feature audio or video).

#### HTM L Describes the Structure of Pages: 

To describe the structure of a web page, we add code to the words we want to appear on the page.
The HTML code is made up of characters that live inside angled brackets — these are called HTML elements. 
Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and closing tags.
Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

- HTML structure: 

1- <body>: 

Everything inside this element is shown inside the main browser window.

2- <head>
Before the <body> element you will often see a <head> element.
This contains information about the page (rather than
information that is shown within the main part of the browser window.
You will usually find a <title> element inside the <head>
element. 

3- <title>
The contents of the <title> element are either shown in the
top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).

## Extra Markup: 

#### The several tags in HTML: 

1- DOCCTYPEs: Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using 

2- Comments in HTML: If you want to add a comment to your code that will not be visible in the user's browser, you
can add the text between these characters.
<!-- comment goes here -->. 

3- ID Attribute: Every HTML element can carry the id attribute. It is used to uniquely identify that element
from other elements on the page. Its value should start with
a letter or an underscore. 

4- Block Elements: Some elements will always appear to start on a new line in the browser window. These are known as block-level elements.
Examples of block elements are <h1>, <p>, <ul>, and <li>.

5- Inline Elements: Some elements will always appear to continue on the same line as their neighboring elements. These are known as inline elements.
Examples of inline elements are <**>, <****>. 

## HTML5 Layout: 

1- Headers & Footers: The <header> and <footer> elements can be used for:
 - The main header or footer appears at the top or bottom of every page on the site.
 - A header or footer for an individual <article> or <section> within the page.

2- Navigation: The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation.

3- Articles: The <article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.

4- Sections: The <section> element groups related content together, and typically each section would have its own heading.

## Process & Design: 

#### Who is the Site For?

Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is, It can be helpful to ask some questions about the people you would expect to be interested in the subject of your site.

#### Why People Visit Your Website? 

Now that you know who your visitors are, you need to consider why they are coming. While some people will simply chance across your website, most will visit for a specific reason, Your content and design should be influenced by the goals of your users.

#### What Your Visitors are Trying to Achieve? 

It is unlikely that you will be able to list every reason why someone visits your site but you are looking for key tasks and motivations. This information can help guide your site designs.

#### What Information Your Visitors Need? 

You know who is coming to your site and why they are coming,so now you need to work out what information they need in order to achieve their goals quickly and effectively, You may want to offer additional supporting information that you
think they might find helpful. 

#### How Often People Will Visit Your Site? 

Some sites benefit from being updated more frequently than others. Some information (such as news) may be constantly changing, while other content remains relatively static. 

#### Site Maps: 

Now that you know what needs to appear on your site, you can start to organize the information into sections or page , The aim is to create a diagram of the pages that will be used to structure the site. This is known as a site map and it will show how those pages can be grouped.

#### WireFrames: 

A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require, A lot of designers will take the elements that need to appear on each page and start by creating wireframes. This involves
sketching or shading areas where each element of the page
will go (such as the logo, primary navigation, headings and main bodies of text, user logins, etc).

#### Designing Navigation: 

Site navigation not only helps people find where they want to go, but also helps them understand what your site is about and how it is organized.
Good navigation tends to follow these principles: 
 - Concise. 
 - Clear. 
 - Selective. 
 - Context. 
 - Interactive. 
 - Consistent. 

## The ABC of programming: 

#### What is a script and how do I create one? 

A script is a series of instructions that a computer can follow to achieve a goal. 

- WRITING A SCRIPT: 
 1- To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it. 

 2- Start with the big picture of what you want to achieve, and break that down into smaller steps.


#### Designing a script: 

1- Tasks: 
Once you know the the goal of your script, you can work out the individual tasks needed to achieve it. 

2- Each individual task may be broken down into a sequence of steps, when you are ready to code the script, these steps can be translated into lines of code. 

## How do computers fit in the world around them? 

#### COMPUTERS CREATE MODELS OF THE WORLD USING DATA:  

A computer has no predefined concept of what a hotel or car is. It does not know what they are used for. So how do we use computers to create hotel booking apps, or video games where players can race a car? The answer is that programmers create a very different kind of model,  especially for computers. Programmers make these models using data. That is not as strange or as scary as it sounds because the data is all the computer needs in order to follow the instructions you give it to carry out its tasks. 


#### OBJECTS & PROPERTIES:  

- OBJECTS (THINGS): 

In computer programming, each physical thing in the world can be represented as an object. 

Each object can have its own:

• Properties
• Events
• Methods

Together they create a working model of that object.

- PROPERTIES (CHARACTERISTICS): 

Both of the cars share common characteristics. In fact, all cars have a make, a color, and engine size. You could even determine their current speed. Programmers call these characteristics the properties of an object.

Each property has a name and a value, and each of these name/value pairs tells you something about each individual instance of the object. The most obvious property of this hotel is its name. The value for that property is Quay. You can tell the number of rooms the hotel has by looking at the
value next to the rooms property. 

#### EVENTS: 

There are common ways in which people interact with each type of object. programs are designed to do different things when users interact with the computer in different ways. For example, clicking on a contact link on a web page could bring up a contact form, and entering text into a search box may automatically trigger the search functionality. An event is the computer's way of sticking up its hand to say, "Hey, this just happened!. 

Programmers choose which events they respond to. When a specific event happens, that event can be used to trigger a specific section of the code. So a script will state which events the programmer wants to respond to, and what part of the script should be run when each of those events occur. 

#### METHODS: 

Methods typically represent how people (or other things) interact with an object in the real world. They are like questions and instructions that:

• Tell you something about that object (using information stored in its properties). 

• Change the value of one or more of that object's properties. 

The code for a method can contain lots of instructions that together represent one task. When you use a method, you do not always need to know how it achieves its task; you just need to know how to ask the question and how to interpret any answers it gives you. 

#### THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE: 

Using the document object, you can access and change what content users see on the page and respond to how they interact with it. 

Like other objects that represent real-world things, the document object has:

- PROPERTIES: Properties describe characteristics of the current web page (such as the title of the page).
- METHODS: Methods perform tasks associated with the
document currently loaded in the browser (such as getting information from a specified element or adding new content).
- EVENTS: You can respond to events, such as a user clicking or tapping on an element. 

#### HOW A BROWSER SEES A WEB PAGE? 

1- RECEIVE A PAGE AS HTML CODE: 
Each page on a website can be seen as a separate document. So, the web consists of many sites, each made up of one or
more documents.

2- CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY: 
The model shown on the right hand page is a representation
of one very basic page. Its structure is reminiscent of a
family tree. At the top of the model is a document object,
which represents the whole document. Beneath the document object each box is called a node. Each of these nodes is another object.

3- USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN: 
If there is no CSS, the rendering engine will apply default styles to HTML elements. When the browser receives CSS rules, the rendering engine processes them and applies each rule to its corresponding elements. This is how the browser positions the elements in the correct place, with the right colors, fonts, and so on. 


## How to write a script for a web page? 

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

javascript:  
BEHAVIOR LAYER. (js files):
This is where we can change how the page behaves, adding
interactivity. We will aim to keep as much of our JavaScript as possible in separate files.


#### CREATING A BASIC JAVASCRIPT: 


JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script.

1- Create a folder then start up your code editor, A JavaScript file is just a text file (like HTML and CSS
files are) but it has a .js file extension, so save this file with the name add-content .js. 

2- In your code editor, enter the HTML. Save this file with the name add-content.html The HTML <script> element is used to load the JavaScript file into the page. It has an attribute called src, whose value is the path to the script you created. This tells the browser to find and load the script file (just like the src attribute on an <img> tag).

3- Open the HTML file in your browser. You should see that JavaScript has been added. 

4- view the source code for the page. The source of the web page does not actually show the new element that has been added to the page; it just shows the link to the JavaScript file.

- JAVASCRIPT RUNS WHERE IT IS FOUND IN THE HTML When the browser comes across a <script> element, it stops to load the script and then checks to see if it needs to do anything.

