---
layout: post
title: "Javascript Basics"
excerpt_separator: <!--more-->
---
JavaScript was initially created to **“make webpages alive”**.
The programs in this language are called scripts. They can be written right in the HTML and execute automatically as the page loads.
<!--more-->
Scripts are provided and executed as a plain text. They don’t need a special preparation or a compilation to run.
In this aspect, JavaScript is very different from another language called Java.

At present, JavaScript can execute not only in the browser, but also on the server, or actually on any device where there exists a special program called the JavaScript engine.

<blockquote class="blockquote">
{% highlight html%}
<!DOCTYPE html>
<html>
<body>

<h2>My First JavaScript</h2>

<button type="button" onclick="document.getElementById('demo').innerHTML = Date()">
    Click me to display Date and Time.
</button>

<p id="demo"></p>

</body>
</html>
{% endhighlight %}
</blockquote>

The browser has an embedded engine, sometimes it’s also called a **“JavaScript virtual machine”**.

JavaScript is one of the 3 languages all web developers must learn:

   1. **HTML** to define the content of web pages
   2. **CSS** to specify the layout of web pages
   3. **JavaScript** to program the behavior of web pages

Web pages are not the only place where JavaScript is used. Many desktop and server programs use JavaScript. Node.js is the best known. Some databases, like MongoDB and CouchDB, also use JavaScript as their programming language.

Different engines have different **“codenames”**, for example:

+ **V8 – in Chrome and Opera.**
+ **SpiderMonkey – in Firefox.**
+ **There are other codenames like “Trident”, “Chakra” for different versions of IE, “ChakraCore” for Microsoft Edge, “Nitro” and “SquirrelFish” for Safari etc.**

The terms above are good to remember, because they are used in developer articles on the internet. We’ll use them too. For instance, if “a feature X is supported by V8”, then it probably works in Chrome and Opera.

