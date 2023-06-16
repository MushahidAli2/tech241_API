

## What are APIs?

APIs (Application Programming Interfaces) are a set of rules and protocols that allow different software applications to communicate with each other. They enable applications to request and exchange data, access functionalities, and integrate with external systems.



## REST API

A REST (Representational State Transfer) API is a widely used architectural style for designing web APIs. It follows a set of principles that make APIs simple, scalable, and stateless.

### Key Features of REST APIs

- **Resources**: REST APIs treat everything as a resource. Resources can be users, products, or any other entities that an application exposes.

- **Uniform Interface**: REST APIs have a uniform interface that uses HTTP methods and URLs to interact with resources.

### HTTP

HTTP (Hypertext Transfer Protocol) is the foundation of communication on the World Wide Web. It defines the format of messages exchanged between clients and servers.

- **HTTP**: Hypertext Transfer Protocol
- **HTTPS**: HTTP Secure, which adds a layer of encryption to protect data during transmission.

### HTTP Request Structure



HTTP requests consist of:
- **Method**: The HTTP verb that defines the action to be performed on the resource (e.g., GET, POST, PUT, PATCH, DELETE).
- **URL**: The endpoint that identifies the resource being accessed.
- **Headers**: Additional information about the request.
- **Body**: Optional data sent with POST, PUT, PATCH requests to create or update a resource.

### HTTP Response Structure



HTTP responses consist of:
- **Status Code**: A three-digit code indicating the status of the request (e.g., 200 OK, 404 Not Found).
- **Headers**: Additional information about the response.
- **Body**: The actual response data, such as HTML, JSON, or XML.

### HTTP Verbs (Methods)

There are five primary HTTP verbs or methods:

- **GET**: Retrieves data from a resource.
- **POST**: Sends data to create a new resource.
- **PUT**: Updates an existing resource with new data.
- **PATCH**: Partially updates an existing resource.
- **DELETE**: Deletes a resource.

## Statelessness

REST APIs are stateless, meaning that the server does not store any client information between requests. Each request from the client contains all the necessary data for the server to process it.

## Caching

Caching is a mechanism that stores a copy of a response to serve future requests faster. It reduces the load on the server and improves performance by retrieving data from a cache rather than making a new request to the server.

---