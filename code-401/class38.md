# Redux - Asynchronous Actions

## async actions

**Why use Redux middleware?**

If you wanted to enable async logic

**Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.**

The UI layer dispatches an action, which is intercepted by the middleware, which in turn dispatches a new action to update the state. The updated state is then passed back up to the UI layer to be rendered.

**How are we accommodating async in our Redux app?**

REST API

## thunk middleware

**Why would you need redux-thunk middleware?**

With a plain basic Redux store, you can only do simple synchronous updates by dispatching an action. Middleware extends the store's abilities, and lets you write async logic that interacts with the store.

Thunks are the recommended middleware for basic Redux side effects logic, including complex synchronous logic that needs access to the store, and simple async logic like AJAX requests.

From [Thunk GitHub](https://github.com/reduxjs/redux-thunk)

**Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.**

function

**Describe how any return value from the inner thunk function will be made available.**

Any return value from the inner function will be available as the return value of dispatch itself

From [Thunk GitHub](https://github.com/reduxjs/redux-thunk)

[Back to Home](../README.md)
