# Online-Offline-Tracker
Goal: To make a balance tracker that allows offline use and will update the balance once its online.<br>
This project has the following abilites:<br>
- Able to *add* funds to balance as well as *subtract* from the balance, i.e. deposit and withdraw
- Able to display balance activities as a graph
- When the user *does not* have internet connection, the tracker will store all user's inputs and send them to the server once the user is connected to the internet again

<br>

This project contains the following files:
- models/transactions.js: contains data structure for the schema of the database
- public folder: contains client facing *HTML*, *JavaScript* and *CSS* files
- public/db.js: contains codes for creating and interacting with the IndexedDB built into Google Chrome
- api.js: contains endpoints for API call to interact with the database using 
- package.json: contains basic info of the app and all packages used in this project
- server.js: uses **express.js** to serve contents with the *public* folder as well as hosting routes for API calls

<br>

This project was made using: **HTML5**, **JavaScript**, **CSS**, **NodeJS**, **ExpressJS**, **Mongoose**, **MongoDB** and **IndexedDB**.<br>
This project is currently hosted on Heroku with MongoDB Atlas: https://shielded-garden-71901.herokuapp.com/<br>

## The Tracker
