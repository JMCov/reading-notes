# Advanced State with Reducers

## useReducer hook

**Name an alternative to the useState Hook.**

useReducer

**Why might the useReducer Hook be preferable to the useState Hook?**

useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

From [Hooks API Reference](https://legacy.reactjs.org/docs/hooks-reference.html#usereducer)

**What are two ways to set the initial state?**

Either pass it as a second argument to useReducer or pass an init function as a third argument to allow you to extract the logic for calculating the initial state

## Ultimate Guide to useReducer

**In terms of state, what does useReducer expect to receive as a parameter?**

a reducer function

**What does useReducer return?**

an array that holds the current state value and a dispatch function to which you can pass an action and later invoke it

From [React useReducer Hook ultimate guide](https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/)

**Explain dispatch to a non-technical recruiter.**

It sends the type of action to the reducer function to perform its job which is updating the state


[Back to Home](../README.md)