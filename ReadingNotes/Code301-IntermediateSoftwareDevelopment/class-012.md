# CRUD
## 1.in your own words, describe what each group of status code represents:
**100’s** =   tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.
**200’s** = (success codes)They tell the client that its request was accepted
**300’s** =  These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. 
**400’s** = These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc.
**500’s** = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

## 2. What is a status code 202?

this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

## 3.  What is a status code 308?

Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore.

## 4. What code would you use if an update didn’t return data to a client?

204 No Content
## 5. What code would you use if a resource used to exist but no longer does?

 410 gone

## 6. What is the ‘Forbidden’ status code?

 The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
 
 
 ## 2.1: Why do we need to pull our MongoDB database string out of our server and put it into our .env?

When we deploy the server we are going to use anathor URL

## 2.2: What is middleware?

code that run when server gets the request but before it gets passed to the routes.

## 2.3: What does app.use(express.json()) do?

 accept JSON inside a get or post elements

## 2.4: What does the /:id mean in a route?

it's for getting on element in database this is a parameter and give access to whatever they pass after the first slash

## 2.5: What is the difference beween PUT and PATCH?

patch if we want to update based on what  the user passes
put it will update all information to describe it at once

