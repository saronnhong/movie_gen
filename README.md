# Wat2Watch App
## Overview
Wat2Watch is a full stack application that collects information through surveys and favorited movies, stores and analyzes it in a MySQL database, and gives the user recommendations for movies that they would like.

## Usage
Wat2Watch runs in the browser window and is deployed on Heroku. To start, go to https://wat2watch-p2.herokuapp.com/ and create a new user to log into the application. After the new user is created and logged in, the user will be directed to answer a few questions on a survey. Based on these results, the app will recommend movies for the user to watch. The user is also able to add any movies to their favorites list. Information from the favorites list is stored in a MySql database. The app will analyze the the stored information and recommend more movies to the user when the page is reloaded. The more information the application is able to collect, the more accurate the recommendations will be. 

## Examples
### Images:
![alt text](./public/images/login_ss.png "login")
Screenshot of the Login page

![alt text](./public/images/survey_ss.png "survey")
Screenshot of the Survey page

![alt text](./public/images/wat2watch_ss.png "home")
Screenshot of the Home page

![alt text](./public/images/about_ss.png "about")
Screenshot of the About page



## Technologies
Wat2Watch was created using these technologies
* JavaScipt
* Node.js
* MySql
* API
    * The Movie Database API
* NPM JS Packages
    * Bcrypt
    * Dotenv
    * Express
    * Express Handlebars
    * Express Session
    * Morgan
    * MySQL 2
    * Passport
    * Sequelize
    * Unirest


## GITHUB
[github link](https://github.com/saronnhong/movie_gen)

## DEPLOYED SITE
[heroku link](https://wat2watch-p2.herokuapp.com/)

## TEST ACCOUNT
User: test

Password: test123