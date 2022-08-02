# Exercise : server

This project is the _server_ part of an exercise, made for front-end testing purpose.  
It offers endpoints for users, along with possible companies and roles a user can have / work to.

# Install
As this is a regular npm project, the only thing to do is `npm install`.  
(Please make sure you have a fairly recent version of node and npm installed). 

# Run
This project provides a simple `npm start` command in order to run in localhost:3000.
In particular, it offers : 

 * `http://localhost:3000/users` returning a list of 100 users
 * `http://localhost:3000/companies` returning a list of companies. Please note a company can recursively handle sub-companies.
 *  `http://localhost:3000/roles` returning a list of available roles.

# Dependencies & tools,

Many thanks to : 
* [json-server](https://github.com/typicode/json-server) for providing such a good way to create fake CRUD APIs
* [json-generate](https://next.json-generator.com/) for providing such a great JSON generator