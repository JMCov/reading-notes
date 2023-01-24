# CRUD

## Status Codes Based On REST Methods

**In your own words, describe what each group of status code represents:**

100’s = Informational status code. Tells the client that a request has been received.
200’s = Success codes. Tell the client the request was accepted
300’s = Redirection codes. Tells the client the resource they requested isn't available.
400’s = Client error codes. Tells the client they requested something invalid.
500’s = Server error codes. Often associated with overwhelmed servers

**What is a status code 202?**

Accepted - If the deletion is asynchronous and takes some time, which is the case in distributed systems, it can be appropriate to return this code with some information or URL to tell the client when it will be deleted.

From[Which HTTP Status Code to Use for Every CRUD App](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

**at is a status code 308?**

Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

From[Which HTTP Status Code to Use for Every CRUD App](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)


**What code would you use if an update didn’t return data to a client?**

204 - No Content

**What code would you use if a resource used to exist but no longer does?**

410 Gone

**What is the ‘Forbidden’ status code?**

403 Forbidden

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**

So when we deploy it isn't the local host that is used. Also for security reasons

**What is middleware?**

Code that runs when the server gets a request but before it gets passed to your routes

**What does app.use(express.json()) do?**

Allows our server to accept JSON as a body instead of a post element

**What does the /:id mean in a route?**

It is a parameter giving us access to whatever they pass through after the /

**What is the difference between PUT and PATCH?**

PUT is a create route PATCH is a updating route

**How do you make a default value in a schema?**

naming a property Default and setting it equal to what you want it to be defaulted too. 

**What does a 500 error status code mean?**

That there is an error on your server

**What is the difference between a status 200 and a status 201?**

200 is everything was successful and 201 is a more specific way of saying it successfully created something.

## Things I want to know more about

I would like to have more hands on with what we learned in the video

[Back to Home](../README.md)