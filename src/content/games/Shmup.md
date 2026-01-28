---
title: "Shoot'Em Up"
description: "First project, in association with a Sound Design student. Arcade Shmup with a boss phase in sync with music"
gametype: "Action / Arcade game"
order: 0
heroImage: "/ShmupHero.png"
heroVideo: "/Shmup_Video.mp4"
---

The goal was to create a fast-paced action game satisfying to play with the use of a lot of player feedbacks.

I developped 100% of the game except for all the music and sound design part. 
Through this project, I learned and worked on: :

- Usage of the Godot 4 engine

- Object-Oriented Programming principles: Encapsulation, Inheritance, and Polymorphism

- Basics of the GLSL language through a vignette shader

- Game feel through juiciness, player feedhback, and forgiveness mechanics

- Game design for enemy and boss movement and shooting patterns, with the use of mathematics for implementation

- Design and implementation of a player special ability: bullet-time dashes using a simple state machine

- Basics of Photoshop for UI and in-game assets

- Level Design

- Implementation and design of the First Time User Experience (FTUE)



<h3> I was heavily focused on GameFeel while developing this project : </h3>

Forgiveness mechanics: the player hitbox is smaller than its visual, but its hitbox for dealing damage to enemies while dashing is larger. This setup allows the player to make precise moves while still feeling challenged, without the game explicitly assisting or overpunishing them.

Visual feedback: enemies flash white when hit, the player sprite blinks when invincible after taking damage, and bullets create particle splashes when hitting walls.

Visual effects: screen shakes to emphasize laser impacts, enemy explosions made with particles, thruster trails for spaceships and rocket trails for projectiles.

UI feedback: score popups move toward the score counter and make it bounce when reached; collectibles behave similarly, moving toward their UI icon with a small bounce on arrival.


