# Burger-app



## Description
This is A Node, Express, Handlebars, and MySQL burger app that lets users input the names of burgers they'd like to eat... and then devour them! Please check out the launched app on Heroku https://pacific-plateau-26858.herokuapp.com/

## Usage 
Using ORM.js, the app has 3 functions. 
The first  selects and reads all entries from the MySQL database and displays them to the DOM using Handlebars.
The second one updates a selected burger by clicking "Devour", which will hit a route in Express to change its "devoured" status in the MySQL database then re-routes the webpage back to the index, where the burger is now in the devoured list (via Handlebars)
the Third function Creates a new burger using the "Add Burger" button, which... * hits a  route in Express to insert a new burger into the MySQL database * re-routes the webpage back to the index, where the burger is now in the ready to be "devoured" list (via Handlebars)


## Demo
![img](/img/first.png)

## Technologies used
![img](https://img.shields.io/badge/JavaScript-used-green)
![img](https://img.shields.io/badge/MySQL-used-blue)
![img](https://img.shields.io/badge/Express-used-orange)

## License

MIT License

Copyright (c) 2020 Paul Fodrovics
