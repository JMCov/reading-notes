# Application State with Redux

## Dan Abramov Redux Tutorials

**What is the first principle of Redux?**

To represent the whole state of your application as a single JavaScript object

**what is a store and what do we use our reducers for within that store?**

A store is a central container that holds the entire state tree of your application.
Reducers are pure functions that take the current state and an action as arguments, and return a new state.

**Name three Redux store methods given to us by createStore and describe their use.**

`getState()`: This method returns the current state of the store.

`dispatch()`: It lets you dispatch actions to change the state of your application. If we log this chore state after dispatch, we're going to see that it has changed.

`subscribe()`: It lets you register a callback that the Redux chore will call any time an action has been dispatched, so that you can update the UI of your application. It will reflect the current application state.

**Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.**

`combineReducers()`is a function provided by Redux that is used to combine multiple reducers into a single reducer function. The main benefit of using `combineReducers()` is that it makes it easier to manage complex state structures in a Redux application. As an application grows the state becomes quite large and complex, with many different pieces of state that need to be managed.

## Things I want to know more about

This seems to be another way of doing state.  I guess my big questions is out of all the methods we have been taught which is the best? How will I know when to use each one?

[Back to Home](../README.md)
