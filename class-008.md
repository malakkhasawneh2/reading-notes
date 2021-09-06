## What is REST?

In 2000, Roy Fielding proposed Representational State Transfer (REST) as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.

A primary advantage of REST over HTTP is that it uses open standards, and does not bind the implementation of the API or the client applications to any specific implementation. For example, a REST web service could be written in ASP.NET, and client applications can use any language or toolset that can generate HTTP requests and parse HTTP responses.
## REST APIs are designed around a ?

A RESTful API is an architectural style for an application program interface that uses HTTP requests to access.

## What is an identifer of a resource? Give an example.

The target of an HTTP request is called a “resource”, whose nature isn’t defined further; it can be a document, a photo, or anything else. Each resource is identified by a Uniform Resource Identifier (URI) used throughout HTTP for identifying resources.
## What are the most common HTTP verbs?

 GET, POST, PUT, PATCH, and DELETE.

## What should the URIs be based on?

 based on nouns
 
 ## Give an example of a good URI.


https://adventure-works.com/orders // Good


## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource


they are considered poor quality  because requiring multiple network calls will slow down an application

## What status code does a successful GET request return?**

      2xx Successful : 200

## What status code does an unsuccessful GET request return?**

      400 

## What status code does a successful POST request return?**

      200 - 201


## What status code does a successful DELETE request return?**

      HTTP response code 200 (OK)
