# React-test

This project is a test of react features and definitions towards a web application.  
It follows the [tutorial on react page](https://facebook.github.io/react/docs/tutorial.html) to build and show the features

## Setup
1. [Install node + npm](https://nodejs.org/en/download/)

2. Install project dependencies
> npm install

## The server
This project has 2 components: the http server serving content and results for the frontend, and 
 the frontend written in react.

### Running the server
> node server.js  

Check server working at [http://localhost:3000](http://localhost:3000)

### Server content
- "/" serves the static content under "public" folder
- "/api/comments" Gets and posts comment entities in the "database"

### The pseudo database
comments.json acts as the database for the server, and is used to persist comments