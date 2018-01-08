# Star-Wars-Game
Star Wars Game Assignment



This assignment is a fun and interactive game for web browsers. The app must dynamically update the HTML pages with the jQuery library.

Here is how the app works:

When the game starts, the player will choose a Character by clicking on the fighter's picture. The player will fight as that Character for the rest of the game.
The player must then defeat all of the remaining fighters. Enemies should be moved to a different area of the screen.
The player chooses an opponent by clicking on an enemy's picture.
Once the player selects an opponent, that enemy is moved to a Defender area.
The player will now be able to click the Attack Button.
Whenever the player clicks Attack, their character damages the defender. The opponent will lose HP (health points). These points are displayed at the bottom of the defender's picture. 
The opponent character will instantly counter the attack. When that happens, the player's character will lose some of their HP. These points are shown at the bottom of the player character's picture.
The player will keep hitting the attack button in an effort to defeat their opponent.
When the Defender's HP is reduced to zero or below, the Defender is removed and the player Character can now choose a new opponent.
The player Wins the game by defeating all enemy characters. 
The player Loses the game if their Character's HP falls to zero or below.

Game design notes:

Each character in the game has 3 attributes: Health Points, Attack Power and Counter Attack Power.
Each time the player attacks, their character's Attack Power increases by its base Attack Power. For example, if the base Attack Power is 6, each attack will increase the Attack Power by 6 (12, 18, 24, 30 and so on).
The enemy character only has Counter Attack Power. Unlike the player's Attack Points, Counter Attack Power never changes.
The Health Points, Attack Power and Counter Attack Power of each character must differ.
No characters in the game can heal or recover Health Points. 
A winning player must pick their characters wisely by first fighting an enemy with low Counter Attack Power. This will allow them to grind Attack Power and to take on enemies before they lose all of their Health Points. Healing options would mess with this dynamic.
Your players 
