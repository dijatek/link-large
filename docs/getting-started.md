# Getting started

## Installation
- Create Repo with Readme and .gitignore
- Clone Repo
- Get your docs started in Readme
- Copy project two starter template
- Create docs folder for extended instructions, references and code documentation
- __Authentication using Passport__
  - Use the [Passport example](https://github.com/coding-boot-camp/FullStack-Lesson-Plans/tree/master/02-lesson-plans/part-time/15-Week/Supplemental/Sequelize-Passport-Example) and copy the following files into your application structure: `config/middleware/isAuthenticated.js`, `config/passport.js`, `models/user.js`, 
    - Merge route files (api and htm) by adding the passport routes to the application routes
    - Remember to require `var passport = require("../config/passport");
    - Merge server.js files and change the session secret to a .env variable and generate it randomly`
  - Create `.env` file in the root directory, add the SESSION_SECRET and NODE_ENV to it then require it using the dot-env npm

## Local/Development Setup
* Make sure you have a mysql database `link-large` on your local database server
* Ensure configuration settings in your database [configuration file](../config/config.json) `/config/config.json` match your local settings.
* `npm i` from the root directory of your project
* `npm start` to run the application

## Deploying to Heroku

