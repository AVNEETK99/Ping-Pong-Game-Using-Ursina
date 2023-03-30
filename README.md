# Ping-Pong-Game-Using-Ursina

Ping pong is a sport that is played by two or four players, using paddles to hit a lightweight ball back and forth over a net that is stretched across a table. The objective of the game is to hit the ball in such a way that the opponent is not able to return it over the net. Points are scored when an opponent is unable to return the ball within the rules of the game. Ping pong is also known as table tennis, and it is a popular recreational activity and competitive sport around the world.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python ping.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The code imports the Ursina game engine library using ```from ursina import *```.
* The ```app = Ursina()``` creates a new instance of the game engine.
* The background color of the window is set to black with ```window.color = color.black```.
* ```camera.orthographic = True``` and ```camera.fov = 1``` set the camera view to orthographic mode and adjust the field of view to 1.
* Two paddles are created using ```Entity``` with specified scale, position, and rotation.
* A floor and ceiling are created using the ```duplicate``` function to copy the floor entity and adjust its position and rotation.
* The ```collision_cooldown``` and ```ball``` entities are created.
* The ```update``` function is called every frame and updates the position and collision of the ball and paddles.
* The ``` input``` function is called when a key is pressed and checks for the 'space' and 't' keys.
* The ```reset``` function is called when 'space' is pressed and resets the game.
* The ```app.run()``` method starts the game and runs the game loop.
