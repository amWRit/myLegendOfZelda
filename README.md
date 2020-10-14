# amWRit

# LegendOf50

As part of learning through Harvard's CS50G "Introduction to Game Development" course, recreating the Legend of Zelda game using Lua and LOVE2D.
Updates were made on the original source code provided by CS50, based on assignment specifications.

__Assignment 5: “Legend of Zelda, The Pot Update”__

__LOVE 11.3__

# Assignment Updates

__Hearts__
- When an enemy is vanquished (dead), a heart might be spawned at random. Right now, there's a 50% chance.
- When the player consumes the heart, health is healed by a full heart. 

__Pot Spawn__
- Generate a pot at random position.
- The player can use 'Enter' key to pick up pot. 
- When the pot is picked up, the player goes into a different state- can't use sword and also the animation is different.

__Pot throw__
- If the player has picked up a pot, it can throw the pot using the same 'Enter' key. 
- The pot can travel 4 tiles distance in direction of the player and break. 
- The pot breaks if it hits the wall.
- If it hits an enemy at the distance, it does damage to the enemy.
