## EXECUTIVE SUMMARY

**Objective**

SafeMOVE is an tool designed to provide perspective home buyers a simple app to help them find the most home for their money in the safest neighborhooD in Orange County.
Using FBI crime statistics and various real estate data SafeMOVE makes moving safe! 

#### *Check it out on Heroku* : https://nameless-badlands-19621.herokuapp.com/


## Technologies used:
* JavaScript
* Node.js
* Express
* Sequelize
* Handlebars
* Bootstrap
* Twilio

## Instructions:

### To run locally:

* Install yarn https://yarnpkg.com/en/docs/install or npm https://www.npmjs.com/get-npm?utm_source=house&utm_medium=homepage&utm_campaign=free%20orgs&utm_term=Install%20npm


* Change configurations in app/config/config.json or set up you environment variables for DataBase password and UserName 

* Run schema.sql simply to create the schema in mysql workbench/command line.  Sequelize will take care of creating tables based on models created in server/models folder.
* Run ```yarn start``` 
