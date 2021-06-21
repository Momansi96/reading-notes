# Class2

[Return to home page](https://momansi96.github.io/reading-notes/). 


## React lifecycle


* Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

"render" happens before "componentDidMount". 


* What is the very first thing to happen in the lifecycle of React?

The cycle begins with the Mounting phase which begins with the Constructor function. 


* Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates. 

1. constructor. 
2. render. 
3. componentDidMount. 
4. React Updates. 
5. componentWillUnmount. 


* What does componentDidMount do?

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. 

setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.


## State Vs Props


* What types of things can you pass in the props?

React allows us to pass values from a parent component down to a child component. The values can be any data type, from strings to functions, objects, etc.


* What is the big difference between props and state?

Props is an object of arbitrary inputs a React function component accepts as the first argument. 

State is data that changes over the lifetime of a specific instance of a React component.


* When do we re-render our application?

React components automatically re-render whenever there is a change in their state or props


* What are some examples of things that we could store in state?

We use state for storing any data which may be a string, number or any complex object.

