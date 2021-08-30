# Readings: Message Queues

## ``What does it mean that web sockets are bidirectional? Why is this useful?``
***WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time***
***enables interaction between a web browser (or other client application) and a web server with lower overhead than half-duplex ****

## ``Does socket.io use HTTP? Why?``
***Even when websockets can be used, the initial connection setup it done over HTTP. Also, a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js .***

## ``What happens when a client emits an event?``
***will run the event in client side that was listening to the event***

## ``What happens when a server emits an event?``
***will run the event in whole server that was listening to the event***

## ``What happens if a client “misses” an event?``
***If a client missed an event it is known as an unhandled message and is ignored as if there were no event handler for the event. How can we mitigate this? We should always have handlers installed for all events, and determine within those handlers whether the event should be responded to***


## Term

### Socket
***A socket is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. An endpoint is a combination of an IP address and a port number***

### Web Socket
***is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server. With this API, you can send messages to a server and receive event-driven responses without having to poll the server for a reply.***

### Socket.io
***Socket.IO is a JavaScript library for real-time web applications. It enables real-time, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for node.js. Both components have an identical API.***

### Client
 ***person or group that uses the professional advice or services of a lawyer, accountant, advertising agency, architect, etc. a person who is receiving the benefits,***
 
### Server
***A server is a computer or system that provides resources, data, services, or programs to other computers, known as clients, over a network. In theory, whenever computers share resources with client machines they are considered servers.***

### OSI Model
***The Open Systems Interconnection model ( OSI model) is a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology. Its goal is the interoperability of diverse communication systems with standard communication ...***

### TCP Model
***The TCP/IP model is a part of the Internet Protocol Suite. This model acts as a communication protocol for computer networks and connects hosts on the Internet. It is a concise version of the OSI Model and comprises four layers in its structure.***

### TCP
***The Transmission Control Protocol (TCP) is a transport protocol that is used on top of IP to ensure reliable transmission of packets. TCP includes mechanisms to solve many of the problems that arise from packet-based messaging, such as lost packets, out of order packets, duplicate packets, and corrupted packets.***

### UDP
***? The User Datagram Protocol, or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups. It speeds up communications by not formally establishing a connection before data is transferred.***

### Packets
***a packet is a small segment of a larger message. Data sent over computer networks*, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them.***
