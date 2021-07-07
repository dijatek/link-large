# Getting started

## Installation
* Create Repo with Readme and .gitignore
* Clone Repo
* Get your docs started in Readme
* Copy project two starter template
* Create docs folder for extended instructions, references and code documentation
* __Authentication using Passport__
  * Use the [Passport example](https://github.com/coding-boot-camp/FullStack-Lesson-Plans/tree/master/02-lesson-plans/part-time/15-Week/Supplemental/Sequelize-Passport-Example) and copy the following files into your application structure: `config/middleware/isAuthenticated.js`, `config/passport.js`, `models/user.js`, `public/js/login.js`, `public/js/members.js`, `public/js/signup.js`
    * Merge route files (api and htm) by adding the passport routes to the application routes
    * Remember to require `var passport = require("../config/passport");
    * Merge server.js files and change the session secret to a .env variable and generate it randomly`
  * Copy `public/login.html`, `public/members.html` and `signup.html` into the views directory and update their contents and file extension to be handlebars files
    * Update the routes to return a render instead of sendFile for the Passport routes
      * Move the catchall html route to the bottom of the route list
  * Create `.env` file in the root directory, add the SESSION_SECRET and NODE_ENV to it then require it using the dot-env npm
  * `npm i passport`
  * `npm i express-session`
  * `npm i passport-local`
  * `npm i bcrypt-nodejs`

## Local/Development Setup
* Make sure you have a mysql database `link-large` on your local database server
* Ensure configuration settings in your database [configuration file](../config/config.json) `/config/config.json` match your local settings.
* `npm i` from the root directory of your project
* `npm start` to run the application

## Deploying to Heroku

