# What is web socket? 

Client-Server - web-client-socket and web-server-socket, internet connects those two web sockets. Internet connection is Full-Duplex, means data can flow in both direction. Also it's reliable (niezawodny). So socket is just an end connection. So there is Server-Socket and Client-Socket. One connection needs two sockets.

# Web Browsers

Basic components of web browser:
- user interface, buttons etc.
- browser engine
- rendering engine, taking html, css, js and putting something on the screen
- networking, uses HTTP, requests, responses, resolve DNS's
- javascript interpreter
- UI back-end - stuff that draw stuff that you want like i want rectangle and you have it... xd
- data persistance, cookies, search-history and all other data


Rendering engine includes and do stuff like:


> Resource gathering - web uses network to get resources, HTML, CSS, Pictures... 

> Parse HTML & Create DOM Tree - (DOM - document object tree) DOM is very flexible, if you fotget a tag it's still gonna work, so basically this point refers to taking resources from point above and create a tree from that. 

> Create Render Tree From DOM Tree - now take CSS from resources and apply that to DOM tree (HTML files)

> Layout - position all elements

> Painting - send to UI back-end and display onto screen, draw stuff

> Additional: 
e.g. You have DOM-tree and there is a tag that is hidden. If you hide something then Render-Tree-part doesn't gonna need to render HTML's tag that is hidden. 


# HTTP Overview

- follows client-server model
- stateless which means every transaction is independent is not related to others. Fliping a coin is a stateless example. BUT web application still provide you state: session & cookies mechanisms
- it's application layer which means it on top of TCP/IP layer. In most cases uses TCP. 
- client-actions - GET / POST / PUT / DELETE 
- response status codes
- headers - bit of information that you send with response / request. Cool header is cache-control determines how those resurces are cached. 

# Sessions & Cookies

Let's say we go to Cafe-shop everyday. We take caffe every day. Any interaction with Cafe is stateless, we go in, order, take Cafe, done. 

> session -  gives state, they are stored on the server. But sometimes on the client-side. Session can be stored on the client-side. Major thing is that on cline-side is faster. It doesn't have to look up at server, so it's very fast. But mostly it's on server.

> cookies - cookies remembers sessions, it's useful to get session. Client-side. It stores the state 

# Computer Security

Basic words: 

- Authorization vs Authentication

> Authentication is the mechanism whereby systems may securely identify their users. Authentication systems seek to provide answers to the questions:
>> Who is the user? <br>
>> Is the user really who he/she represents himself to be?

> Authorization, by contrast, is the mechanism by which a system determines what level of access a particular (authenticated) user should have to resources controlled by the system. For an example that may or may not be related to a web-based scenario, a database management system might be designed so as to provide certain specified individuals with the ability to retrieve information from a database but not the ability to change data stored in the database, while giving other individuals the ability to change data. Authorization systems provide answers to the questions:

>> Is user X authorized to access resource R?
>> Is user X authorized to perform operation P?
>> Is user X authorized to perform operation P on resource R?

> Asymmetric RSA

> Symmetric AES

> SSL, HTTPS

> PUBLIC KEY

> PRIVATE KEY

> CIPHER


















