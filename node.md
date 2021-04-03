# Node.js and npm

* node.js is based on the v8 engine which is an open source Javascript engine, and its also written in C++ so its fast.

* node.js comes with npm (node package manager) bond with it,Which is the world largest software registry

```Linux
npm init -y
```

> used to auto populate and create `package.json`file.

## usage of node js (and npm)

1. install(by npm ) and use (by node.js) various build tools designed to automate the process of developing modern javascript application.

2. React.js or Angular.js or any other modern JS frameworks are all available via npm and rely on node.js to run create a sensible development environment in which they can run.

3. **node.js runs javascript on the server**

## Node.js excution module

* it is a single threaded and event driven.

* Node’s execution model causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous connections.

![node.js execution module](https://uploads.sitepoint.com/wp-content/uploads/2012/10/1516152673node_event_loop.png)

> Source: Introduction To Node.js by Prof. Christian Maderazo, James Santos

* node.js uses `libvu` library to implement this asynchronous (that is, non-blocking) behavior.

* node.js single thread does impose limitation:
   1. blocking I/O calls should be avoided
   2. CPU-intensive operations should be handed off to a worker thread 
   3. errors should always be handled correctly for fear of crashing the entire process.

** this site ( [callback hell](http://callbackhell.com/) ) used to blog horror stories related from the usage of callbacks.

* node.js is used in real-time applications such as CodeShare

## Node.js advantages

*  speed and scalability.

* using the same language for server and browser 

* node.js speaks JSON (big advantage)

