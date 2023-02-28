# Antiquity Game Project

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

Tutorials and resources used:
- https://www.youtube.com/@quill18creates
- https://www.youtube.com/@unity
- https://www.youtube.com/playlist?list=PLkx8oFug638oaqxmw2Xm-VEq9CyYWyYzn



# Breakout Game Project

## Introduction
The purpose of this project was simply to increase my understanding and knowledge of the Unity Game Engine. This is my second game project using Unity. 

## Overview

This is a simple "Breakout" game where players are given a paddle to control and must knock out the blocks in the air. If the ball falls behind the paddle, the player will lose a life, and their score will be affected. There is a level progression system where players start with an easy level, and go up to harder levels. 

This project incorporates:
  - Physics based collision using colliders and RigidBody components on the ball and objects
  - Code was designed for scalability. New levels can easily be added without much work.
  - Ability to be played on Android

## Custom Features

Applied Game Features and Mechanics:

- Main menu with level selector
- Settings menu
- After not colliding with anything, the ball will begin to fall down so it won't be stuck bouncing between the boundary walls.
- In-game pause menu with options to restart or exit game
- Victory/Defeat screen showing score and more options


# Infinite Runner Game Project

## Introduction
intro

## Overview

overview

This project incorporates:
  - stuff

## Custom Features

Applied Game Features and Mechanics:

- features
- mechanics
