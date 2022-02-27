# Budget Tracker - Challenge #19 in the U of MN Bootcamp

## Built With
* Express.js
* Mongoose
* MongoDB
* IndexedDB
* Service Workers

## Description
This is an update to an existing Budget Tracker blog, adding IndexDB and a service worker to provide offline functionality to the app.

## Table of Contents
* [Installation](#installation)
* [Acceptance Criteria](#acceptance-criteria)
* [Heroku Link](#heroku-link)
* [Screenshot of the Application](#screenshot-of-the-application)
* [Git Repository](#git-repository)
* [How this was accomplished](#how-this-was-accomplished)

## Installation
* npm init -y
* npm install 


## Acceptance Criteria
GIVEN a budget tracker without an internet connection
* WHEN the user inputs an expense or deposit
  * THEN they will receive a notification that they have added an expense or deposit  
* WHEN the user reestablishes an internet connection
  * THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

## Heroku Link
https://shielded-sierra-33702.herokuapp.com/

## Screenshot of the Application
![image](https://user-images.githubusercontent.com/90292697/155900458-b735eb33-1008-4a67-92d7-ba56e18e6346.png)

## Git Repository![Uploading Screenshot (63).png…]()
https://github.com/mbahl1670/ch19-budgetTracker-mjb

## How this was accomplished
* Added indexDB to the app
* Added a service worker to the app
* Deployed the app to Heroku through Mongo Atlas site
