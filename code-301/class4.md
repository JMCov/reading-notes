# React and Forms

## React Docs - Forms

**What is a ‘Controlled Component’?**

An input form element whose value is controlled by React.

**Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

In HTML, form elements such as `<input>`, `<textarea>`, and `<select>` typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

From[React Docs - Forms](https://reactjs.org/docs/forms.html)

**How do we target what the user is entering if we have an event handler on an input field?**

You can add a name attribute to each element and let the handler function choose what to do based on the value of `event.target.name`.

From[React Docs - Forms](https://reactjs.org/docs/forms.html)

## The Conditional (Ternary) Operator Explained

**Why would we use a ternary operator?**

You can reduce the amount of code you write if you need an if statement.

**Rewrite the following statement using a ternary statement:**

  ```js:
  if(x===y){
  console.log(true);
  } else {
  console.log(false);
  }
```

```js:
x===y ? console.log(true) : console.log(false);
```

## Things I want to know more about

If you have an if statement with more than 3 nested ifs can you still use a ternary statement?

[Back to Home](../README.md)
