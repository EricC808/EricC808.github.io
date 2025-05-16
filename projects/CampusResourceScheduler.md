---
layout: project
type: project
image: img/logo-text.png
title: "Campus Resource Scheduler"
date: 2023
published: true
labels:
  - Website
  - TypeScript
  - Bootstrap
summary: "A website where all UH campuses students can borrow resources for use."
---

<div class="text-center p-4">
  <img width="500px" src="../img/HP.jpeg" class="img-thumbnail" >
</div>

<div class="text-center p-4">
  <img width="500px" src="../img/AdminHP.jpeg" class="img-thumbnail" >
</div>

## Overview

For this project, it was completed as a group of four for our final project/assignment in my AP Computer Science A class. We made this program entirely through the IDE Visual Studio Code in Java, which was the main focus of the class—learning the basics of Java and gaining experience and proficiency in it. The game is multiplayer, allowing up to four players at a time, each controlling their own avatar. The goal is to have the most bananas at the end of the timer. The game is playable only locally, fitting all four controls for each avatar on one keyboard. These controls consist of movement in all four directions (up, down, left, right) and an additional control to punch for collecting bananas, depositing them, and punching other players to eliminate them or hit their barrels to steal deposited bananas.

## My Role

For this project, I was in charge of finding the sprites to use and editing them to fit our game requirements. I also worked on the code for the barrels and hearts, specifically focusing on detecting when to update the images for each player’s barrels and hearts. For the barrels, we ensured the game started with every barrel being empty with no bananas. We maintained a count variable that updated whenever it detected if the player of the matching color had bananas and if they punched the barrel to deposit them. If these conditions were met, the count would increase. When the count of bananas was greater than 0, the sprite would change, if it exceeded 10, it would change again, and if it reached 20 or more, it would change to a final sprite until bananas were lost. For the hearts, at the beginning of the game, we ensured all hearts were full, and their images would change if the player was punched by an opponent. The heart had four stages: full, two-thirds, one-third, and empty. It would change sprites each time the fist sprite collided with the monkey sprite.

## Lessons Learned

From this project, I learned how time-consuming it is to develop a game from scratch, not only in terms of coding but also in designing the visual aspects with sprites and images that fit the theme. We didn't have the time to create our own sprites, but even finding them online and editing their colors and appearance to match our theme was very time-consuming. This was also my first major group project where we created a game from scratch, which taught me new time management skills. As the deadline approached, we had to work outside of class to complete the project. Additionally, this experience built my skills in various areas, such as using Visual Studio Code, since I was relatively new to it. I also learned about collaboration and integration, as different people worked on different parts, and we had to ensure everything came together and was compatible in the end.

Here is the link to the Code: [Primate-Pandemonium]((https://github.com/EricC808/Primate-Pandemonium.git))
