# Battleship Online

A casual game of battleship to play with a friend.
Both player name and ship locations on the board are randomly generated by the game so that a player can get into the game quickly.

## Demo

* [Live Demo](https://carabus-battleship.herokuapp.com/)

## Video Demo

TBD

## Screenshots

### Start Page

![Start Page](https://raw.githubusercontent.com/carabus/battleship-online/master/screenshots/landing-page.png)

### Game Page

![Game Page](https://raw.githubusercontent.com/carabus/battleship-online/master/screenshots/game-page.png)

## Technologies used

### Front End:

* JavaScript
* jQuery
* HTML5
* CSS3

### Back End:

* Node.js
* Express
* MongoDB
* Mongoose
* Mocha
* Chai, Chai-http
* Socket.io

### Responsive

* The app is responsive and optimized for both desktop and mobile use

## API Documentation

* GET /player - get randomly generated player id
* POST /battleship - create a game in the room for a particular player. Required fields are: playerId, roomId.
* PUT /battleship/:id - make a turn in the game. Required fields are: id, playerId, roomId, moves.

## Nice to have features

* Ability to restart the game with the same opponent without having to re-send the link
* Ability to view the list of games I am currently playing and continue playing it
* High score board

## Attribution

* Battleship icon [by Luke Anthony Firth](https://thenounproject.com/term/battleship/9270/)
* Cool help messages on the start page - [Chardin.js](https://github.com/heelhook/chardin.js)
* Hand drawn ships on the board - [Rough.js](https://github.com/pshihn/rough)