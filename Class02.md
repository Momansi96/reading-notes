# Class02

[Return to home page](https://momansi96.github.io/reading-notes/). 


## Text

#### Headings: 

HTML has six "levels" of headings:

<h1> is used for main headings. 

<h2> is used for subheadings. 

If there are further sections under the subheadings then the <h3> element is used, and so on.

#### Paragraphs: 

To create a paragraph, surround the words that make up the paragraph with an opening <p> tag and closing </p> tag. By default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

#### Bold & Italic: 

1- <b>:  By enclosing words in the tags <b> and </b> we can make characters appear bold. The <b> element also represents a section of text that would be presented in a visually different way (for example key words in a
paragraph). 

2- <i>:  By enclosing words in the tags <i> and </i> we can make characters appear italic. The <i> element also represents a section of text that would be said in a different way from surrounding content. 

#### Superscript & Subscrip: 

1- <sup>:  The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22. 

2- <sub>: The <sub> element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.

#### White Space: 

In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines. When the browser comes across two or more spaces next to each other, it only displays one space.

#### Line Breaks & Horizontal Rules: 

1- <br />: As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag <br />. 

2- <hr />: To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the <hr /> tag.

#### Visual Editors & Their Code views: 

1- Visual editors often resemble word processors. Although each editor will differ slightly, there are some features that are common to most editors that allow you to control the presentation of text. 

2- Code views show you the code created by the visual editor so you can manually edit it, or so you can just enter new code yourself. 

### Semantic Markup: 

There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup such as: 

1- <strong>: The use of the <strong> element indicates that its content has strong importance, By default, browsers will show the contents of a <strong> element in bold. 

2- <em>: The <em> element indicates emphasis that subtly changes the meaning of a sentence. By default browsers will show the contents of an <em> element in italic. 

3- <blockquote>: The <blockquote> element is used for longer quotes that take up an entire paragraph.however you should not use this element just to indent a piece of text — rather you should achieve this effect using CSS.

4- <q>: The <q> element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put quotes around the <q> element. 

5- <abbr>: If you use an abbreviation or an acronym, then the <abbr> element can be used. A title attribute on the opening tag is used to specify the full term.

6- <cite>: When you are referencing a piece of work such as a book, film or research paper, the <cite> element can be used to indicate where the citation is from.

7- <dfn>: The first time you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is known as the defining instance of it. The <dfn> element is used to indicate the defining instance of a new term. 

8- <address>: The <address> element has quite a specific use: to contain contact details for the author of the page. It can contain a physical address, but it does not have to. For example, it may also contain a phone number or email address.

9- <ins>, <del>: The <ins> element can be used to show content that has been inserted into a document, while
the <del> element can show text that has been deleted from it.

10- <s>: The <s> element indicates something that is no longer accurate or relevant (but that should not be deleted). Visually the content of an <s> element will usually be displayed with a line through the center. 



## Introducing CSS: 

#### Understanding CSS: Thinking Inside the Box. 

The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element. CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration. 

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

#### Using External CSS: 

<link>: The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes:

1- href: This specifies the path to the CSS file (which is often placed in a folder called css or styles).

2- type: This attribute specifies the type of document being linked to. The value should be text/css.

3- rel: This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

#### Using Internal CSS: 

- <style>: You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page. The <style> element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/css. 

When building a site with more than one page, you should use an external CSS style sheet. This:

 - Allows all pages to use the same style rules (rather than repeating them in each page).
 - Keeps the content separate from how the page looks.
 - Means you can change the styles used across all pages by altering just one file (rather than each individual page).

#### CSS Selectors: 

There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document, such as: 

1- Universal Selector (*): Applies to all elements in the document. 

2- Type Selector: Matches element names. 

3- Class Selector (.): Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol. 

4- ID Selector (#): Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol. 

5- Child Selector: Matches an element that is a direct child of another. 

6- Descendant Selector: Matches an element that is a descendent of another specified element (not just a direct child of that element). 

7- Adjacent Sibling Selector: Matches an element that is the next sibling of another. 

8- General Sibling Selector: Matches an element that is a sibling of another, although it does not have to be the directly preceding element. 

#### How Css Rules Cascade? 

If there are two or more rules that apply to the same element, which will take precedence: 

1- LAST RULE: If the two selectors are identical, the latter of the two will takeprecedence. 

2- SPECIFICITY: If one selector is more specific than the others, the more specific rule will take precedence
over more general ones. 

3- IMPORTANT: You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.


## Basic javascript instructions. 

#### STATEMENTS: 

A script is a series of instructions that a computer can follow one by one, Each individual instruction or step is known as a statement, Statements should end with a semicolon.

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

- Once you created the variable you can tell it what kind of information you want to store in it. 
(name = 'Mohammed'; )

#### DATA TYPES: 

JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.

1- NUMERIC DATA TYPE: The numeric data type handles
numbers. 

2- STRING DATA TYPE: The strings data type consists of
letters and other characters.

3- BOOLEAN DATA TYPE: Boolean data types can have one
of two values: true or false. 

#### RULES FOR NAMING VARIABLES: 

- Here are six rules you must always follow when giving a variable a name: 

1- The name must begin with a letter, dollar sign ($), or an
underscore (_). It must not start with a number.

2- The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name. 

3- You cannot use keywords or reserved words. 

4- All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases.

5- Use a name that describes the kind of information that the variable stores. 

6- If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word.

#### ARRAYS: 

An array is a special type of variable. It doesn't just store one value; it stores a list of values. You should consider using an array whenever you are working with a list or a set of values that are related to each other. Arrays are especially helpful when you do not know how many items a list will contain because, when you create the array, you do not need to specify how many values it will hold. 

You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array). The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.

Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one). Each item in an array is automatically given a number called an index. This can be used to access specific items in the array. 

