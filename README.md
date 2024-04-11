# CRUD Tutorial with React, Axios, and JSON Server
This repository contains a tutorial on creating a CRUD (Create, Read, Update, Delete) application using React for the frontend, Axios for handling HTTP requests, and JSON Server to simulate a RESTful API. 

![Capture](https://github.com/Yousra-Zahra-LATER/crud-axios-react/assets/138157165/f636c729-77b9-4456-9d51-42f6f2fa44be)

## Prerequisites
Before starting this tutorial, make sure you have the following installed on your system:

`Node.js` and `npm`.\
A code editor such as`Visual Studio Code` 

## Running the Application
1- Clone this repository to your local machine:
2- Open a terminal window.\
3- You will need to install node package manager and json-server globally on your system. You can do this by running the following commands in your terminal: .\
`npm install` and  `npm install -g json-server` 
4- Start the JSON Server to simulate a RESTful API by running the following command:
`json-server --watch db.json --port 3001`
This command will start the JSON Server using the db.json file as the data source and expose it at `http://localhost:3001`.
5- Open another terminal window (keeping the first one running,then Start the React application by running the following command:
 `npm start`
Runs the React app in the development mode.\
The application will be accessible at `http://localhost:3000` 
The page will reload when you make changes.\
You may also see any lint errors in the console.
