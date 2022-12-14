# Local Storage

## Local Storage and How To Use It On Websites

**Why would a developer use local storage for a web application?**

The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored. This is why, as a developer, you need to store the state of your interface somewhere. Normally, this is done server-side, and you would check the user name to know which state to revert to.

From [Local Storage And How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

**What information should not be stored in local storage?**

Malicious software can be used to exploit a user's computer through local storage.

**Local storage can store what type of data? How would you convert it to that type before storing?**

It can only store strings, however you can convert strings by by using the native `JSON.stringify()` and `JSON.parse()` methods

## What I would like to know more about

I would like to learn what the limitations of local storage can be.

[Back to Home](../README.md)
