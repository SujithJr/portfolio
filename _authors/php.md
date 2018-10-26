---
title: PHP
name: php
excerpt_separator: <!--more-->
permalink: php
layout: default
---
<img src="/assets/images/php.png" class="c-image">
**PHP**, which stands for **"PHP: Hypertext Preprocessor"** is a widely-used Open Source general-purpose scripting language that is especially suited for web development and can be embedded into HTML. 
<!--more-->
Its syntax draws upon C, Java, and Perl, and is easy to learn. The main goal of the language is to allow web developers to write dynamically generated web pages quickly, but you can do much more with PHP. 

It is possible to use the **```header()```** function to send an *"Authentication Required"* message to the client browser causing it to pop up a Username/Password input window. Once the user has filled in a username and a password, the URL containing the PHP script will be called again with the predefined variables **```PHP_AUTH_USER```**, **```PHP_AUTH_PW```**, and **```AUTH_TYPE```** set to the user name, password and authentication type respectively. These predefined variables are found in the **```$_SERVER```** array. Both "Basic" and "Digest" (since PHP 5.1.0) authentication methods are supported. See the **```header()```** function for more information. 