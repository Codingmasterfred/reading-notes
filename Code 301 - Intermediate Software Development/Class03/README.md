## React Docs - lists and keys

### What does .map() return?
The .map() method returns a new array with the results of calling a function for every array element.
### If I want to loop through an array and display each value in JSX, how do I do that in React?
To loop through an array and display each value in JSX, we can use the .map() method and return a JSX element for each element in the array.
### Each list item needs a unique ____.
Each list item needs a unique 'key' to help React identify which items have changed, been added, or been removed.
### What is the purpose of a key?
The purpose of a key is to help React identify which items have changed, been added, or been removed from a list.
## The Spread Operator

### What is the spread operator?
The spread operator is a syntax for expanding iterable objects into individual elements.
### List 4 things that the spread operator can do.
Four things that the spread operator can do are: concatenate arrays, copy arrays, add new items to an array, and merge objects.
### Give an example of using the spread operator to combine two  arrays.
An example of using the spread operator to combine two arrays would be: const combinedArray = [...array1, ...array2];
### Give an example of using the spread operator to add a new item to an array.
An example of using the spread operator to add a new item to an array would be: const newArray = [...oldArray, newItem];
### Give an example of using the spread operator to combine two  objects into one.
An example of using the spread operator to combine two objects into one would be: const combinedObject = {...object1, ...object2};

## How to Pass Functions Between Components

### In the video, what is the first step that the developer does to pass functions between components?
The first step to pass functions between components is to define the function in the parent component.
### In your own words, what does the increment function do?
The increment function increases a counter variable by one and sets the updated value in the component's state.
### How can you pass a method from a parent component into a child component?
We can pass a method from a parent component into a child component by passing it as a prop.
### How does the child component invoke a method that was passed to it from a parent component?
The child component can invoke a method that was passed to it from a parent component by calling it as a function, and passing any necessary arguments.

## Things I want to know more about?