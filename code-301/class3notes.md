# Passing Functions as Props

## React Docs - lists and keys

### What does .map() return?

The .map() method creates a new array populated with the results of calling a provided function on every element in the calling array. In the context of React, it's commonly used to create an array of JSX elements.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

In React, you would use the .map() method on the array, returning a JSX element for each item in the array.

### Each list item needs a unique ____.

Each list item needs a unique key.

### What is the purpose of a key?

Keys help React identify which items have changed, were added, or were removed. Keys should be given to the elements within the array to give the elements a stable identity.

## The Spread Operator

### What is the spread operator?

The spread operator (...) is used to expand iterable elements into individual elements. It's a convenient syntax to work with arrays and objects.

### List 4 things that the spread operator can do.

- Copying arrays.
- Concatenating or combining arrays.
- Using Math functions.
- Copying objects and adding new properties to objects.


### Give an example of using the spread operator to combine two arrays.

> const arr1 = [1, 2, 3];
> const arr2 = [4, 5, 6];
> const combinedArr = [...arr1, ...arr2];  // [1, 2, 3, 4, 5, 6]

### Give an example of using the spread operator to add a new item to an array.

> const arr = [1, 2, 3];
> const newArr = [...arr, 4];  // [1, 2, 3, 4]

### Give an example of using the spread operator to combine two objects into one.

> const obj1 = { a: 1, b: 2 };
> const obj2 = { c: 3, d: 4 };
> const combinedObj = { ...obj1, ...obj2 };  // { a: 1, b: 2, c: 3, d: 4 }

## How to Pass Functions Between Components

### In the video, what is the first step that the developer does to pass functions between components?

He created a function on the parent component where the state is going to change

### In your own words, what does the increment function do?

When you  click the button that is inside person function, It calls the increment function that will update the state, then it passes the name that was given back up to the increment method that is going change state thats going to re render the new value of count.

### How can you pass a method from a parent component into a child component?

In React, you can pass methods from a parent component to a child component via props.

### How does the child component invoke a method that was passed to it from a parent component?

The child component can invoke a method passed to it from a parent component by accessing it through the props object and then calling it in a function.