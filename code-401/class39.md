# Redux - Additional Topics

## Redux Toolkit (RTK)

**What concerns are addressed by Redux Toolkit?**

1. "Configuring a Redux store is too complicated"
2. "I have to add a lot of packages to get Redux to do anything useful"
3. "Redux requires too much boilerplate code"

From [Getting Started with Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)

**What does configureStore() do?**

It wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

From [Getting Started with Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)

**How would I use createSlice()?**

createSlice() accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

From [Getting Started with Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)

## MobX

**What is Mobx?**

A scalable state manager

**How does MobX make it “impossible” to produce an inconsistent state?**

Make sure that everything that can be derived from the application state, will be derived. Automatically.

From [MobX](https://mobx.js.org/getting-started.html)

**How would we build a reactive user interface?**

By using the observer HoC wrapper that wraps React components to autorun

## Tutorial

**What take-away(s) did this tutorial provide?**

The big takeaway for me is there are a pethora of documentation regarding redux. 

[Back to Home](../README.md)
