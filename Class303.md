# Class3

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Lists and Keys

* What does .map() return?

A new array is returned after a function is applied to the first array. 


* If I want to loop through an array and display each value in JSX, how do I do that in React?

Using .map() to iterate through an array and calls a specified function for each of the items. Components in JSX are JS functions. For each object in the array, a block of JSX elements is returned.

Also, data from the object is passed to each block using the JSX handlebars-like curly brackets.


* Each list item needs a unique __ Key __.


* What is the purpose of a key?

A key is a special string attribute you need to include when creating lists of elements, Keys help React identify which items have changed, added, or removed. 


## The Spread Operator 


* What is the spread operator?

Spread operator The syntax is three dots(...) followed by the array it allows an iterable to expand in places where 0+ arguments are expected. It is mostly used in the variable array where there is more than 1 values are expected.

* List 4 things that the spread operator can do.

1. Copying an array.
2. Concatenating or combining arrays. 
3. Adding an item to a list. 
4. Combining objects. 


* Give an example of using the spread operator to combine two arrays.

let number = [1, 4, 9];
let newNumber = [16, 25, 36];
allNumbers = [...number, ...newNumber]; 


* Give an example of using the spread operator to add a new item to an array.

let number = [1, 4, 9];
let newNumber = 16;
allNumbers = [...number, newNumber]; 


* Give an example of using the spread operator to combine two objects into one.

let obj1 = { foo: 'fighter', x: 42 };
let obj2 = { foo: 'baz', y: 13 };
let mergedObj = { ...obj1, ...obj2 };


## How to Pass Functions Between Components? 


* In the video, what is the first step that the developer does to pass functions between components?

Creating the increment function. 


* In your own words, what does the increment function do?

It loops through the array and searches for the name to increase the count. 


* How can you pass a method from a parent component into a child component?

1. Define your parent callback function in your parent component.
2. Pass the function to the child component.
3. Set up an input variable in child component.
4. Call the callback function.


* How does the child component invoke a method that was passed to it from a parent component?

In order to execute a function from a child component, you will need to use Refs. React supports a special attribute that you can attach to any component, that's the ref attribute, it takes a callback function, and you can access the functions of the child component in the parent. 

