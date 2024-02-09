# Web Development Overview

# Client server model

client, server, communication channel, request, response and resource

me, supermarket, call, what I want to buy, the request, what I want

### Components

- client and server
- communication channel
- request and response
- resource and services

![download.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/c5e9244e-0971-4356-bd22-cca30b1c54ab/download.png)

- The **client–server model** is a [distributed application](https://en.wikipedia.org/wiki/Distributed_application) structure that partitions tasks or workloads between the providers of a resource or service, called [servers](https://en.wikipedia.org/wiki/Server_(computing)), and service requesters, called [clients](https://en.wikipedia.org/wiki/Client_(computing)).[[1]](https://en.wikipedia.org/wiki/Client%E2%80%93server_model#cite_note-1)
- Often clients and servers communicate over a [computer network](https://en.wikipedia.org/wiki/Computer_network) on separate hardware.

---

## **Internet**

**Internet is the communication language**

what if the client and server speak different language… here is the role of protocol

**HTTP** 

- The **Hypertext Transfer Protocol** (HTTP)
- HTTP is an application layer protocol designed to transfer information (like HTML) between networked devices and runs on top of other layers of the network protocol stack.

![images.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/2e686fbb-0f20-44df-84c7-d8e7178b8128/images.png)

**Server has a permanent IP**

1. type the name of website in the browser as a client
2.  the browser build the http request and send it to the server 
3. server generate a http response and send it to the client

---

## Web Application?

- it is a software application that run on a web server (it help to open web application)
- it is run by server side language PHP
- it is a client-side and server-side software

## Front end vs Back end

![0_ArZByYbv7qk7nPEc.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/f8346b70-b45c-4d33-b95e-aa8f61d1b52f/0_ArZByYbv7qk7nPEc.png)

**front ⇒ client , server send files as static files to the client**

 **backend ⇒ server between them API ,code run away from client**

---

## Static Sites

- static web page displays the same information for all users
- only the files you want

Static nightmare ⇒ if we have a million user we want a million page, it is impossible  so the dynamic is the solution.

## Dynamic Sites

Generate content and data based on a specific request URL 

- One page server million user
- Only change the data
    
    ![9a6a35f3d1634154a306b1a67c6b67aa.jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/c410d0ec-7238-4113-a230-583d51206b6d/9a6a35f3d1634154a306b1a67c6b67aa.jpg)
    
    **Dynamic sites Cycle**
    
    - receiving HTTP request for a product
        - the server determine the product id
        - the web server detect that the request is dynamic and forward it to web application to process it
        - fetch the data from database based on the given id
        - build the html page by inserting data
        - sent the template to client
    
    ---
    
    # **Front-End**
    
    ![web_application_with_html_and_steps.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/46435581-0b6c-4f17-b205-f94ded90b29b/web_application_with_html_and_steps.png)
    
    **HTML**
    
    ![download.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/a04bdf7e-0e33-4cdb-a072-b5396e590e14/download.png)
    
    **CSS**
    
    ![download.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/52103a7f-5adc-488f-a77c-61a11c5188dd/download.png)
    
    **JS**
    
    ---
    
    # **Back-End**
    
    **Server Side ⇒ car engine**
    
    - it handle routing
    - handle Authentication
    - handle Authorization
    - connect with database
    
    **PHP**
    
    - PHP it is general-purpose scripting language it is for web development only
    - fast, flexible and pragmatic
    - .php
    - code only on server side don’ t send to the client
    - you can write html inside PHP files ⇒ to create dynamic sites
    
    # Laravel Framework
    
    Laravel is a web application framework with expressive, elegant syntax.
    
    ![What-is-Laravel.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/5dc0fb7b-7603-484b-88e2-27cdef130b8e/What-is-Laravel.png)
    
    Laravel is easy ⇒ easy is dangerous 
    
    # Into The Web Application
    
    ## **Design Pattern**
    
    context, problem and solution.
    
    is a general, [reusable](https://en.wikipedia.org/wiki/Reusability) solution to a commonly occurring problem within a given context in [software design](https://en.wikipedia.org/wiki/Software_design). It is not a finished design that can be transformed directly into [source](https://en.wikipedia.org/wiki/Source_code) or [machine code](https://en.wikipedia.org/wiki/Machine_code). Rather, **it is a description or template for how to solve a problem that can be used in many different situations.** Design patterns are formalized [best practices](https://en.wikipedia.org/wiki/Best_practice) that the programmer can use to solve common problems when designing an application or system.
    
    - **compound Design pattern ⇒ it is a combines two or more patterns into a solution to solve general problem.**
    
    ## **MVC (Model View Controller)**
    
    The king of compound design pattern
    
    - context: building web application
    - problem: separate the functionalities of the web application
    - solution: we will use a certain organization of classes
    
    MVC's the paradigm for factoring your code, into functional segments so your brain does not explode
    
    ![gBfe7.jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/ac853207-49ff-432a-b05a-fcd9ece6ecf9/gBfe7.jpg)
    
    ![model-view-controller-light-blue.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/0717192e-a19e-4175-83d5-cf3be9cd2d1e/model-view-controller-light-blue.png)
    
    # HTTP
    
    every request has many parts like Verb and Path ⇒ what is information you need and how that information is being requested
    
    **PATH ⇒ it is the URL (/task, /task/4)**
    
    VERB ⇒ HOW (GET, POST, DELETE, PUT )
    
    ![7076fb1e-53be-4080-b855-8448a6f4a07a_1199x601.jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/37c312e2-fc82-4ef1-9f21-1bbcd104c62c/7076fb1e-53be-4080-b855-8448a6f4a07a_1199x601.jpg)
    
    What is routing in HTTP?
    
    Routing refers to **how an application's endpoints (URIs) respond to client requests**. For an introduction to routing, see Basic routing. You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests.
    
    ## MVC & Routing
    
    ![Router-MVC-DB.svg.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/82f4328f-1316-499c-976b-272748013a6c/bbdb3178-84ff-4bff-abab-0d72a7aa9b72/Router-MVC-DB.svg.png)
    
    **Router ⇒ handle the request into action to send it to the controller**
    
    ## Resources
    
    Head First Object Oriented Analysis And Design
    
    Head First Design Pattern 2nd edition