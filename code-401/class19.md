# AWS: Events

## AWS SQS vs SNS

**What is the difference betweeen SQS and SNS?**

SNS is a distributed publish-subscribe service.

SQS is distributed queuing service.

**What are some use cases for both SNS and SQS?**

Choose SNS if:

- You would like to be able to publish and consume batches of messages.
- You would like to allow same message to be processed in multiple ways.
- Multiple subscribers are needed.

Choose SQS if:

- You need a simple queue with no particular additional requirements.
- Decoupling two applications and allowing parallel asynchronous processing.
- Only one subscriber is needed.

From [AWS — Difference between SQS and SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

## AWS SNS and SQS

**Describe how to use SQS and SNS in a “fanout” pattern.**

SNS is an AWS service that coordinates and manages the delivery or sending of messages to subscribing endpoints. It offers you the possibility to create an “SNS topic” which is a logical access point that acts as a communication channel. By using AWS CLI, SDK, or the web console, you can start publishing messages to this topic. The SNS topic will forward the messages to its subscribers. One of the possible subscribers is SQS, which is the queuing service of AWS. You can subscribe multiple queues to the same topic to replicate a message over multiple queues. This is called fan-out.

From [How to Fan-Out to Different SQS Queues Using SNS Message Filtering](https://betterprogramming.pub/how-to-fan-out-to-different-sqs-queues-using-sns-message-filtering-84cd23ed9d07)

**Explain how “push notifications” work, using SNS.**

When an app and mobile device register, the push notification service returns a device token. Amazon SNS uses the device token to create a mobile endpoint, to which it can send direct push notification messages. In order for Amazon SNS to communicate with the different push notification services, you submit your push notification service credentials to Amazon SNS to be used on your behalf.

From [Mobile push notifications](https://docs.aws.amazon.com/sns/latest/dg/sns-mobile-application-as-subscriber.html#sns-how-user-notifications-work)

## SQS and SNS Basics

**How might a large scale, distributed application make use of a Queue system like SQS?**

- Separate Throughput from Latency 
- Use Batch APIs Wherever Relevant
- Tradeoff Message Durability and Latency

From [Scaling with Amazon SQS](https://aws.amazon.com/blogs/aws/scaling-with-amazon-sqs/)

[Back to Home](../README.md)