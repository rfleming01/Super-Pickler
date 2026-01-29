 # Super Pickler
**Version: 0.1**
* Game starts on a simple title screen with an exit and start button
* Exit button quits the game
* Start button takes you to the kitchen scene
* Player character in the kitchen and maze scene has top down movement, mapped to WASD
* Pickle launcher rotates on the player, always following the cursor
* Pickle launcher can fire pickles using mouse button
* Customization table can be used with enter during collision, which opens the customization layout
* customization layout has three columns, liquid, vegegtable.
* Each column can be changed using available ingredients, using the up and down arrow buttons on screen
* Ingredients customize the way the pickle launcher operates:
*  Milk: Heals player on kill
*  Honey: Sticks enemies temporaraly
*  Carrot: Peirces through enemies
*  Bell Pepper: explodes into 5 slices on hit
*  Mint: Slows and increases incoming damage
*  Peppercorn: Increases ammo and allows faster shooting
* Dummy in kitchen can be used to test basic weapon capabilities
* Large door can be used to travel to the maze
* Maze scene starts in hall 1, and continues to hall 2, 3, and 4
* Each hall has germs as the enemies, which periodically shoot germ pellets outwards.
* Germs have pathfinding, which is used to avoid the walls, player, and shoot randomly
* There are three main germ enemies, which get bigger and shoot more pellets as they go: small, medium, and big
* Germ boss "Ultra Germ" is in the 4th hall
* Each hall must have all germs defeated before the door opens, allowing the player to move onto the next hall
* When the boss germ is defeated, a undscovered ingredient appears in fron of the big door
* Colliding with the ingredient adds it to your available ingredient pool
* Going through the big door in the boss room takes you back to the kitchen


[Go here to play the working game](https://gd.games/games/bdff90d6-8387-4b8a-8b11-ea21bbd503a3)

*How To Compile*
* Download the current version of [Gdevelop](https://gdevelop.io/download)
* Download and unzip this source folder
* Open SuperPickler.json in gdevelop
