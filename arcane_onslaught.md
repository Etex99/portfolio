## Arcane Onslaught

Unity game, autumn 2020
Emma Kemppainen, programmer

### Overview

Arcane Onslaught is a lane-based tower defense game for mobile platforms. It was developed under Oulu Game Lab (OGL) as part of two game development courses supported by Oulu University of Applied Sciences (OAMK). The development team consisted of full-time students including myself. My main role in this project was gameplay programmer.

[Gameplay trailer](https://www.youtube.com/watch?v=7l2r3sZqLxc)

### Takeaway

Unity physics
_Variety of unity physics engine features were used to enable interaction between game objects. Raycast-functions were used to check for obstructions and targets. Built in collision events were also utilized to enable behavior such as projectile hit detection._

Core game loop logic
_The core game loop is broken down to separable game phases in a state-machine structure for good efficiency. It handles updating other core game systems and is responsible for triggering game events like win and loss._

Inheritance
_I used inheritance to promote uniform, predictable and efficient behavior in game objects of the same logical category. Animated and live game objects of the game derive from the same base class to handle effects of the custom game world environment. A good example of this are the elemental status effects like burning._

Unity animation system
_During the project I learned the basics of unity animation system to control the animation playback of enemies, wizards and some other miscellaneous game objects._

Serialization and IO-operations
_For local game data saving I made a simple serializeable class and a binary formatter to produce relatively hard to edit save data._
