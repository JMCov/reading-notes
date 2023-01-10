# State and Props

## React lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render

2. What is the very first thing to happen in the lifecycle of React?

When a component is being created the first thing that occurs is the Mounting phase.

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, render, react updates, componentDidMount, componentWillUnmount

4. What does componentDidMount do?

 If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.

From[React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

## React State Vs Props

1. What types of things can you pass in the props?

Props are like arguments to a function. Pass the arguments that you want use in your component.

2. What is the big difference between props and state?

State is handled inside the component and you can update it inside the component while props are outside and must be updated outside the component.

3. When do we re-render our application?

When you change the state inside your application.

4. What are some examples of things that we could store in state?

- A form that a user fills out.

- A counter function that needs to update the count of something.

## Things I want to know more about

I need to practice more with React!

[Back to Home](../README.md)
