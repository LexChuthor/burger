# burger

Burger is an application with Node.js/Express/MySQL/Handlebars

### Description

This application is a demonstration of a full stack application with HTML/CSS implemented with HTML templating using handlebars.  The backend is implemented using Node.js and express.

The application will start with a few classic burgers already in the database.  The User may enter any burger to add a new burger to the MySQL database.  The user may then "eat" a burger by clicking on the button, or "remake" a burger, which will change the section that the burger is in on the page and change its status within the database.

### Demo

The working application can be found [here](https://blooming-fjord-62134.herokuapp.com/)

### Installation

Clone this repository and navigate to the burger application folder on your computer terminal.  Install the application dependencies with the following command:

```
npm install
```

Upon successful installation, run the server locally
```
node server.js
```

The application will run on port 8080 by default, but you may change the following line in server.js to make it run on whichever port you desire: 
```
3  var PORT = process.env.PORT || 8080;
```