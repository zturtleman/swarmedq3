## Introduction ##
Swarmed Quake 3 is a mod that pits you and up to three of your friends in a fight against waves of incoming enemies. These enemies are all AI controlled bots which you have to frag to progress to the next round. Each consecutive round is harder than the previous. Passing all the rounds resets you to the first round but at a higher difficulty level.

Swarmed Quake 3 takes many gameplay cues from Gears of War 2's Horde mode but strays far from it when it comes to pacing and tactics.

## Goals ##
Some goals for a first _alpha_ release of this project are:
  * Implement a framework for initializing and handling progress through waves.
  * Making it possible to spawn bots into the game with a specific weapon and prevent them from picking up additional weapons/items.
  * Make it impossible for a player to join the bots team.
  * Get rid of a bot when it's fragged.
  * Implement a "lives" system where the players share a set number of lives. Each player death subtracts a life. When no lives are left, the game is over.
  * Implement a "game over" state of the game.
  * Implement a "game won" state of the game.

These features should make it possible to play the SwarmedQ3 game in a very basic form. After that some level of polishing will be applied. The goals for a _beta_ release are:
  * Implement countdown before starting each next wave.
  * Implement some anti-cheat measures, such as not being able to win the game by kicking bots.
  * Clean up the scoreboard so bots aren't shown.
  * More to come, without a doubt...

Note that these goals may be subject to change :-)

## Releases ##
There are currently no available releases.