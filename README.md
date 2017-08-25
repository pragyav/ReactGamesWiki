Prerequisites:

Create & Update FileStack YOUR_API_KEY in client/src/index.js file.

Update YOUR_MONGO_CONNECTION in server.js file.

Start MongoDB by running Mongod.exe.

Run App:

If you don't have *yarn* installed, go ahead and install it.
From npm:

```
npm install yarn -g
```

Then in the root folder run:

```
yarn
```

Check the package.json for the running scripts.

Start Server : yarn api, listen on port 8080

Start Client : yarn start, listen on port 3000

App Demonstrates:

We first built the backend of the app, an API server with Node.js and Express, connect it to Mongo.db, write the games API and test it with postman.
Then, we built Frontend by wrting React components and serve it with webpack-dev-server. 

Then included Redux state container and Redux-saga to perform asynchronous HTTP requests to our real server. 
Finally, some simple authentication.