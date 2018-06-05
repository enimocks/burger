# :hamburger: Eat-Da-Burger
This project creates a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. Following the MVC design pattern, using Node and MySQL to query and route data in the app, and Handlebars to generate HTML -- this app lets users enter the names of burgers they'd like to eat.

##
View This Project
This project uses both front-end and back-end technologies, and is hosted for viewing on Heroku. You can visit the project by clicking here: [https://limitless-temple-52001.herokuapp.com/](https://limitless-temple-52001.herokuapp.com/).

## Functionality
This is a full-stack application, that allows you to add your own custom burger (or anything really!) to a list of things to-be-devoured. From that list, you can then click the "Devour" button to move the burger to the devoured section. Since it uses Bootstrap for styling -- it is fully mobile responsive.

It uses 3 of the 4 CRUD operations in MySQL (and the analogous Express routing methods):
* CREATE - to add a new burger to the list (POST)
* READ - to read all existing (devoured or otherwise) burgers from MySQL to the page via Handlebars on the back end (GET)
* UPDATE - to update a burger's status from "Ready to Eat" to "Already Eaten" (PUT)

### Technologies Used
* Bootstrap
* HTML5/CSS3
* MySQL
* JavaScript
* JQuery
* Node.js
* Express.js
* Handlebars.js
* Custom ORM

#### Screenshot
![Screenshot](/public/assets/img/burger-screenshot.png)
