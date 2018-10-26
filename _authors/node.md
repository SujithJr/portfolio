---
title: NodeJS
name: node-js
excerpt_separator: <!--more-->
permalink: node-js
layout: default
---
<img src="/assets/images/node-js.png" class="c-image">
As an asynchronous event driven JavaScript runtime, **NodeJS** is designed to build scalable network applications. 
<!--more-->
In the following "hello world" example, many connections can be handled concurrently. Upon each connection the callback is fired, but if there is no work to be done, Node will sleep.

This is in contrast to today's more common concurrency model where OS threads are employed. Thread-based networking is relatively inefficient and very difficult to use. Furthermore, users of Node are free from worries of dead-locking the process, since there are no locks. Almost no function in Node directly performs I/O, so the process never blocks. Because nothing blocks, scalable systems are very reasonable to develop in Node.