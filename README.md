# Superbort

// hier irgendwie ein general bild von gameplay, aber auch irgendwie weitere bilder in laufe der README

// ihr musst vlt mir das schicken das ich einbauen kann bzw ihr baut das selbst in die readme ein über github

// wir müssen mal schauen ob man auf die einzelen git accounts verweisen kann

// auch irgendwie vlt 2,5D erw#hnen?

## Project Description & Gameplay

Superbrot is an isometric action game inspired by Vampire Survivor and Superhot. The player controls a sentient piece of bread fighting against hostile birds in a dystopian world. Enemies attack in waves using melee charges and projectiles. The core gameplay twist is time manipulation: time slows down and eventually goes near to zero when the player does not move, allowing for tactical positioning and precise combat. The game is played using WASD movement with mouse-based aiming. The player gets after every wave a reward for now every even round a new weapon and all uneven waves and upgrades that buff all current weapons.
Surviving waves and managing positioning during time slow are key to success.

## Main Challenges & Solutions

One of the main challenges was implementing the time manipulation mechanic in combination with animations and enemy behaviour. This was solved by controlling time scaling and adding short residual movement to keep the game feeling dynamic. Additional challenges included working with tile-maps, subclass-based architecture, and understanding code written by other team members. UI Toolkit was also difficult to learn due to limited learning resources, but prior CSS knowledge helped speed up the process.

## What Went Well & Lessons Learned

The initial project scope was too ambitious, but the core idea and main mechanics were successfully implemented. The time-stop feature works as intended and gives the game a unique identity. While additional features such as more waves, weapon upgrades, and polishing are still needed, the foundation is solid. Overall, the project was a valuable learning experience in game architecture, teamwork, and iterative design.

## Who did what

### Paul

### Andrey

### Friedrich

### [Benjamin Winde / RengoWin](https://github.com/RengoWin)

- Designed the initial enemy spawning system, including configurable enemy data, spawn limits, multiple spawn points and basic movement towards the player.
- Designed and implemented the core weapon architecture and several ranged and melee weapon types, including pistol, shotgun, rocket launcher, swords and spear.
- Refactored the weapon system by separating player input and weapon handling responsibilities into dedicated components.
- Implemented reusable pickups for health, ammunition and temporary player buffs.
- Designed and implemented a flexible upgrade system for player and weapon stats using additive and multiplicative modifiers.

#### Personal Takeaways

This was my first larger group project and gave me my first experience developing a game as part of a team. During the first weeks, I also helped coordinate and distribute tasks within the team. Working together with another programmer taught me more about designing systems that could later be extended and integrated by someone else. On the programming side, I gained more practical experience with inheritance by using shared weapon classes to build different ranged and melee weapons.
