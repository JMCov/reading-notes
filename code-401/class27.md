# useState() Hook

## Introducing Hooks

**What was the motivation for introducing Hooks?**

Hooks solve a wide variety of seemingly unconnected problems in React that we’ve encountered over five years of writing and maintaining tens of thousands of components.

From [Introducing Hooks](https://legacy.reactjs.org/docs/hooks-intro.html#motivation)

**What changes are important regarding implementing Hooks versus Component Classes?**

They are 100% backwards compatiable

**Hooks allow you to reuse stateful logic without changing ___ _______.**

Component hierarchy

## hooks api

**Name two rules imposed by React Hook usage.**

1. Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
2. Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)

From [Hooks at a Glance](https://legacy.reactjs.org/docs/hooks-overview.html)

**How would you identify a custom Hook and why might you create one?**

if the functions name starts with use and calls other hooks it is a custom hook. You could create one to handle forms.

## the state hook

**What is a Hook?**

They let you use state and other React features without writing a class.

**When would I use the useState Hook?**

When you need to add React State to function components

**If you were to add React state to a function component by declaring a state variable:**

    **What does calling useState do?**

       Adds state

    **What do we pass to useState as an argument?**

        the initial state

    **What does useState return?**

      the current state and a function that updates it

## Things I want to know more about

How hooks could have made my 301 projects better.

[Back to Home](../README.md)
