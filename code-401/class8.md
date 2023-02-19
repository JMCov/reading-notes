# Access Control (ACL)

## 5 steps to RBAC

**What is Role Based Access Control (RBAC) and why do we care?**

RBAC is the idea of assigning system access to users based on their role within an organization. The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs. Access is then assigned to each person based strictly on their role assignment. With tight adherence to access requirements established for each role, access management becomes much easier.

From [5 steps to simple role-based access control](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

**Describe a Role/Permission heirarchy that you might implement using RBAC.**

**Access control lists (ACL)** — An ACL is a means of defining access rights by a given user or user group, to a specific object, such as a document.  As a simple example, an ACL could be used to allow users from one department to make changes to a document, while only allowing users from other departments to read the document.

From [5 steps to simple role-based access control](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

**What approach might you take to implement RBAC?**

Analyze your workforce and create roles:

You need to group your workforce members into roles with common access needs.  Avoid the temptation to have too many roles defined. Keep them as simple and stratified as possible.

For example, you might have a basic user role, which includes the access any employee would need, such as email and the intranet site. Another role might be a customer service rep, that would have read/write access to the customer database, and a customer database administrator, that would have full control of the customer database.

From [5 steps to simple role-based access control](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

## wiki - RBAC

**If Authentication is “you are who you say you are,” what is Authorization?**

It determines whether the authenticated user has access to whatever is they are trying to retrieve.

**Name three primary rules defined for RBAC.**

1. **Role assignment**: A subject can exercise a permission only if the subject has selected or been assigned a role.
2. **Role authorization**: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
3. **Permission authorization**: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

From [Role-based access control](https://en.wikipedia.org/wiki/Role-based_access_control)

**Describe RBAC to a non-technical friend.**

RBAC is like setting up permissions to a streaming application so that children can only access certain movies.

## RBAC tutorial

**What Are access rights Associated with? The User? or The Role? Explain.**

The role. You determine what role the user has access to and allow them based off their roles.

**Access Rights, or Authorization, is activated after a user successfully does what?**

Once authentication is complete, and roles are determined.

**Explain how RBAC might benefit a business.**

Policies don't need to be updated when a cerain person with a role leaves. When a new employee arrives you only need to determine what role they take.  

## Reflection

**What are your learning goals after reading and reviewing the class README?**

To learn how the back end and front end handles authorization and roles.

## Things I want to know more about

RBAC implementation on our existing websites. 

[Back to Home](../README.md)