# Message Queues

## Socket.io Chat Example

**Explain to a non-technical recruiter what the Chat Example (above) does.**

It creates a chat room where multiple users can join the chat

**What proof of life are we getting on the backend from the above app?**

The console log showing which port is connected

**Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?**

The broadcast flag

## Rooms

**What is a room and how might a room be useful?**

A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients

From [Rooms](https://socket.io/docs/v4/rooms)

**How do you join a room?**

You can call join to subscribe the socket to a given channel:

``` Javascript
io.on("connection", (socket) => {
  socket.join("some room");
});
```

And then simply use to or in (they are the same) when broadcasting or emitting:

``` Javascript
io.to("some room").emit("some event");
```

From [Rooms](https://socket.io/docs/v4/rooms)

**how do you leave a room?**

To leave a channel you call leave in the same fashion as join.

## Namespaces

**What is a Namespace and what does it allow you to do?**

A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

From [Namespaces](https://socket.io/docs/v4/namespaces/)

**Each namespace potentially has its own what?**

1. Event Handlers
2. Rooms
3. Middlewares

**Discuss a possible use case for separate namespaces.**

Namespaces separated by roles can be used

## Reflection

**What are your learning goals after reading and reviewing the class README?**

This material is a very dry read I am mainly wanting to see how namespaces are used.

[Back to Home](../README.md)
