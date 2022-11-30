# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML

**When should you use an `unordered list` in your HTML document?**

For grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless.

**How do you change the `bullet style` of unordered list items?**

By using the attribute `type`

**When should you use an `ordered list` vs an `unorder list` in your HTML document?**

The `<ol>` and `<ul>` elements both represent a list of items. The difference is with the `<ol>` element, the order is meaningful.

**Describe two ways you can change the numbers on `list items` provided by an `ordered list`?**

Using the `type` attribute and assigning it as a Roman numeral or using the `start` attribute and assigning it a certain number to start at.

## CSS

**Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?**

The Box model family loves each other. `Padding` hugs his child named `content` wrapping his arms completely around him.  `Padding`'s wife `margin` walks in the room and hugs her child and husband wrapping her arms completely around them.  The end.

**List and describe the four parts of an HTML elements box as referred to by the `box model`.**

1. **Content box**: The area where your content is displayed; size it using properties like `inline-size` and `block-size` or `width` and `height`.

2. **Padding box**: The padding sits around the content as white space; size it using `padding` and related properties.

3. **Border box**: The border box wraps the content and any padding; size it using `border` and related properties.

4. **Margin box**: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using `margin`** and related properties.

## JavaScript

**What `data types` can you store inside of an `Array`?**

Strings, numbers, objects and other arrays.

**Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?**

Yes, it is a valid array. You could access the first item of data in 2nd array by using, `people[1][0];`

**List five shorthand operators for assignment in javascript and describe what they do.**

**Division assignment** is written as `x /= f()` but actually means `x = x / f()`
**Remainder assignment** is written as `x %= f()` but actually means `x = x % f()`
**Multiplication assignment** is written as `x *= f()` but actually means `x = x * f()`
**Exponentiation assignment** is written as `x **= f()` but actually means `x = x ** f()`
**Subtraction assignment** is written as `x -= f()` but actually means `x = x - f()`

**Read the code below and evaluate the last `expression` and explain what the result would be and why.**

The result would be **10dog** because variable c is a Boolean and would not be displayed.  

**Describe a real world example of when a conditional statement should be used in a JavaScript program.**

A conditional statement could be used if you want to give a user options to select. Say you have options 1-5 and allow the user to select which they want.  You could take their input and store it in a variable and your conditional statement would trigger the block of code that the user selects.

**Give an example of when a `Loop` is useful in JavaScript.**

You could use a loop to go through an array sorting or searching for certain items within it.

## Things I want to know more about

I am familiar with arrays but would like to know more real world examples of how they can be useful.

[Back to Home](../README.md)
