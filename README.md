# NodeJsDemo

## Overview

This application uses custom authentication to authenticate users locally. The sessions are managed using MongoStore and express-session. 
Also, a Product Quality journey has been demonstrated and the results are saved in MongoDB.
The interactions with MongoDB is performed using mongoose package.

## Required Packages

- express
- express-session
- async
- mongoose@4.6.0
- connect-mongo
- body-parser
- ejs
- babel-register

## Instructions

If you would like to download the code and try it for yourself:

1. Clone the repo: "https://github.com/gsbedi28/NodeJsDemo.git"
2. Install packages: "npm install"
3. Change the database configuration in config/database.js
4. Dump folder contains the collections and databases. Use mongorestore command to get the database to execute the application.
5. Launch: "node server.js"
6. Visit in your browser at: "http://localhost:3000"
