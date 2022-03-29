# GravLab

Authors: Matthew Conway, Dean Gumas

Date: October 29th, 2019

Purpose: Video Game Design Final Project


## About

Welcome to GravLabs! Professor Newt has flipped the space time continuum
and unleased the power of variable gravity on the universe. You are a young
scientist who has learned the ability to control your own gravity. Using
w, a, s, and d, your character can change gravity within the platform game.
With i, j, k, and l, you can move your character along a platform (These keys
are relative to your gravity, so their actual movements change but it is
intuitive). The scientist also has the ability to throw gravityballs, which
travel in projectile fashion according to his gravity. Througout the game,
the scientist will learn all of his abilities, and the instructions are
displayed to the player.

This game is based off the mechanics of a platform game, with the added twist
of controlling the gravity of the main character. The scientist dies by falling
off the map or running into an adversary on the map. When the scientist dies,
the level restarts. To finish a level, travel through the portal at the end
of the level to advance to the next. In the final level, the scientist will
face Professor Newt, where he must shoot him down to win the game. When the
user wins the game, a winning animation is displayed and the game returns to
the main menu.

There are many obsticles and elements that the scientist will encounter on his way
to finding Professor Newt on planet Zeltron. Each obsticle/element will be listed
below with explainations on their function within the game:

1. Platform blocks - These are the standard blocks for the scientist to
                land on throughout the game, with a green color.
                They do not change at any point. To land on a platform
                block, set the scientists gravity such that he falls on
                the block.

2. Portal blocks   - These are black blocks with small objects inside them,
                usually at the very end of the level. By coming in contact
                with this block, the scientist travels to the next level.

3. Chest blocks    - These are tan blocks scattered throughout the levels in
                the game. Collecting the chests increases the scientist's
                overall score. This score is saved at the end as a high score
                and determines overall quality of play outside of finishing.

4. Ammo boxes      - Ammo boxes contain 10 balls for the scientist to carry and
                shoot. If you get close enough, 10 balls will be added to
                the ball count in the top right.

3. Brick blocks    - These are the red brick blocks scattered throughout after
                level 4 (This is when the user gets the ability to throw balls).
                Throwing a ball at the brick will break it, unlocking new
                paths through the map.

4. Fly             - There are two types of flies, vertical and horizontal. For each,
                they travel in their relative direction back and forth in the map.
                If the scientist runs into one of the flies, he dies and the level
                restarts. There is no way to kill flies.

5. Slime           - Slime blocks are light blue in color and bounce up and down on the map.
                If the scientist comes close to or in contact with a slime, it will
                push him in the direction relative to which they made contact, and will
                likely send him off the map to die. There is no way to remove slime.

6. Professor Newt  - Professor Newt is at the end of the last level. He moves laterally, then
                flips his gravity. Once he lands on aother surface, he begins moving again.
                If a ball is close to him, he will prematurely reverse his gravity to
                avoid the balls. Take this into consideration when trying to kill him.


## For Grading

There is a way to skip through each level. By pressing the '+' character in a level,
the game will advance to the next level. If you reach the last level and press the '+'
character, the game will end and the winning animation will show. You can also do this
by advancing to the end and killing Professor Newt. To simulate the loss, simply fall
off the map.

Certain elements are introduced at certain points. Below are the list of what and when:

Level 1:
- Moving using i, j, k, and l
- Flipping gravity using w and s
- Chests
- Portals

Level 2:
- Flipping gravity using a and d

Level 4:
- Breakable blocks
- Ammo boxes

Level 5:
- Fly adversary

Level 7:
- Slime adversary

Final Level:
- Professor Newt
