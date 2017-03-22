# README
## Description of Project
This is an online version of the game Bananagrams. This supports a game
between multiple players on a Node.js server using Socket.io. The game is
played exactly as the game is played with tiles and there are buttons for each
of the calls that are made during the game ("peel", "split", etc). The words
are checked againts the SOWPODS scrabble word list.

Players start a new game by typing in their name and clicking the "New Game"
button. They are then given a "Game ID" so that others can join their game.

Some of the planned improvements to this project are:
* Better resizing of tiles and game board for mobile interface
* An option to move tiles between locations on the board without returning tile
to hand
* Disallow empty field for "Name" on main screen
* Notification when players drop out in the middle of the game with option to
return

## Contents
* **`bananagram_rules.pdf`**- the rules for the game
* **`Bananagrams`**- contains the files for the project; to run:
1. Start terminal in `Bananagrams` directory
2. Start node server by running the command "node server.js"
3. Go to the URL http://127.0.0.1:3000
4. If this is to be used with multiple players on different computers,
replace all instances of "localhost" in the instructions and the code with the
public ip address of the computer hosting the node server
* **`Screenshots`**- contains images that show each page a user would encounter
throughout the game on both a mobile browser and a desktop browser
---
**Technologies used:** Node.js, Express.js, Socket.io, jQuery, media queries,
responsive web design  
**Estimated Lines of Code:** 1400

![](/Screenshots/Desktop/screenshot1.png)  
Welcome page

![](/Screenshots/Mobile/screenshot1.png)  
Mobile version of the welcome page

![](/Screenshots/Desktop/screenshot2.png)  
Waiting for players to join

![](/Screenshots/Desktop/screenshot4.png)  
The game in progress

![](/screenshots/Desktop/screenshot5.png)  
The winning move