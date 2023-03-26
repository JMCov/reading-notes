# `<Login />` and `<Auth />`

## What is Role Based Access Control (RBAC)?

**What is Role Based Access Control (RBAC)?**

Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

From [What is Role-Based Access Control (RBAC)?](https://www.digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

**Share some an example of RBAC including all possible CRUD operations and correlating roles.**

Roles:

- Admin: Can perform all CRUD operations on all resources.
- User: Can send and receive messages, create groups, and manage their own account.

Permissions:

  - Admin:

    - Create, read, update, and delete all messages.
    - Create, read, update, and delete all groups.
    - Create, read, update, and delete all user accounts.

  - User:

    - Send and receive messages.
    - Create and manage their own groups.
    - Update and delete their own account.

**What are the Benefits of RBAC?**

1. Reducing administrative work and IT support.
2. Maximizing operational efficiency.
3. Improving compliance.

## react-cookie library & react-cookies component

**Describe some `react-cookie` features.**

- Provides a simple API for managing cookies in a React application
- Provides options for setting custom cookie options such as expiration time, domain, and path.
- The library is lightweight and has no external dependencies, which makes it easy to use and integrate with other libraries.

**Describe some `react-cookies` features.**

- Provides a simple and easy-to-use API for getting, setting, and removing cookies.
- Provides options for setting custom cookie options such as expiration time, domain, and path.
- Automatically parses cookies into a JSON object, which makes it easy to work with and access individual values.

**Which library would you prefer would you prefer? Why?**

Probably react-cookie because the methods are simple with the naming convention being set, get, remover, and getAll. Also react-cookie has no external dependencies whereas react-cookies does.

## Things I want to know more about

I'm interested in what react-cookie can do for me once implemented.

[Back to Home](../README.md)
