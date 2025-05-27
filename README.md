# CosmicDevourer
This project was created for the 2024 iteration of Hack@Brown in February. It reflects an Agario-based single-player 
game that involves eating smaller planets to become larger and larger before ultimately devouring the black hole to win. 

## Class Descriptions
* **main.lua** - Deals with general functionality of the game, including planet generation & randomization, setting general gravitational 
physics w/ blackhole, updating the game based on planetary collisions, creating the game backdrop/background, and changing game-states 
to either win or lose depending on player outcomes

* **conf.lua** - Sets general window configurations

* **ball.lua**  - Also known as the "player" class, this class deals with player movement and gravitational interactions

* **object.lua** - Reflects the planet objects randomly generated throughout the game. The class deals with their random generation (both in terms of size, location, and color) as well as its respective gravity physics 

* **stars.lua** - Reflects the randomly generated star objects created for the game background

* **vector.lua** - Deals with underlying gravitational physics of planets 
