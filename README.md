# social-network

# Description
This social network API app is a back-end Node.js application that was created using a NoSQL database. The app does not have a front-end so the user will need to run npm install and test out the routes using Insomnia Core. Users are created, can be updated and deleted. All users have the ability to add thoughts, friends and reactions. The key technologies used are listed below.

# Technologies
JavaScript
Node.js
Express.js
MongoDB
Mongoose.js
Moment.js

# Requirements
When the user enters npm start to invoke the application
the server is started and the Mongoose models are synced to the MongoDB database
The app is built with API GET routes for viewing users and thoughts through Insomnia Core
this data is shows in a formatted JSON
Next, the app also includes POST, PUT and DELETE routes that can create, update and delete users and thoughts in the database
Lastly, the app has POST and DELETE routes to create and delete reactions to thoughts as well as add and remove friends from a user's friend list.
One addition to app was to include a route that removes just one reaction to a thought instead of just having functionality that deletes all reactions
