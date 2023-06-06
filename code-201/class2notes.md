# Reading: Basics of HTML, CSS & JS

## HTML Text Fundamental. HTML Advanced Text Formatting

### *Why is it important to use semantic elements in our HTML?*

Using semantic elements in HTML is important because they make your website easier to use, more visible on search engines, and easier to update.

### *How many levels of headings are there in HTML?*

There are six heading elements: h1, h2, h3, h4, h5, and h6. Each element represents a different level of content in the document; ```<h1>``` represents the main heading, ```<h2>``` represents subheadings, ```<h3>``` represents sub-subheadings, and so on.

### *What are some uses for the ```<sup>``` and ```<sub>``` elements?*

The ```<sup>``` element is used to show something as a superscript, which means it's a small number or symbol displayed above the normal line of text. For example, you can use it to write mathematical equations like E=mc², where the "2" is smaller and raised.

The ```<sub>``` element is used to show something as a subscript, which means it's a small number or symbol displayed below the normal line of text. For example, you can use it to write chemical formulas like H₂O, where the "2" is smaller and lowered.

### *When using the ```<abbr>``` element, what attribute must be added to provide the full expansion of the term?*

When using the ```<abbr>``` element, you need to add the title attribute to explain what the abbreviation means. This way, when someone sees the abbreviation on a webpage and hovers their mouse over it, a little box will appear with the full meaning of the abbreviation.

# Learn CSS

## How CSS is Structured

### *What are ways we can apply CSS to our HTML?*

There's three methods of applying CSS to a document: with an external stylesheet, with an internal stylesheet, and with inline styles.

### *Why should we avoid using inline styles?*

We should avoid using inline styles because they can make our code harder to manage and maintain. When we use inline styles, we directly apply styling rules to individual HTML elements using the style attribute. This means that the styling is mixed with the HTML markup, making it harder to separate the structure and presentation of our webpage.

### *Review the block of code below and answer the following questions:*

 > h2 {
     color: black;
     padding: 5px;
   }

### *What is representing the selector?*

The selector is represented by ```h2```.

### *Which components are the CSS declarations?*

The CSS declarations are:
```color: black;```
```padding: 5px;```

### *Which components are considered properties?*

The components ```color and padding``` are considered properties within the CSS declarations.

# Learn JS

## JavaScript Basics

### *What data type is a sequence of text enclosed in single quote marks?*

A sequence of text enclosed in single quote marks is a string data type in JavaScript.

### *List 4 types of JavaScript operators*

```Arithmetic Operators:``` These operators perform mathematical operations such as addition (+), subtraction (-), multiplication (*), division (/), and more.

```Assignment Operators:``` which assign a value to a variable

```Strict Equalitty:```This performs a test to see if two values are equal and of the same data type. It returns a true/false (Boolean) result.

```Not,Does-not-equal:```This returns the logically opposite value of what it precedes. It turns a true into a false, etc.. When it is used alongside the Equality operator, the negation operator tests whether two values are not equal.

### *Describe a real world Problem you could solve with a Function*

JavaScript functions can also be used to solve real-world problems related to passwords, such as password strength validation and password encryption.

## *Making Decisions In Your Code - Conditionals*

### *An if statement checks a __ and if it evaluates to ___, then the code block will execute*

> Answer: An if statement checks a condition and if it evaluates to true, then the code block will execute.

### *What is the use of an ```else if```?*

He use of an "else if" statement is to provide an alternative condition to check if the previous condition in an if statement is false. If the initial condition is false, the "else if" statement allows you to check for another condition. If that condition evaluates to true, the corresponding code block will execute. It allows for multiple conditional branches in your code logic.

### List 3 different types of comparison operators.

```Equal to (==):``` Checks if two values are equal, regardless of their data types.

```Not equal to (!=):``` Checks if two values are not equal.

```Greater than (>):``` Checks if the value on the left side is greater than the value on the right side.


### *What is the difference between the logical operator ```&&``` and ```||```?*

```&& (AND): The && operator``` returns true if both operands are true, and false otherwise. It evaluates the expressions from left to right and stops evaluating as soon as it finds a false value. If all operands are true, the result is the last true value encountered.

```|| (OR): The || operator``` returns true if at least one of the operands is true, and false if both operands are false. It evaluates the expressions from left to right and stops evaluating as soon as it finds a true value. If all operands are false, the result is the last false value encountered.
