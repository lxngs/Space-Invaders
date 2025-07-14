AssetLoader.py - handles loading images and sounds from the assets folder for use in the game
Game.py - manages the main game loop, state transitions, player interactions, enemy spawning, power-ups, and game rendering
Bullet.py - defines the Bullet class, handling movement, rendering, and distinguishing between player and enemy bullets
Clock.py - implements a simple clock system to track time progression and manage frame-based transitions
CollisionHandler.py - manages collision detection between bullets, enemies, and the player, handling explosions, score updates, and game state changes
Config.py - defines global configuration settings, including canvas dimensions
Effect.py - handles visual effects for power-ups and score indicators, managing sprite animations and tracking their completion
Enemy.py - defines the Enemy class, managing movement, shooting behaviour, and rendering using a sprite-sheet
EnemyManager.py - handles enemy spawning, updates, and interactions, ensuring enemies appear at controlled intervals and move on the screen
Explosion.py - manages explosion animations and sound effects, displaying them at a given position and marking them as finished when the animation completes
GameState.py - defines the different states of the game using an enumeration, such as start, in-game, and game over
Player.py - manages the player character, including movement, shooting, power-ups, shields, and interactions with the game environment
Powerup.py - handles power-up items, including their effects, movement, and rendering on the screen
PowerupEffect.py - defines different types of power-up effects, including increased fire rate, a protective shield, and extra health
PowerupManager.py - manages the spawning, activation, and expiration of power-ups, ensuring they interact correctly with the player and game mechanics
ScoreIndicator.py - displays animated visual effects when the player earns points, using different sprites to represent score increments
Sound.py - manages background music playback, including looping, playing, and stopping the music during the game
Spritesheet.py - handles the animations of objects in the game
Vector.py - defines a Vector class for 2D vector operations such as addition, subtraction, scaling, normalisation, dot product, rotation, and reflection

