# Context API - Behaviors

## Scaling Up with Reducer and Context

**How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)**

`useReducer` is a hook that allows you to manage state in a more predictable way by reducing a collection of actions to a single state object. It accepts a reducer function as its first argument, which takes the current state and an action as its arguments and returns the new state. `useContext` is a hook that allows you to consume data that is provided by a parent component without having to pass the data down through intermediate components as props. This can simplify the code and make it easier to manage state.

Combining these two hooks allows you to create a centralized store of state that can be accessed and modified by any child component that needs it. You can further declutter the components by moving all wiring into one file.

From[Scaling Up with Reducer and Context](https://react.dev/learn/scaling-up-with-reducer-and-context)

[Back to Home](../README.md)
