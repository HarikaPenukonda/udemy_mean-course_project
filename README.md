# udemy_mean-course_project
## This is a mean stack project where we use Mongo DB, Express, Angular and NodeJs

## Angular and NodeJS - The Mean Stack Guide

## M - MongoDB 
## E - Express JS
## A - Angular
## N - Node JS


#### Node JS is the language used on the server, Express is a framework for NodeJS that makes working with it easier.

### What is Angular?

 1. It runs on the client-side in the browser
 2. It's a framework building upon javascript or using JS which is used to create "**single page application**"
 3. Render the user interface with dynamic data, update the UI whenever there is new information.
 4. Responsible for handling user input, validating
 5. Communicates with back end services
 6. Provides a "**Mobile-App**" like experience

### What is Node JS?

 1. Server-side, JavaScript Runtime
 2. JavaScript can run on the browser, NodeJS add few things that are useful on the server. Eg : working with files, HTTP requests
 3. It listens to incoming requests and able to send back responses.
 4. Execute server-side logic
 5. Interact with Database and files
 6. An alternate to PHP, Ruby on Rails, java etc.

 **Note:** Theoretically, we can connect to DB from angular, since all the client-side JavaScript is visible to the user, it would be very insecure to connect DB as it will expose all the credentials.

### What is Express?

 1. Express is a NodeJS framework which simplifies server-side code and logic.
 2. Middle-ware based
 3. Includes Routing, view-rendering and more
 4. Different requests to different URLs are handled correctly
 5. Simplifies the usage of Node, Express is for Node what Larval would be for PHP.

### What is MongoDB?

 1. A NoSQL database which stores "Documents" in "collections".
 2. Store Application data
 3. Enforces no data schema or relations
 4. Easily connected to Node / Express
 5. A powerful DB which can easily be integrated into a Node/Express environment.

###  Single Page Application
In an angular application, we have one root html file which is called index.html. we will serve that from our node.This HTML page basically includes some script imports that houses Angular application. 
Angular framework + Our own code --> dynamic re-render

###  why?
By having this pattern, we do not need to reload the page just because the user clicks on a post and want to see the details.

We instead navigate to that page directly because we don't really leave the page, we just remove some element from DOM and add new elements which is handled by Angular Framework.

This allows for instant re-rendering, instant user feedback and makes building highly engaging UI's possible.

## MEAN - THE BIG PICTURE

 - Requests which can be sent without needing to reload the page.
 - JSON data, efficient for encoding.
 - Angular uses TypeScript, a superscript to Javascript
 - A different language that's heavily based on Javascript that does not run on browser and to make it run, we need to compile it.  
