# API Design Best Practices

## What does REST stand for?

Roy Fielding proposed Representational State Transfer

## REST APIs are designed around a ____.

resources, which are any kind of object, data, or service that can be accessed by the client.

## What is an identifer of a resource? Give an example.

which is a URI that uniquely identifies that resource

For example, the URI for a particular customer order might be:
```
https://adventure-works.com/orders/1
```

## What are the most common HTTP verbs?

For REST APIs built on HTTP, the uniform interface includes using standard HTTP verbs to perform operations on resources. 


## What should the URIs be based on?

 URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

 ## Give an example of a good URI.

For example, /customers is the path to the customers collection, and /customers/5 is the path to the customer with ID equal to 5

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

web APIs that expose a large number of small resources.

it is bad

## What status code does a successful GET request return?

typically returns HTTP status code 200

## What status code does an unsuccessful GET request return?


 return 404 (Not Found).

## What status code does a successful POST request return? 
 it returns HTTP status code 201

## What status code does a successful DELETE request return?


HTTP status code 204
