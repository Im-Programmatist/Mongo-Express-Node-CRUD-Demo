# Mongo-MOngoose-Express-NodeJs Website with CRUD operation and JWT Authentication-

## `Backend`
1. This is the server part of the application and we will create all the stuff related to server in this directory.

2. We will have to make separate node_module folder for backend using initiating the node package. So, using this special package.json we can install all the packages which is only required for server related developement. 

3. We can add Mocha/Tea testing framework that is used to perform tests within our application.It makes sure everything works correctly. 

4. Commands to create Node.js project in Backend folder.
#### `$ npm init` OR `$ npm init -y`
- initiate node in folder and this will create package.json and  package.lock
#### `$ npm install --save-dev babel-cli` 
- Babel is mainly used to compile JavaScript code, which will have backward compatibility.
#### `$ npm i body-parser` 
- Node.js body parsing middleware. Parse incoming request bodies in a middleware before your handlers, available under the req.body property.
#### `$ npm i mongodb` 
- install mongodb package in folder - we will gonna use mongoose for connection between node and mongodb database  
#### `$ npm i mongoose` 
- Object Data Modeling (ODM) library for MongoDB and Node. Mongoose provides a straight-forward, schema-based solution to model your application data.
#### `$ npm i nodemon` 
- Simple monitoring tool, tool that helps develop node. js based applications by automatically restarting the node application when file changes in the directory are detected. 
#### `$ npm i validator`  
- Vaidator is very popular pacge that used to make validation in a easy way for any form. 
#### `$ npm install mocha chai --save-dev`
- Mocha is a relatively fast and straightforward JavaScript test framework hosted on GitHub.
#### `$ npm i hbs`
- Using hbs as the default view engine requires just one line of code in your app setup. This will render .hbs files when res.render is called.
#### `$ npm i jsonwebtoken`
- Using jsonwebtoken we can create token and authenticate user while using API. JWT is used for stateless authentication mechanisms for users and providers, this means maintaining session is on the client-side instead of storing sessions on the server.
#### We will keep on adding packages as per our need

6. Initiate `Git` and create `gitignore file` in root directory so that we can push our frontend and backend code in one respository**

7. Initiate node in root directory using `$ npm init`, this will create package.json for `global` root directory. In global directory we will going to install 2 packages - concurrently and nodemon**

8. Folder Structure as below -
### node_module - created by default using npm init

### src- Source where all working folder place, this directory contains following folders ⬇️

**1. Configs - all database and other configuration detail files here**

**2. Controllers - All the business logic files can create in this controller folder**

**3. Middlewares - Pre or Post operation can perform respectively on request and response using middleware for all kind of routes**

**4. Models - Database schema models come under this folder**

**5. Routes - Route for all kind of  API**

**6. Services - Services for API, all routes method and their query operation files keep in this folder**

**7. Utils - Helper functions or global used files can keep in this folder**

### test - testing framework directory

### views - contains render hbs files if you want to run UI/presentation part using pure node js.

### public - contains images,css files and storage folder like for download(report csv file we need to create it and pass path in api response), 

### index.js - start point of the server application, here we mention express app and routes

### package.json & package-lock.json - package manager create this file, keep record of all the packages used in node project

