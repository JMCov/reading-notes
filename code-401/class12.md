# Socket.io

## Web Sockets

What is a Web Socket?

A computer communications protocol, providing full-duplex communication channels over a single TCP connection.

From [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

**Describe the Web Socket request/response handshake and what happens once the connection is established.**

Once the connection is established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol.

From [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

**Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.**

request

## Socket.io Tutorial

**What does the event handler io.on() do?**

It handles connection, disconnection, and events inside of it.

**Describe some possible proof of life or proof that the code works as expected.**

You can console log after the server is expected to be running for proof

**What does socket.emit() do?**

Allows you to create and use custom events

## Socket.io vs Web Sockets

**What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).**

**WebSocket** is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the Client or server to terminate the request.

**Socket.IO** is a library that enables real-time and full-duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts; both WebSocket vs Socket.io are event-driven libraries.

- Client-Side: it is the library that runs inside the browser
- Server Side: It is the library for Node.js

From [WebSocket vs Socket.io](https://www.educba.com/websocket-vs-socket-io/)

**When would you use Socket.IO?**

When you need broadcasting and fallback options

**When would you use WebSockets?**

When there is no need for broadcasting and fallback options

## OSI Model Explained

**What are a couple of key takeaways from this video?**

It defines and is used to understand how data is transfered between computers.

It allows to transfer data between computer with different operating systems

**Application Layer** - Human-Computer interaction layer, where applications can access the network services

**Presentation Layer** - Ensures that data is in a usable format and is where data encryption occurs.

**Session Layer** - Maintains connections and is responsible for controlling port and session.

**Transport Layer** - Transmits data using transmission protocols including TCP and UDP

**Network Layer** - Decides which physical path the data will take

**Physical Layer** - Transmits raw bit stream over the physical medium

## TCP Handshakes Explained

**Translate the gist of this video to a non-technical friend**

TCP connection must be established with a 3-way handshake.  It is similar to ordering something at a resturant.  You ask for your order (1st step), the server says yes but requests money (2nd step), finally you give your money (3rd step).

## Reflection

**What are your learning goals after reading and reviewing the class README?**

Understanding Websockets and how they work is something that doesn't make much sense in reading.

## Things I want to know more about

I want to learn more about web sockets.

[Back to Home](../README.md)
