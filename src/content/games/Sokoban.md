---
title: "Sokoban"
description: "Group project as 5 Gameplay Programmers, inspired by the classic Sokoban game, with a windy special feeature !"
gametype: "Puzzle Game"
order: 2
engine: "Godot C#"
heroImage: "/SokobanHero.jpg"
heroVideo: "/Sokoban_Video.mkv"
---

This was my first group project. The goal was to make a classic Sokoban game, which is a puzzle game where the player has to push boxes around to help them reach their targets, with a special feature. We chose to add wind currents that can push both the player and lighter boxes but can be blocked by heavier boxes. Through this project, I learned how to use Git.

<h3>My main tasks were:</h3>

- Development of the special feature system and main gameplay system: I coded all the interactions between the player and boxes, as well as all interactions with the wind.

- Implementation of the wind current visuals through object pooling for trails, reactive to their environment as they can be blocked.

- Development of the save and login system, using JSON to save and load data.

- Designed a level of the game.

- Implemented many player feedback and gamefeel effects.


<h3>GameFeel of the game:</h3>

We wanted a dreamlike experience for the player that feels light and relaxing. I implemented several effects to achieve this:

- The tiles the player walks on slightly sag, emphasizing the feeling of walking on a cloud.

- The cloud islands each float slowly at their own speed.

- The path the player will follow using pathfinding glitters in gold, giving a magical feeling to movement.

- The clouds slowly drop small particles.