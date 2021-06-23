# Class5

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Thinking in React


* How would you break a mock into a component heirarchy?

Using the single responsibility principle. 


* What is the single responsibility principle and how does it apply to components?

that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.


* What does it mean to build a ‘static’ version of your application?

It means to build a version that takes your data model and renders the UI but has no interactivity.


* Once you have a static application, what do you need to add?

Identify The Minimal Representation Of UI State. 


* What are the three questions you can ask to determine if something is state?

1. Is it passed in from a parent via props? If so, it probably isn’t state.
2. Does it remain unchanged over time? If so, it probably isn’t state.
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.


* How can you identify where state needs to live?

1. Identify every component that renders something based on that state.
2. Find a common owner component (a single component above all the components that need the state in the hierarchy).
3. Either the common owner or another component higher up in the hierarchy should own the state.
4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

