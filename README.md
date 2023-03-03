# Antiquity

<div style="width: 1000px; height 600px;"><img src="https://github.com/edwarddemy/AntiquityGameProject/blob/main/a3.PNG?raw=true" width="25%" height="25%" align="right"></div>


## Introduction
The purpose of this project is to utilize my aquired skills, increase my knowledge on app development, and gain experience from creating and publishing a game. This is my third game project using the Unity Game Engine. 

Currently it is being worked on two people, including myself. The other person is working on a different part of the game, while I am working on the main gameplay loop. All work shown and presented is my own. Acknowledgements and tools I've used will be linked below. It's important to note that all visuals are placeholders for now! Eventually we plan to remake the UI and appearance of the game.

## Overview

This project is a turn-based strategy game set in the older ages, where the objective of the player is to win by controlling a majority of key areas. The player may do this in a variety of ways, such as using combat units, managing their economical power, researching new technologies, and more. The area of the game is played on a hex grid painted with functioning terrain and resources.

<div style="width: 1000px; height 600px;"><img src="https://github.com/edwarddemy/AntiquityGameProject/blob/main/a5.PNG?raw=true" width="30%" height="30%" align="right"></div>

This project incorporates:
  - Unit pathfinding using a self-implemented Dijkstra's algorithm to find all possible paths for a unit
  - Local Multiplayer using "Fish-Networking" developed by FirstGearGames
  - Generated hex grid, terrain, and resources using Perlin Noise
  - Usage of PlasticSCM as source control in conjunction with Unity Engine

## Custom Features

<div style="width: 1000px; height 600px;"><img src="https://github.com/edwarddemy/AntiquityGameProject/blob/main/a6.gif?raw=true" width="50%" height="50%" align="right"></div>

Applied Game Features and Mechanics:

- Main menu and lobby
- Unique world generation each startup
- Unit creation, movement, and a basic attack on opponents
- Structure creation and abilities, such as the ability to load units onto transport ships
- Individual player inventory
- Resource collection
- Ability to research and employ technologies
- "Fog of War", where the players are not able to see the hexes they have not explored yet
- Ability to stack multiple units on a single hex, while still retaining the ability to control them individually

### Acknowledgements

Unity plugins used:
- https://github.com/FirstGearGames/FishNet/
- https://github.com/VeriorPies/ParrelSync

Resources and references used:
- https://www.youtube.com/@quill18creates
- https://www.youtube.com/@unity
- https://www.youtube.com/playlist?list=PLkx8oFug638oaqxmw2Xm-VEq9CyYWyYzn
