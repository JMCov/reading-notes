# APIs


## API Design Best Practices

**What does REST stand for?**

Representational State Transfer

**REST APIs are designed around a ____.**

Resources

**What is an identifier of a resource? Give an example.**

something that uniquely identifies a resource. An example would be our lab from yesterday with our URI ending in /weather

**What are the most common HTTP verbs?**

GET, POST, PUT, PATCH, and DELETE

**What should the URIs be based on?**

Nouns (the resource)

**Give an example of a good URI.**

It's a good practice to organize URIs for collections and items into a hierarchy. For example, /customers is the path to the customers collection, and /customers/5 is the path to the customer with ID equal to 5. This approach helps to keep the web API intuitive.

From [RESTful web API design](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

When a web API expose a large number of small resources. It is a bad thing.

**What status code does a successful GET request return?**

200

**What status code does an unsuccessful GET request return?**

204

**What status code does a successful POST request return?**

201

**What status code does a successful DELETE request return?**

204

## Things I want to learn more about

I would like to learn more about all of the status codes and more about APIs (what all APIs exist)

[Back to Home](../README.md)