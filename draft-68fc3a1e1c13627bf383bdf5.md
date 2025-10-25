---
title: "Client-Server Architecture for Beginners"
slug: client-server-architecture-for-beginners
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ukzHlkoz1IE/upload/77d73afaed53fbb084a3a467a1a4ab53.jpeg

---

Have you ever thought when we go to any website or youtube , instagram or any other app and we click on some icon or on somewhere on the page how things just suddenly appear in front of our eye

Are they stored in our system or in a very big computer in somewhere in world or there is some software engineer who keep looking us and does some sort of magic when we use our websites …lol just kidding

the core thing behind this is client server architecture/model

So now you might have some questions in your mind like…

* **How do we Interact with Computer Applications ?**
    

* **What is Client** ?
    

* **What is Server ?**
    

* **Is there any medium for this or everything happens by magic!**
    

Don’t worry ,we are going to learn each and everything from scratch

### Interaction between User and computer:

I think you have got the idea till now for this,

whole interaction between user and computer is done by a model or architecture which is based on some protocol(rules) called client server model/architecture .

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1761360941898/26a07a2b-cadd-4f18-ab78-750d9eeaf07a.png align="center")

We can break interaction in 3 stages:

* **Input Stage:** The user gives input (typing, clicking, tapping).
    
* **Processing Stage:** The client software (like a browser or app) turns this into a **network request** using internet protocols.
    
* **Output Stage:** The server processes the request, sends back a response, and the client displays it to the user.
    

Example flow:

User ⇒Browser ⇒Internet ⇒Server ⇒Response ⇒ Browser ⇒User

## Client:

Client is someone who requests some piece of information ,file or data and client operations are usually performed on user’s device

Let’s understand this by a real life analogy-

Think of a restaurant menu we are holding . We can read it ,and give orders and eat whatever we want without entering kitchen.

**Examples of Client side operations-**

* Animations and Transitions
    
* Form Validations(checking user input in browser before data sent in server)
    
* Executing some scripts without requiring server side
    

## Server:

Server is something that sits on the other end and gives us that piece of info back which is requested by client side .

This operation is usually done by a big system usually located far away from client (client and server sometimes may also be on same device) .

Let’s understand this too by a real life analogy-

The kitchen in restaurant ,in which we had given our order that kitchen is server side which prepare our food and send it.

(Notice that raw material for food was already available in kitchen(server) ,it was just processed there to make it usable for client)

**Examples of Server side operations-**

Remember We discussed about a medium ?

Let’s now understand about that medium .

## Network:

A network is simply a connection between client and server which acts like a bridge between them that transfers files, docs , and other type of data between them

Let’s understand its by a analogy

Imagine you (the client) call your favorite pizza place (the server).The **telephone line** that connects your call is the **network.**

Without it, your order (request) would never reach the restaurant, and your pizza (response) would never reach you.

you must have listened some type of networks in school days like **LAN,WAN,WLAN,MAN** ,if not then don’t worry we will discuss about these things in detail in upcoming articles

Now lets understand about the Protocols(rules) on which our Client Server Architecture works

## Protocols:

A **protocol** is like a **set of rules** or **a language** that defines *how* two devices (client and server) should communicate over a network.

Just like we humans need a language to communicate with other humans ,in same manner computers need some protocols that data start making sense while communicating

There are multiple type of protocols like HTTP,HTTPS,FTP,TCP/IP etc on which our whole architecture works.

So basically -

| **Component** | **Role** |
| --- | --- |
| Client | Send requests |
| Server | Processes and responds |
| Network | Connects them |
| Protocols | Defines how they talk |

### Advantage 0f Client Server Architecture:

* Central Resource Management
    
* Scalability
    
* Flexibility of reach
    

### Disadvantage of Client Server Architecture:

* Single Point of Failure
    
* Network Congestion
    
* Security Risks
    

| **Category** | **Term / Concept** | **Description** | **Example / Analogy** |
| --- | --- | --- | --- |
| **Architecture** | **Client** | A device or application that requests data or services from a server. | Your web browser or mobile app. |
| **Architecture** | **Server** | A powerful computer that stores data and provides services to clients. | A restaurant kitchen preparing your order. |
| **Architecture** | **Client-Server Model** | A communication system where clients send requests and servers respond. | Ordering food online — you request, restaurant delivers. |
| **Network Type** | **LAN (Local Area Network)** | Connects computers within a small area (like a home or school). | Wi-Fi at your home. |
| **Network Type** | **WAN (Wide Area Network)** | Connects computers over large distances (like cities or countries). | The Internet itself. |
| **Network Type** | **MAN (Metropolitan Area Network)** | Covers a larger area than LAN but smaller than WAN. | A city-wide university network. |
| **Protocol** | **HTTP / HTTPS** | Protocol for transferring web pages between client and server. | Opening a website in your browser. |
| **Protocol** | **TCP/IP** | Ensures reliable communication and data delivery over the internet. | Like postal tracking — makes sure your data reaches safely. |
| **Protocol** | **DNS** | Translates website names into IP addresses that computers understand. | Like a phonebook for websites. |
| **Protocol** | **FTP** | Used for transferring files between computers over a network. | Uploading files to a website. |
| **Protocol** | **SMTP / POP3 / IMAP** | Email sending and receiving protocols. | Sending/receiving emails via Gmail or Outlook. |
| **Interaction** | **User ↔ Computer** | User gives input → client sends request → server processes → response shown. | Typing a search on Google and seeing results instantly. |

Now you might be wandering with some new terms in this article like HTTP,HTTPS,FTP,TCP/IP,DNS and some other other terminology which you have interacted with first time ,don’t worry in upcoming articles each and every things will be covered separately one by one

Till then stay tuned and keep exploring and learning

> "Anyone who stops learning is old, whether at twenty or eighty. Anyone who keeps learning stays young." — **Henry Ford**