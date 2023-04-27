# Running Frontend and Backend with npm start and nodemon server.js
In this markdown file, we will discuss how to run frontend and backend servers using npm start and nodemon server.js. This guide assumes that you have already set up a project with a frontend and a backend.

## Prerequisites
Before getting started, you need to make sure that you have the following installed on your computer:

Node.js
npm
nodemon (for the backend)
If you don't have these installed, you can download and install them from the official websites.

## Running the Frontend
To run the frontend, open a terminal window and navigate to the root directory of your frontend project. Then, run the following command:
`npm start fe`
This will start the development server and open a new tab in your default web browser. You should see your frontend application running.

## Running the Backend
To run the backend, open a new terminal window and navigate to the root directory of your backend project. Then, run the following command:
`nodemon server.js`
This will start the server and watch for any changes in the server.js file. If you make any changes to the backend code, nodemon will automatically restart the server.

## Running Both Frontend and Backend
To run both the frontend and backend at the same time, open two terminal windows and navigate to the root directories of your frontend and backend projects, respectively.

### In the first terminal window, run:
`npm start fe`

### In the second terminal window, run:
`nodemon server.js`
This will start both the frontend and backend servers. You can now interact with your application by visiting http://localhost:3000 in your web browser.

# Conclusion
In this markdown file, we discussed how to run frontend and backend servers using npm start and nodemon server.js. By following these steps, you should now be able to start both servers and develop your application with ease.
