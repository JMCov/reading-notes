# Putting it all together

## React Docs - Thinking in React

**What is the single responsibility principle and how does it apply to components?**

Single responsibility principle means a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

**What does it mean to build a ‘static’ version of your application?**

Now that you have your component hierarchy, it’s time to implement your app. The easiest way is to build a version that takes your data model and renders the UI but has no interactivity. It’s best to decouple these processes because building a static version requires a lot of typing and no thinking, and adding interactivity requires a lot of thinking and not a lot of typing.

From [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

**Once you have a static application, what do you need to add?**

Add minimal representation of UI State

**What are the three questions you can ask to determine if something is state?**

1. Is it passed in from a parent via props? If so, it probably isn’t state.
2. Does it remain unchanged over time? If so, it probably isn’t state.
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

From [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

**How can you identify where state needs to live?**

For each piece of state in your application:

- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

From [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

## Higher-Order Functions

**What is a “higher-order function”?**

Functions that operate on other functions, either by taking them as arguments or by returning them.

From [Higher-order functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

**Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

It passes a value (n) and returns whether or not m is greater or not when called in another function.

**Explain how either map or reduce operates, with regards to higher-order functions.**

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.

From [Higher-order functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

## Things I want to know more about

Higher-order functions are still confusing to me hopefully today's lecture will help.

[Back to Home](../README.md)
