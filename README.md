Intro to Mongoose

## Technologies Used for Note App API:

* Node.js
* Express.js
* Mongoose and MongoDB
* Heroku (in the past)


--------------------------------------------
## How to Install Note App API locally:

* Fork and clone this repository to your machine
* Change into the new directory
* In your IDEs terminal, run npm install:

```
$ npm install

```

* Next, create your own .env file, and add your MongoDB connection string with the variable name MONGO_URI 
```
MONGO_URI=mongodb+srv://YOURDBCLUSTERNAME:<THISISTHEPASSWORD___REMOVE___THE___CARATS>@sei-w0kys.azure.mongodb.net/<THISISTHEDATABASENAME___REMOVE___THE___CARATS>?retryWrites=true

```
* Open another terminal tab, and run nodemon
```
$ nodemon

```


You're all set to run Note App API on your machine. You will see notes on the main page. You can delete these, and create your own either in the JSON file (then reseeding your database with node seeds.js) or using any front end framework. Have fun with it... 