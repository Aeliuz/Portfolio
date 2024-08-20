# Swift G4

[Itch.io](https://yrgo-game-creator.itch.io/swiftg4)

[Github repository](https://github.com/SebbGameCreator/SwiftG4)

## Game description
Swift G4 is a Mirror's Edge inspired parkour game, where you try to outrun an explosion. Find the most effecient path and improve your time!

# My contribution

## Movement system
I was in charge of creating the movement system for the game. I'll break down the movement to it's component parts.

## Running and jumping
Since the game is about running and maintaining a high speed this was a small but crucial part. We experimented with having a sprint function in the game, but since everyone enjoyed sprinting and felt slow when not using the sprint, I chose to make the sprint acceleration the default.
Jumping in the game is a simple part and we decided that the time jump key is pressed controls the amount of elevation you get, this gives the player more control.

## Vaulting
Being able to quickly jump over low obstacles and maintain your speed is a very satisfying mechanic. For vaulting as well as for climbing and wall running i created a system that checks what is in front of the player and the game reacts appropriately. 

## Climbing
Using the same system as for vaulting, the climbing animation is activated for higher obstacles. Limits with this had to made so that the player doesn't climb where they shouldn't be able to or walk into walls.

## Wall running
For the game to allow the player to run on the wall, the player has to have some speed parallel to the wall, this is so a wallrun can't be activated by running straight into a wall. Once wallrunning, the player moves along the wall in an arch and is able to jump from the wall in the way they are looking (with restrictions).

