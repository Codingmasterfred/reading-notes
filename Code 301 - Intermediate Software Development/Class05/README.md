## React Docs - Thinking in React

### What is the single responsibility principle and how does it apply to components?
The single responsibility principle means that a component should only have one reason to change, making it easier to understand and maintain.
### What does it mean to build a ‘static’ version of your application?
Building a 'static' version of an application means creating a version with hard-coded data and no interactivity.
### Once you have a static application, what do you need to add?
After building a static application, you need to add interactivity by adding state and event handling.


### What are the three questions you can ask to determine if something is state?
To determine if something is state, you can ask: 1 Is it passed in from a parent via props? 2 Does it remain unchanged over time? 3 Can it be computed from other state or props?
### How can you identify where state needs to live?
You can identify where state needs to live by finding the components that need the state and finding a common owner component that can hold the state and pass it down to the components that need it.

## Higher-Order Functions

### What is a “higher-order function”?
A "higher-order function" is a function that takes one or more functions as arguments and/or returns a function as its result. 
### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
 The greaterThan function returns a function that captures a number and returns a Boolean indicating whether the passed number is greater than that captured number; Line 2 is returning an arrow function.
### Explain how either map or reduce operates, with regards to higher-order functions.
 Map and reduce are higher-order functions that take a function as an argument and apply it to each element of an array, with map returning a new array with the results and reduce accumulating the results into a single value.


## Things I want to know more about?