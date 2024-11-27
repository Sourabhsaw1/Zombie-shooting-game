# Zombie-shooting-game
This game is a 2D zombie shooter where the player fights against waves of zombies. The game runs on a canvas element and uses JavaScript to handle all the game mechanics, including player movement, shooting, zombie spawning, and collision detection.

Core Components:
Player Movement: The player can move around the screen using the mouse. The movement is controlled by updating the player's position based on mouse coordinates, with the player being represented by a circle and a weapon (which is a rotating gun).

Weapons: The player has access to multiple weapons, including a revolver, shotgun, machine gun, sniper rifle, minigun, laser gun, and more. Each weapon has different properties, such as reload time, bullet speed, and fire rate.

Zombie Behavior: Zombies are randomly generated on the screen and try to move toward the player. When a bullet hits a zombie, it is destroyed, and the player earns points. There are different types of zombies, some special ones that provide power-ups, such as new weapons or extra lives.

Bullets and Shooting: The player shoots bullets in the direction of the mouse. The bullet properties depend on the current weapon, and each weapon has its own shooting pattern and reload time.

Game Modes: There is a "softcore" mode with basic weapons and a "hardcore" mode with stronger enemies and more challenging gameplay. The difficulty increases as more zombies are killed.

Health and Lives: The player starts with a set number of lives. Each time a zombie hits the player, they lose a life. If all lives are lost, the game ends with a "Game Over" screen showing the number of zombies killed.

Special Power-ups: Some zombies drop power-ups, such as new weapons or extra lives. These power-ups are randomly distributed when a special zombie is defeated.

Graphics and Visuals: The game uses basic graphics with shadows, colors, and shapes drawn using the HTML5 canvas API. Zombies and bullets are rendered as circles with varying sizes, and the player is represented by a rotating gun.

Audio/Effects: While no explicit sound is mentioned in the code, the game can include sound effects like gunfire or zombie death sounds in the future.

Game Over:
When the player's lives run out, the game ends, displaying a "Game Over" message along with the number of zombies killed. Players can restart the game by pressing the "Enter" key.

Controls:
Mouse: To aim the weapon.
Left Mouse Button (or click): To fire the weapon.
Keyboard (Enter): To restart the game after it ends.
This game is a simple yet engaging way to practice JavaScript game development using canvas, handling object-oriented principles (like player and zombie classes), and applying basic game physics (movement, collision detection, etc.)
