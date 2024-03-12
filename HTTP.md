# HTTP Basics

HTTP stands for Hyper Text Transfer Protocol. It allows the communication between different systems on the internet. 

## HTTP and OSI Model

HTTP is a protocol of transmission layer of OSI Model, which means it produces data that must be transmitted over the network. It is responsible for directly providing services to user applications, rather than managing low-level details of network communication. Although TCP/IP is used nowadays instead of the OSI model, the concept of the application layer remains the same, which means HTTP also operates at the highest layer of TCP/IP stack.

## HTTP Overview

HTTP is responsible for defining how web browsers (client applications) request web resources from web servers and how web servers respond to those requests. It specifies the format of the requests and responses exchanged between clients and servers. The communication between the client and the server is done by requests and responses.

## HTTP Methods

HTTP methods – or HTTP verbs – are the actions that can be performed on resources identified by a URL. These methods include:

1. GET: request data
2. POST: submit data
3. PUT: update or replace data
4. DELETE: delete data
5. PATCH: apply partial modifications
6. HEAD: like GET but only requests the header from the URL
7. OPTIONS: used to request information about the communication options available
8. TRACE: used to echo the received request back to the client

## HTTP Request

Each HTTP request mode on the internet carries with it a series of encoded data that carries different types of information including:

- HTTP Version type
- A URL
- An HTTP method – action which the HTTP request expects, for example, GET or PUT.
- HTTP request headers – these headers communicate core information such as what browser the client is using and what data is being requested, this data is stored in a key-value pair format.
- HTTP body (optional) – contains any information to be submitted to the web server.

## HTTP Response

HTTP response: the response provided by the server to an HTTP request. It contains:

- An HTTP Status code - 3-digit codes to check if the HTTP request was successful.
- HTTP response headers – meta data
- HTTP body (optional) – the requested data from GET.

# Network Socket

A network socket is the endpoint of communication between two machines over a network. An HTTP socket refers to a network socket that is used for communicating via the HTTP protocol.