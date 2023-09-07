# State and Props

## React Lifecycle

### Based off the diagram, what happens first, the 'render' or the 'componentDidMount?

When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

### WHat is the very first thing to happen in the lifecycle of React?

 Imagine you're building with LEGO blocks. The first thing you do is pick out all the pieces you need. In React, the very first thing is like picking your LEGO pieces. It's called the "constructor."

### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.

React is like a recipe. You have steps to follow. First, you decide what tools you need (constructor). Then, you start putting things together (render). When you're done, you might want to add some finishing touches (componentDidMount). If you want to change something, you can (React Updates). And when you're finished, you can clean up (componentWillUnmount).

### What does CoponentDidMount Do?

Think of componentDidMount as the step where you invite friends over to see what you've built. It's like having a party to show off your creation.

## React State Vs Props

In React, you have two ways to give information to your components. "Props" is like passing notes to your friends. You can share things with them. "State" is like your personal notes. You can write and change them, but they're private to you.

### What types of things can you pass in the props?

 With props, you can give information to your components. It's like giving them instructions on how to look or what to say. For example, you can tell a button what color it should be.

### What is the big difference between props and state?

The big difference is that props are for sharing information between components. Everyone can see them. State is for your component's personal information. It's private and can only be changed by that component.

### When do we re-render out application?

 In React, we re-render when we want to change how things look on our website or app. It's like updating a webpage when you want it to show something new.

### WHat are some examples of things that we could store in state?

Let's say you have a search bar on your website. When a user types something into the search bar, you want to remember what they typed, right? You can use state to store this input value.
