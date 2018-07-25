# Request-Response Cycle, Web Servers & Web Frameworks

1. 5 min Intro & Objectives
1. 10 min Think, Pair Share
1. 20 min TT Separation of Concerns, Request-Reponse Cycle, MVC
1. 30 min CoC & MVC Challenges
1. 10 min Break
1. 10 min TT and demo of client technologies: HTML, CSS, JS
1. 5 min demo of Emmet package
1. 30 min HTML/CSS/JS Challenges
1. Wrap up

## Objectives

1. Identify and describe the Request-Response Cycle
1. Identify and describe the Model View Controller convention
1. Define **Convention over Configuration**
1. Define the **Separation of Concerns**

## Initial Exercise

**Think, Pair, Share** - Think up 5 conventions that exist in ordinary day-to-day life. Share your list with a partner. Why do we follow these conventions? What are alternatives? What if we didn't follow them what would happen?

## Overview

### Why?

Why do we have architectures like MVC? The answer is because they are conventions that make coding easier.

We could write all the code together in one file without spaces or new lines, the computer does not care, but that would be very hard for humans to work on.

Instead, we break up code into by **Concern** or area of functionality in order to simplify the process of writing web servers. This principle is called the **Separation of Concerns**. Basically "keep code together that do the same thing".

We want to always look for conventions to use, and be careful when we depart from conventions. We want to put **Convention over Configuration** - so that our code is standardized and recognizable by other developers.

## Two Conventions: MVC & The Request-Reponse Cycle

Code is instructions for a computer.

The web is a network of computers with two types of nodes in the network. Clients, that request and display data, and servers that request and respond with data (but do not display it).

Clients and servers request data and servers respond to requests to data using one process called the **Request-Response Cycle**. Examples of clients are browsers, apps, and IoT devices like the Amazon Echo. Examples of servers are any website or web service on the internet.

![Request-Response](assets/req-res.gif)

Servers, who request and respond to data, have various ways that they are organized, but we will be learning the most common pattern called **Model View Controller** or **MVC**.

![MVC](assets/mvc-simple.png)

* **Controllers** - Where code that defines routes, requests, and responses logic goes.
* **Views** - Where code goes that users see and interact with (HTML).
* **Model** - Where code goes that interfaces with a database.

Here is a diagram of an integrated look at the Request-Response Cycle and MVC:

![mvc req res](assets/mvc-req-res.jpeg)

## Resources

1. [Request Response Cycle Code Academy](https://www.codecademy.com/articles/request-response-cycle-static)
1. [What is Programming in MVC](https://www.youtube.com/watch?v=1IsL6g2ixak)
1. [This is what Node.js is used for in 2017 - Survey Results](https://blog.risingstack.com/what-is-node-js-used-for-2017-survey/)

## Baseline Challenges

**CoC & MVC**
1. Work with a partner to come up with an analogy for the request response cycle and MVC and share it on slack.
1. Draw your own original picture of the Request Response Cycle and MVC.

**HTML/CSS/JS**
1. Install [Emmet](https://emmet.io/) or another HTML snippet package to your text editor.
1. Prerequisites - if you have not completed all the prerequisites, take the time to do that now and before next class. (Intro to HTML/CSS/JS)
  1. [HTML Semantics (videos)](https://www.youtube.com/playlist?list=PLWjCJDeWfDdc0Sp_DinOWnodw3KnWCwc1)
  1. [Dash Tutorial](https://dash.generalassemb.ly/)
  1. [CSS Cross-Country (Tutorial)](https://www.codeschool.com/courses/css-cross-country)
  1. [Learn CSS in 12 Min (video)](https://www.youtube.com/watch?v=0afZj1G0BIE)
  1. [Code Academy JavaScript lesson (tutorial)](https://www.codecademy.com/learn/javascript)
