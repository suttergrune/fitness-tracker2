# Fitness Tracker

https://fitness-tracker2.herokuapp.com/

This is fully responsive web application for tracking a user's fitness progress. It is connected to a Firebase database (firebase.google.com). A new user can enter his or her fitness information on the "NEW USER" section. Upon pressing submit, a simple "account" is created and the information is stored in the database, along with the current date. If a user wishes to check their fitness progress at a later date, they can simply enter their username and weight in the "RETURNING USER" section. Upon pressing submit, their progress is displayed in terms of the last time they logged their weight, along with their other account information. And of course, their account information is updated in the database.

NOTE: This is not a PHP application. The "index.html" was changed to "index.php" merely to allow for simple deployment from Heroku.com, without the need for any additional packages or dependencies. However, the original version of this application was indeed a PHP application that used a MySQL database. 
