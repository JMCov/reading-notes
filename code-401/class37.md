# Combined Reducers

## Multiple Reducers Example

**Why create multiple reducers?**

In Redux multiple reducers are used to handle different parts of the application state. By breaking down the application state into smaller parts and creating separate reducers for each part it becomes easier to manage and maintain the state.

**How would you combine multiple reducers?**

By using Redux's `combineReducers()` built in function

**How will you manage state as an immutable object? why?**

By creating new objects and arrays using the spread operator so that a new copy of the state is created with the updated values, instead of modifying the original

## Redux Docs: Using Combined Reducers

**combineReducers is a utility function to simplify the most common use case when writing ___ _____ .**

Redux Reducers

**Explain how combineReducers assembles the new state tree.**

`combineReducers()` will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed.

From [Using combineReducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)

**How would you define initial state in an app using combineReducers?**

There are two ways to define the initial shape and contents of your store's state. First, the createStore function can take preloadedState as its second argument. This is primarily intended for initializing the store with state that was previously persisted elsewhere, such as the browser's localStorage. The other way is for the root reducer to return the initial state value when the state argument is undefined. These two approaches are described in more detail in Initializing State, but there are some additional concerns to be aware of when using combineReducers.

From [Using combineReducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)

## Redux Docs: Combined Reducer Syntax

**Why will you want to split your reducing functions as your app becomes more complex?**

So each reducer function an manage certain parts of the state. 

**The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.**

combineReducers/createStore

**What is a popular convention when naming reducers?**

Name the reducers after the state slices they manage

## Things I want to know more about

How all of this comes together for our Apps.  It would be nice to see how using multiple reducers is more beneficial than using one big one.

[Back to Home](../README.md)
