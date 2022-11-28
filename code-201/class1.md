# Intro to HTML

**Compose a short poem describing how HTTP sends data between computers.**

HTTP Haiku

Browser finds website
Browser sends request for copy
Approved request good

**Describe how HTML, CSS, and JS files are “parsed” in the browser.**

- The browser parses the HTML file first, and leads to the browserrecognizing any `<link>`element references to external CSS stylesheets and any `<script>` element references to scripts.
- As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.
- The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
- As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

**How can you find images to add to a Website?**

There are many ways to add images to a website.  One of the eassiest is to use Google.com and search for images that you would like to use. When you find one right-click the image and choose *Save Image As...*, and save it in your preferred folder.

**How do you create a String vs a Number in JavaScript?**

Declaring Strings vs. Numbers can be done with the following code:

**String** - `var = 'Jordan';`
**Number** - `var = 13;`

A String is declared by using a pair of quotes.

**What is a Variable and why are they important in JavaScript?**

Variables are containers that store values. Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in an image gallery.

**What is an HTML attribute?**

Attributes contain extra information about the element that won't appear in the content. For example,

`<p class="Cars">Ford Mustang</p>`

In this example class="Cars" creates a class to target the element with style information.

An attribute should have:

- A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
- The attribute name, followed by an equal sign.
- An attribute value, wrapped with opening and closing quote marks.

**Describe the Anatomy of an HTML element.**

`<p>Hello World!</p>`

The anatomy of an element is:

- **The opening tag**: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect.
- **The content**: This is the content of the element. In this example, it is the "Hello World!".
- **The closing tag**: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

The element is the opening tag, followed by content, followed by the closing tag.

**What is the Difference between `<article>` and `<section>` element tags?**

- `<article>` encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).
- `<section>` is similar to `<article>`, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. It's considered best practice to begin each section with a heading; also note that you can break `<article>s` up into different `<section>s`, or `<section>s` up into different `<article>s`, depending on the context.

**What Elements does a “typical” website include?**

- Header: `<header>`.
- Navigation bar: `<nav>`.
- Main content: `<main>`, with various content subsections represented by `<article>`, `<section>`, and `<div>` elements.
- Sidebar: `<aside>`; often placed inside `<main>`.
- Footer: `<footer>`.

**How does metadata influence Search Engine Optimization?**

Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the `<meta>` element. Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines.

**How is the `<meta>` HTML tag used when specifying metadata?**

The `<meta>` tag is used for:

- Specifying a page's character encoding `<meta charset="utf-8" />`
- Adding an author `<meta name="author" content="Jordan Covington" />`
- Adding a description `<meta name="description" content="Reading Notes Repo" />`

**What is the first step to designing a Website?**

Define what you want to accomplish with it.

**What is the most important question to answer when designing a Website?**

What exactly do I want to accomplish?

**Why should you use an `<h1>` element over a `<span>` element to display a top level heading?**

`<span>` will render it to look like a top level heading, but it has no semantic value, so it will not get any of the extra benefits as `<h1>` would.

**What are the benefits of using semantic tags in our HTML?**

- Search engines will consider its contents as important keywords to influence the page's search rankings
- Screen readers can use it as a signpost to help visually impaired users navigate a page
- Finding blocks of meaningful code is significantly easier than searching through endless `div`s with or without semantic or namespaced classes
- Suggests to the developer the type of data that will be populated
- Semantic naming mirrors proper custom element/component naming

**Describe 2 things that require JavaScript in the Browser?**

**Browser APIs** are built into your web browser, and are able to expose data from the surrounding computer environment, or do useful complex things

**Third party APIs** are not built into the browser by default, and you generally have to grab their code and information from somewhere on the Web.

**How can you add JavaScript to an HTML document?**

JavaScript is applied to your HTML page in a similar manner to CSS. Whereas CSS uses `<link>` elements to apply external stylesheets and `<style>` elements to apply internal stylesheets to HTML, JavaScript only needs the `<script>` element. JavaScript can be added internally, externally, or inline.

## Things I want to know more about

I want to learn more about JavaScript to improve my web development skills.  I specifically need to learn as much syntax as I can.

[Back to Home](../README.md)
