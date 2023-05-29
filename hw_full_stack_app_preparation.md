### Questions

1. What is responsible for defining the routes of the `games` resource?
- In server.js there is a variable called gamesCollection that accesses the 'games' collection. Then there is another variable called gamesRouter which creates a router using gamesCollection. 


2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
- Things that are relevant to the user experience are contained in client and backend things are in server folder. 


3. What are the the responsibilities of server.js?
- server.js connects to a mongoDB database, makes a server with express and creates a router for the games


4. What are the responsibilities of the `gamesRouter`?
- gamesRouter allows us to have restful routes for our application. 


5. What process does the the client (front-end) use to communicate with the server?
-  

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

## Extension

Why do we need to use [`ObjectId`](https://mongodb.github.io/node-mongodb-native/api-bson-generated/objectid.html) from the MongoDB driver?

Add to your diagram the dataflow for removing a game.