#### EXPRESSIONS: 

An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions: 

1- EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE. 

2- EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE. 

#### OPERATORS : 

Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 

- There are several types of operators such as: 

1- ASSIGNMENT OPERATORS: Assign a value to a variable.

2-ARITHMETIC OPERATORS: Perform basic math.

 - ORDER OF EXECUTION:  Several arithmetic operations can be performed in one expression, but it is important to understand how the result will be calculated. Multiplication and division are performed before addition or subtraction.

3-STRING OPERATORS: Combine two strings. 

There is just one string operator: the+ symbol, It is used to join the strings on either side of it. 


## DECISIONS & LOOPS. 

#### Comparison operators: 

You can evaluate a situation by comparing one value in the script to what you expect it to be, and the result will always be boolean. 

- You can use several tools to compare values such as: 

1- (==) "is equal to", the operator compares if two values if they are the same.

2- (!=) "is not equal to", the operator compares the two values if they are not the same. 

3- (===) "is strict equal to", the operator compares the two values if the values and the datatype are the same. 

4- (!==) "is strict not equal to", the operator compares the two values if the values and the datatype are not the same. 

5- (<) "is less than", the operator compares if the number on the left is less than the one on the right. 

6- (>) "is greater than", the operator compares if the number on the left is greater than the one on the right. 

7- (<=) "is less than or equal", the operator compares if the number on the left is less thaan or equal the one on the right.

8- (>=) "is greater than or equal", the operator compares if the number on the left is greater than or equal the one on the right. 

#### Llogical operators: 

Comparison operators usually return single values, logical operators allowes you to compare the results of the comparison operators.  

- You can use several logical operators to compare such as:

1- (&&) "logical And", this operator tastes more than one condition, and to have "True" as your result all conditions must be true.

2- (||) "logical Or", this operator tastes more than one condition, and to have "True" as your result atleast one conditions must be true. 

3- (!) "logical not", this operator takes the boolean and inverts it. 

## Loops

Loops check a condition, it returns true a code block will run, then the condition will be checked again and if it still return true the code block will run again, it repeates until the condition returns false.  

- There are several types of loops such as: 

1- IF statement: this statement checks a condition if the condition is true, any statements in the code block below it will be executed.  

2- IF Else statement: this statement checks a condition if the condition is true the first code block will be executed, if the condition is false the second code block will run instead. 

3- SWITCH statement: A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. 

















