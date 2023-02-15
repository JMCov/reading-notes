# Express REST API


## Review: ES6 Classes

**Classes are a template for creating ____.**

Objects

**Can a class declaration be hoisted?**

No.

**How would you describe a constructor and contextual “this” to a non-technical friend?**

A constructor is a function that is called when a new class is created. This new class will have access to the constructor prototype.  You can reference it wth the this `keyword`

## Using Express Routing

**Within Express, what does routing refer to?**

How an application’s endpoints respond to client requests.

**What is the difference between a route path and a route method?**

A route method is derived from one of the HTTP methods, and is attached to an instance of the express class. Examples are GET, POST, PUT, DELETE.

Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.

From [Routing](https://expressjs.com/en/guide/routing.html)

**When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?**

You can provide multiple callback functions that behave like middleware to handle a request. The only exception is that these callbacks might invoke next('route') to bypass the remaining route callbacks. You can use this mechanism to impose pre-conditions on a route, then pass control to subsequent routes if there’s no reason to proceed with the current route.

From [Routing](https://expressjs.com/en/guide/routing.html)

## Express Routing

**What is an Express Router?**

It is a mini express application without all the bells and whistles of an express application, just the routing stuff.

From [Learn to Use the New Router in ExpressJS 4.0](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)

**By what mean do we initialize express.Router() in an express server?**

`var router = express.Router();`

**What do we use route middleware for?**

Route middleware in Express is a way to do something before a request is processed. This could be things like checking if a user is authenticated, logging data for analytics, or anything else we’d like to do before we actually spit out information to our user.

From [Learn to Use the New Router in ExpressJS 4.0](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)


## Reflection

**What are your learning goals after reading and reviewing the class README?**

It appears a lot of this lecture will be review mixed with applying SQL to the REST API so I am planning on solidifying my knowledge in that area.

## Things I want to know more about

Routes. I want to learn how to code a more efficient website.

[Back to Home](../README.md)