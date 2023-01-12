# Passing Functions as Props

## React Docs - lists and keys

**What does .map() return?**

Nothing

**If I want to loop through an array and display each value in JSX, how do I do that in React?**

You can use a map function to put the array into a new array and then call the new array.

**Each list item needs a unique ____.**

Key.

**What is the purpose of a key?**

Keys help React identify which items have changed, are added, or are removed.

## The Spread Operator

**What is the spread operator?**

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

From[How to Use the Spread Operator (…) in JavaScript](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

**List 4 things that the spread operator can do.**

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments

**Give an example of using the spread operator to combine two arrays.**

```js:
  const firstArray = [`A`,`B`,`C`]
  const secondArray = [`D`,`E`,`F`]
  const combinedArray = [...firstArray,...secondArray]
```

**Give an example of using the spread operator to add a new item to an array.**

```js:
  const firstArray = ['C','D','E']
  const secondArray = ['A', 'B', ...firstArray]
```

**Give an example of using the spread operator to combine two objects into one.**

```js:
const objectOne = {Name: "Jordan"}
const objectTwo = {Age: "35"}
const objectThree = {...objectOne, ...objectTwo}
```

## Things I want to know more about

I would like to know more about how spread operators can be used to make working with arrays and objects easier.

[Back to Home](../README.md)
