# URL-Shrtnr
npm init
npm i express mongoose ejs
#install express, mongoose for mongodb, and expressjs

npm i --save-dev nodemon
#nodemon to save all the changes, to automatically make changes to the files 

make change to the package.json:

"scripts": {
    "devStart": "nodemon server.js"
  },

 npm run devStart >>>> To start the npm server


Something about ES:

 "Rejection" is the canonical term for a promise reporting an error. As defined in ES6, a promise is a state machine representation of an asynchronous operation and can be in one of 3 states: "pending", "fulfilled", or "rejected". A pending promise represents an asynchronous operation that's in progress and a fulfilled promise represents an asynchronous operation that's completed successfully. A rejected promise represents an asynchronous operation that failed for some reason. For example, trying to connect to a nonexistent MongoDB instance using the MongoDB driver will give you a promise rejection:


 Create a model:

 const mongoose = require('mongoose')