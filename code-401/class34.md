# API Integration

## Review API Server Build

**Explain the different between a query string parameter and a path parameter.**

Query string parameters are appended to the end of a URL, after a question mark ?, while path parameters are included as part of the URL path.

**What would our API URL with a path id parameter be given the following information:**

`http://our-site.com/v3/stuff/things`

**We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.**

A dynamic API with an “interface” allows users to interact with an API through a user-friendly interface instead of directly through the API's URL.

## Review Auth Server Build

**Describe how you would use middleware to implement basic and bearer auth.**

Middleware can be used to implement basic and bearer auth by intercepting requests and verifying the user's credentials before allowing the request to proceed. Basic auth involves sending a username and password with each request, while bearer auth involves sending a token.

**Describe the handshake necessary to implement OAuth.**

The handshake necessary to implement OAuth involves the client requesting authorization from the user, redirecting the user to the authorization server, the user granting authorization, and the authorization server issuing an access token to the client.

**Describe how Role Based Access Control works to a non-technical friend.**

 RBAC is like a system where people are given different levels of access to a building based on their job title or responsibilities, with some people having access to more areas than others based on their role in the organization.

[Back to Home](../README.md)
