# JavaScript Object Basics

## How would you describe an object to a non-technical friend you grew up with?

An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects).

## What are some advantages to creating object literals?

Creating object literals in JavaScript has several advantages:

> Simplicity: Object literals provide a simple and straightforward way to define objects in JavaScript. You can easily specify the properties and their values using curly braces {}.
>Flexibility: Object literals allow you to easily add, remove, or modify properties as needed. You can change an object's properties dynamically based on your requirements.
>Readability: Object literals have a clear and easy-to-understand syntax. Properties and their values are defined in a key-value format, making it easy to read and maintain.
>Scoping: Object literals create a specific scope for the object, isolating its properties from the rest of the code. This helps prevent conflicts with other variables or properties.
>Object composition: Object literals can be used to combine different objects, arrays, or functions as properties. This allows you to create more complex and organized data structures.

## How do objects differ from arrays?

> Structure: Arrays are ordered collections of values, accessed using numerical indices (starting from 0). Objects, on the other hand, are collections of key-value pairs, where the keys are strings (or symbols) used to access the corresponding values.
> Accessing Data: In arrays, you access elements by their numeric index, such as array[0]. In objects, you access values using their associated keys, like object['key'] or object.key. Objects allow for more descriptive and meaningful keys, while arrays are accessed by their position.
> Order: Arrays maintain the order of their elements, so the position of an element in the array matters. Objects do not have a defined order for their properties, so the sequence in which properties are defined or accessed may not be consistent.
> Data Storage: Arrays are best suited for storing lists of similar items, such as a list of numbers or strings. Objects, on the other hand, are suitable for storing more complex and structured data, where each value has a specific key and purpose.
> Functionality: Arrays come with built-in methods and properties specifically designed for working with ordered collections, such as length, push(), pop(), and more. Objects, while not offering specific array-like methods, can be extended with custom methods and functions to perform specific operations.

In summary, arrays are best for storing ordered lists of similar items, while objects are suitable for organizing and accessing data with more descriptive key-value pairs. Arrays are indexed numerically, while objects are accessed by keys.

## Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation

If object's property contains a space, we cannot access it using dot notation. Instead, we use bracket notation and provide the key as a string within the square brackets. By using bracket notation, we can access the values associated with the properties even if they have special characters or spaces in their keys.

## Evaluate the code below. What does the term this refer to and what is the advantage to using this?

*Javascript Copy code:*

> const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function() {
    console.log(`${this.name} is ${this.age * 7} in human years`);
  }
}

The code provided defines an object named dog with properties such as name, age, color, and a method humanAge. The this keyword refers to the current object, which is dog in this case.

Using this allows us to access the properties of the object within its own context. In the given code, this.name refers to the value of the name property of the dog object, and this.age refers to the value of the age property.

# Introduction To The DOM

## *What is the DOM?*

## Briefly describe the relationship between the DOM and JavaScript.

The DOM is like a tree that represents a web page, and JavaScript is like a tool that allows you to change and interact with that tree.

The DOM is the structure of the web page, and it has elements like headings, paragraphs, buttons, and more. JavaScript is a language that lets you write code to make changes to those elements. You can change their text, style, add or remove them, and make them do things when you click or interact with them.

So, JavaScript and the DOM work together. JavaScript gives you the power to make the web page dynamic and responsive by modifying and controlling the elements in the DOM.
