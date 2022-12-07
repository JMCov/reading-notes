# CSS Layout

**Flexbox is designed for one-dimensional content. Explain what this means.**

When a flex container wraps it creates multiple flex lines. In terms of space distribution, each line acts like a new flex container. Therefore if you are wrapping rows, it is not possible to get something in row 2 to line up with something above it in row 1. This is what is meant by flexbox being one-dimensional. From [Flexbox](https://web.dev/learn/css/flexbox/)

**Explain the difference between the main axis and cross axis.**

- The **main axis** is the one set by your `flex-direction` property. If that is `row` your main axis is along the row, if it is `column` your main axis is along the column. From [Flexbox](https://web.dev/learn/css/flexbox/)

- The **cross axis** runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column. From [Flexbox](https://web.dev/learn/css/flexbox/)

**How can using certain properties of flexbox negatively impact accessibility?**

There are certain properties that can reorder the visual display

**What are some advantages of using flexbox over float?**
Floats make the following layout designs hard or impossible to achieve:

- Vertically centering a block of content inside its parent.
- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

**How does this topic connect with your long term goals?**

I am not too familiar with CSS.  Since the course started I have become more familiar with it however it is still my weakest part of the class. I want to be able to make visually appealing websites.

## Things I want to know more about

I hope that Flexbox is able to teach me easier ways to style webpages in today's lecture.

[Back to Home](../README.md)
