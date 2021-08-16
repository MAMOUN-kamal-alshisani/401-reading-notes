# Readings: Express REST API


## Name 3 real world use cases where you’d want to change the request with custom

1. ***handling errors***
2. ***requesting query and params***
3. ***changing the request and response***

## True or false: The route handler is middleware?
***False***

## In what ways can a middleware function end the process and send data to the browser?
***next()***

## At what point in the request lifecycle can you “inject” middleware?
***After recieving the request.****

## What can cause express to error with “Request headers sent twice, cannot start a second response"?

***when treating an async response inside an express route as a synchronous response and they end up sending data twice.***


## Document the following Vocabulary Terms

***Middleware: Middleware are different types of functions that are invoked by the Express.js routing layer before the final request handler. As the name specified, Middleware appears in the middle between an initial request and final intended route. In stack, middleware functions are always invoked in the order in which they are added.***

***Response Object: e express.js request object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on. The following table specifies some of the properties associated with request object.***

***Application Middleware: Middleware is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.***

***Routing Middleware: middleware functions can perform the following tasks:Execute any code,Make changes to the request and the response objects.***

***Test Driven Development:Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed,,***

***Behavioral Testing:Behavioral testing is widely used and accepted as an integral part of toxicological evaluations. The data can be sensitive, specific, and reliable in detecting chemical effects, as well as useful for regulatory decisions and mechanistic evaluations in basic research. Interlaboratory comparisons indicate that data can be reliable and reproducible.***

