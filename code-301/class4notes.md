# React Docs - Forms

### What is a ‘Controlled Component’?

A 'Controlled Component' in React is a component that renders form elements and controls them by keeping the form data in the component's state. The React component that renders the form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React is called a "controlled component".

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?

You should update state with the user's responses as soon as they enter them. This allows you to have instant access to the dater entered by the user, and you can also perform real time validations or transformations on the input data.

### How do we target what the user is entering if we have an event handler on an input field?

To taget what the user is entering, you use the 'event' object that is passed to the event handler.

## The Conditional (Ternary) Operator Explained

### Why would we use a ternary operator?

We use a ternary operator as a shorthand way of writing an 'if-else' statement. It's useful when you want to assign a value to a variable base on a condition or when you want to perform a simple action vased on an condition.

### Rewrite the following statement using a ternary statement:

> if(x===y){
  console.log(true);
} else {
  console.log(false);
}

>console.log(x===y ? true : false); 