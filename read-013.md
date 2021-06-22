# Status Codes Based On REST Methods

## In your own words, describe what each group of status code represents:

100’s = usually tell the client that the header part of the request has been received

200’s = tell the client that its request was accepted

300’s = tell the client that the resource they are requesting isn’t available at the expected location anymore.

400’s = They are all about invalid requests a client sent to a server.

500’s =  Often they indicate problems with overwhelmed servers or unreachable servers behind proxies

## What is a status code 202?

This code tells the client that the request was valid, but its processing will finish sometime in the future. 

## What is a status code 308?

 This tells the client to use another URL to access the resource and not use the current URL anymore.

## What code would you use if an update didn’t return data to a client?

204 No Content 

## What code would you use if a resource used to exist but no longer does?
410 Gone

## What is the ‘Forbidden’ status code?

The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.


# Build A REST API With Node.js, Express, & MongoDB - Quick 

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

because when we deploy our application we are going to use something that is not our localhost

## What is middleware?

is code that runs when the server gets a request but before passed to your routes

## What does app.use(express.json()) do?

accept JOSN as a body instead of a post element

## What does the /:id mean in a route?

means that this is a parameter that we can access by;

## What is the difference beween PUT and PATCH?

PATCH using for update based on what the user passes us.

## How do you make a defalut value in a schema?

just write key with name 'default'

## What does a 500 error status code mean?

it mean that the actual server in had some kind of error caused the actual  transaction

## What is the difference between a status 200 and a status 201?

201 mean successfully create an object by default 
200 mean everything was successful

then that mean 201 more specifics way


