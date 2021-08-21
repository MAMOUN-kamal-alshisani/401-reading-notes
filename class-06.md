## Readings: Authentication

### Explain what a “Singleton” is (in Computer Science terms):

***A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.***

### Explain how the Singleton pattern can be used with Node modules, specifically with classes:

***Singleton design pattern restricts the instantiation of a class to a single instance Example: // recreation.js file class Recreation { constructor ( city , park ) { this . city = city ; this . park = park ; } } module . exports = Recreation ; // adventure.js file const Recreation = require ( ' recreation.js ' ); const greenlake = new Recreation ( ' Seattle ' , ' Greenlake ' );***

### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
***npm init***
***npm install express --save***
***Create server.js and paste the following code:***

***const express = require('express');***
***const app = express();***

***app.get('/', (req, res, next) => {
  res.send('Welcome Home');***
***});***

***app.listen(3000);***


## Document the following Vocabulary Terms

### Router Middleware:

***to set a class before we enter the route. components/Navigation.vue changes the font size for the route with the name of router-middleware. nuxt.config.js contains the router property to activate the middleware.***

### Dynamic Module Loading:
***A recent addition to JavaScript modules functionality is dynamic module loading. This allows you to dynamically load modules only when they are needed, rather than having to load everything up front. This has some obvious performance advantages; let's read on and see how it works.***

### Singleton Pattern :
***is a creational design pattern that lets you ensure that a class has only one instance, while providing a global access point to this instance.***

### #CRUD -> REST Method Matches :
***In RESTful style programming, we should use HTTP methods as our building blocks. I'm a little confused though which methods match up to the classic CRUD methods. GET/Read and DELETE/Delete are obvious enough.***

### Mock Testing :
***Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.***
