# AWS: API, Dynamo and Lambda

## AWS API Gateway Overview

**What is Amazon API Gateway?**

Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.

From [Amazon API Gateway](https://www.serverless.com/guides/amazon-api-gateway)

**Why is Amazon API Gateway an important part of the Serverless ecosystem?**

Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.

From [Amazon API Gateway](https://www.serverless.com/guides/amazon-api-gateway)

**How does API Gateway integrate with other AWS services?**

API Gateway supports direct integrations that can be configured in the API Gateway user interface (or via the API Gateway’s own API) for the following actions:

- Invoking an AWS Lambda function.
- Invoking another HTTP endpoint, with or without VPC Link.
- Making an HTTP call against the API of any AWS service that provides an HTTP API.
- Returning a mock response generated within API Gateway without calling out to other services.

From [Amazon API Gateway](https://www.serverless.com/guides/amazon-api-gateway)

## AWS API Gateway

**What are the some benefits of using Amazon API Gateway?**

- Efficent API development
- Performance at any scale
- Cost saving at scale

**What two API types might you choose from?**

RESTful and Web Socket APIs

## AWS DynamoDB Guide

**What is DynamoDB?**

DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS)

From [What is DynamoDB?](https://www.dynamodbguide.com/what-is-dynamo-db/)

**Under what circumstances would you recommend DynamoDB over MongoDB?**

If you want a more hands off operations model and so you don't have to worry about instances or scaling up or down.

## AWS DynamoDB

**Explain to a non-technical friend how DynamoDB works.**

Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-Region replication, in-memory caching, and data import and export tools.

From [Amazon DynamoDB](https://aws.amazon.com/dynamodb/)

## Dynamoose

**What is Dynamoose?**

Dynamoose is a modeling tool for Amazon's DynamoDB.

**What are some key features of Dynamoose?**

- Type safety
- High level API
- Easy to use syntax
- DynamoDB Single Table Design Support
- Ability to transform data before saving or retrieving items
- Strict data modeling (validation, required attributes, and more)
- Support for DynamoDB Transactions
- Powerful Conditional/Filtering Support
- Callback & Promise support
- AWS Multi-region support

From [Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

## Things I want to know more about

How DynamoDB could be used for future projects.

[Back to Home](../README.md)
