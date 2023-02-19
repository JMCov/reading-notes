# Authentication

## Securing Passwords

**Explain to a non-technical friend how you would safely hash and store a password.**

I would use an adapative hash function like Bcrypt. This makes brute forcing the hash of the password take longer and thus minimizes the impact of what the hacker will retrieve

**What is Bcrypt?**

Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be

From [Securing Passwords with Bcrypt Hashing Function](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

**Why might you use something like Bcrypt?**

To allow more time to secure your data because the hacking of the hash key will take longer than it should without using Bcrypt.

## Basic Auth

**What is Basic Authentication?**

A method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request. In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic `<credentials>`, where credentials is the Base64 encoding of ID and password joined by a single colon `:`.

From [Basic Authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)

**What properties are necessary in the header of a Basic Auth request?**

Credentials and a password are required.

**How are username:password in Basic Auth encoded?**

Base64 in transit and not encrypted or hashed.

## OWASP auth cheatsheet

**Define the authentication process to a non-technical recruiter.**

It is the process of verifying that an individual, entity, or website is who they claim to be.

**How should your error messaging respond (both HTTP and HTML)? Why?**

In a generic manner, in hopes that this prevents the creation of a discrepancy factor, allowing an attacker to mount a user enumeration action against the application.

**Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.**

The link: [Authentication Cheat Sheet¶](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

## Additional Questions

**Looking ahead at this module’s course schedule, What do you look forward to learning?**

How to secure a website in different ways and which methods should be used in given situations.

**What are your learning goals after reading and reviewing the class README?**

Authorization. It was not introduced until the end of 301. I didn't get a chance to work with it in my group project.

## Things I want to know more about

Same as above, I want to know about the authentication process.

[Back to Home](../README.md)
