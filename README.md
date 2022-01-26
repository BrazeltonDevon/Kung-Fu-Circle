# Kung-Fu-Circle
The goal of this research topic is to create an AI that uses a so-named "Kung-Fu Circle".
This means that enemies will gather around a player and attack one at a time (similar to eastern martial arts movies).

*The player will have a grid with a capacity for enemies and a capacity for attacks
*Enemies have a weight and their attacks have a weight
*Every attack an enemy makes (one-by-one) takes from the current attack capacity, every enemy in the circle takes from the enemy capacity.
*If an enemy approaches and their weight is > than the player's current capacity, they cannot fight him.
*If an enemy's attack costs more than the remaining attack capacity, it tries to choose a lower costing attack or doesn't attack.
*Once every enemy has attacked, the attack capacity is reset to the maximum. When an enemy dies, their weight is removed from the current enemy capacity.

A good example of this sort of combat AI is found in the game 'Kenshi'.
