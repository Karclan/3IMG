---
Topics:
  - "[[Project Design]]"
  - "[[Procedural Runner]]"
tags:
  - In_Progress
Created: 2026-09-09, 7:10:30
Modified: 2026-09-09, 7:47:22
---

# Project Idea 3: Friends Smash
A procedurally generated labyrinth map with isometric view, going forward/upwards infinitely collecting coins to make a score. There is a bonus points item and a bonus multiplier bar. You get more points the further you go as well.

We gonna have our friends be characters in the game. Each friend is gonna have a special ability and they can also be foes. If a character is selected as the player. It can not show as a foe. The abilities should be simple and straightforward pun or jokes about them. Ex: Chimmy coming to save the chat from NSFW Ex: Jinxxy popping a bottle to make her faster but also drunk

Example characters and powers:
- Chimmy: Something about NSFW banning
- Jinxxy: Popping a bottle to make her faster
- Mango: Starts talking shit and people run away from him.

Livy is keen on the idea of people having different theme songs that play when they are selected.

Lets start with a few characters as to not break off more than we can chew. 
Initial starting characters:
- Livy
- Castell
- Karclan

Non playable characters: 
- Alex - Shop keeper for upgrades?
- Castell can fill in the rest.

Changing the map colour based on player too.
- Livy wants pink

## References
The idea is based on the Nikke Persona minigame that is no longer available
The map is procedurally generated
![[Pasted image 20260909152046.png|212]]

![[Pasted image 20260909152128.png|350]]

There is a wall that goes up as well in a slower pace than the player so it keeps people from coming back.
![[Pasted image 20260909152225.png|439]]

The player has a health bar. Everytime the players get hit by a foe it goes down a bit.
There is also a score meter and a distance meter. 1m = 250 score, Each coin is 150.
![[Pasted image 20260909152304.png]]
The skill fills up with time, but it also has items to add a bit to the meter.
It triggers when it's full automatically and it lasts for about 30s
Music changes when it triggers
![[Pasted image 20260909152457.png]]

One of the foes always moves side to side on a line
![[Pasted image 20260909152636.png]]
One of the foes is a wood tree that does not move, until the player get close to it and then it starts following the player, but it's slower than the player and it stops following after a little bit.
![[Pasted image 20260909153147.png]]![[Pasted image 20260909153132.png]]

This character is faster than the player, but it doesn't follow the player. It moves towards the first direction the player shows up from in the line of sight of it and goes until it hits a wall.
It can move again after it has hit a wall. The player can trick it, by making it move in a direction and then hiding for a second and going to the other direction.
![[Pasted image 20260909153716.png]]

This foe comes from the top and it goes down through the fastest way possible. It seems to follow the direction of the player slightly, but it always prefers to go down the lane instead of attacking the player.

![[Pasted image 20260909154007.png]]

This foe comes from the top of the screen seemingly out of nowhere and it follows the player with the same speed as the player. It is extremely annoying.
![[Pasted image 20260909153830.png]]

Bombs create a radius of effect and it blows up in 15 seconds or so or when you touch a foe. It does not damage the playe
![[Pasted image 20260909152958.png]]

This item is a double points item. It creates a meter on the screen that makes every point doubled for 15 seconds.
![[Pasted image 20260909154137.png]]

When you die you get a score and a rank. We could have random funny quotes in the end.
![[Pasted image 20260909154227.png]]