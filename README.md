# JokeSearch

#Description:
My Node.js Module that fetches a joke from the web. <br />
This module gets all its jokes randomly by gathering data from: http://tambal.azurewebsites.net/joke/random <br />
current version: 1.0.2 
#Download:
Npm URL:https://www.npmjs.com/package/jokesearch
Console Command: npm install jokesearch

#Ussage:
Example:
```node
var joke = require('jokesearch');
joke.getJoke(function(joke){
   console.log(joke);
});
```

This module was mainly made and is featured in my facebook bot which can be found at https://github.com/Zein-Fakhreddine/FaceBook-Bot.
