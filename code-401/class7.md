# Bearer Authorization

## Intro to JWT

**What is a JSON Web Token (JWT)?**

An open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

From [Introduction to JSON Web Tokens](https://canvas.instructure.com/courses/6088303/discussion_topics/17042647)

**When should we use JSON Web Tokens?**

For Authorization and Information exchange.

**Claims are expected in which structural component of a JWT?**

Payload

## Are JWTs Secure?

**If I get a JWT and I can decode the payload, how can we call that secure?**

We cannot store any sensitive data in here. But that's not a problem at all because in the third part, so in the signature, is where things really get interesting. The signature is created using the header, the payload, and the secret that is saved on the server.

And this whole process is then called signing the Json Web Token. The signing algorithm takes the header, the payload, and the secret to create a unique signature. So only this data plus the secret can create this signature, all right? Then together with the header and the payload, these signature forms the JWT, which then gets sent to the client.

From [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**

The hash.

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**

It is similar to two people knowing the combination of a locker. One person places something in the locker and later the recipient (who knows the combination) can retrieve what the first person placed.

## JWTs Explained

**Why use JWT?**

For Authentication and Information Exchange

**JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**

It is compact to the point where it can be fastly transmitted and sent in many different ways. It also contains information about the user and avoids querying the database more than once which speeds the process.

**What are the three components (the structure) of a JWT signature?**

Header, Payload, and Signature.

## Reflection

**What are your learning goals after reading and reviewing the class README?**

To learn more about JWT authentication.

## Things I want to know more about

How to make a website as secure as possible with the ways we have been taught.

[Back to Home](../README.md)