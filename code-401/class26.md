# Component Based UI

## Your First Component

**What are the building blocks of a React app?**

Components

**What is the difference between an element and a React component?**

React lets you combine your markup, CSS, and JavaScript into custom “components”, reusable UI elements for your app

A React component is a JavaScript function that you can sprinkle with markup.

From [Your First Component](https://react.dev/learn/your-first-component)

**What are some advantages of React’s component based architecture?**

Reusable code, easier to debug, easier to update code.

## introducing JSX

**What is JSX and why do we use it?**

It is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both.

From [Introducing JSX](https://legacy.reactjs.org/docs/introducing-jsx.html)

**Describe the process of embedding JavaScript expressions in JSX.**

You declare a variable and use it within JSX by wrapping it in curly brackets

**Is it safe to embed user input in JSX? Explain.**

Yes, By default, React DOM escapes any values embedded in JSX before rendering them. Thus it ensures that you can never inject anything that’s not explicitly written in your application. Everything is converted to a string before being rendered. This helps prevent XSS (cross-site-scripting) attacks.'

From [Introducing JSX](https://legacy.reactjs.org/docs/introducing-jsx.html)

## rendering elements

**Explain what a React Component is to a non-technical friend.**

It is something you can reuse over and over again so you don't have to spend time recoding similar things

**Describe mutability and React Components, specifically, how is the UI updated?**

React elements are immutable. Once you create an element, you can’t change its children or attributes. An element is like a single frame in a movie: it represents the UI at a certain point in time. React DOM compares the element and its children to the previous one, and only applies the DOM updates necessary to bring the DOM to the desired state.

From [Rendering Elements](https://legacy.reactjs.org/docs/rendering-elements.html)

**If changes are made to the UI, what does React update?**

DOM

## Things I want to know more about

It's been awhile since I used React so diving back in will be nice.  I would like to see how it all comes together.

[Back to Home](../README.md)
